# 18 - Naked Calls

This chapter is how to trade in the opposite direction: naked CALL options.

There are times that the market is in a downtrend, for example Q1-2 2022, when this happens we need to trade not PUTs but CALLs to be on the opposite side of the movement.

Summary:
1. Sell a naked call 20% out of the money (same rules for rounding up to the next furthest strike)
2. Put a triggered order in to purchase the stock if the price gets within $0.25 of the strike 
3. The resulting profit is Premium (s1) + Delta from strike (s2).

For example:
- Stock ZZZ current price is $40
- Sell CALL at $45, premium is $0.35
- When ZZZ raises to $44.75, purchase the stock. The naked call is now a covered call, net profit is $0.35 + $0.25 when executed.
- If the stock stays below the strike, keep the original $0.35 premium. 

The margin requirements for this are higher since you need to be able to cover the position by purchasing the stock.
- 10x CALL contracts @ $45.00
- Using margin, it requires $45/2 * 10contracts * 100shares-per-contract <=> $22.5 * 10000 <=> $22,500 capital
- Maximum profit is ($0.35 + $0.25) * 10contracts * 100shares-per-contract <=> $600 profit

**Notes:**
- The rules for CALLs and PUTs are the same, just opposite directions.
- Make sure to have at least 50% of the strike in capital to purchase the stock in the event of a negative move (price moves up).

🤞- Onto chapter 19 ...
