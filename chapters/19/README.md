# 19 - Ways to Maximize Your Profits

This chapter is largely a summary on position management, how & why to close early, and how to roll your position away from risk.
An experienced option trader can skip this chapter, but it would be good to review as a refresher.

Summary:

1. Rolling to a different stock. This is an example of closing a position early to replace it with a second position that breaks the 20% rule but has only 1x week of time.

## Rolling to a different stock

1. 1st position, this is a STO (sell-to-open) a PUT contract @ $50, profiting $1080 in premium up front.
2. At week 3x, BTC (buy-to-close) the position for $0.05 in premium, profiting $980 in net premium.
3. After the BTC order is complete, open a second position in a stock with 1x week remaining (same expiration period as ZZZ) for $0.15. This is a 6% return on the position overall
4. The second position expires OTM for full profit.
5. The net profit is $980 + $600 <=> $1580, vs the original $1080 for the single position.

| Stock | Price  | Strike | Premium | Quantity | Duration |
|-------|--------|--------|---------|----------|----------|
| ZZZ   | $64.44 | $50    | $0.55   | 20       | Monthly  |
| ZZZ   | $64.44 | $50    | ($0.05) | (20)     | Monthly  |
| ZXZ   | ???    | ???    | $0.15   | 46       | Weekly   |

## Downside of the same trades

1. This is a risky position. 
2. There was a winning trade that could have run to completion for full-profit.
3. The second trade was unnecessary, and violated the 20% rule however it is a good example of "rolling up" the position.

Rolling up example, close the $40 strike position and open a $42.5 position in the last week.

| Stock | Price | Strike | Premium | Quantity | Duration |
|-------|-------|--------|---------|----------|----------|
| ZZZ   | $50   | $40    | $0.55   | 10       | Monthly  |
| ZZZ   | $50   | $40    | ($0.05) | (10)     | Monthly  |
| ZZZ   | $50   | $42.5  | $0.15   | 10       | Weekly   |

## Rolling Out or Down

1. This is an example of how to manage a trade that goes bad (stock price moves DOWN towards the PUT).
2. When a position goes against you there are only a few options
   - Close the position
   - Roll out (replace the current option for the same strike, 1x month into the future)
   - Roll out and down (replace the current option for a lower strike, 1x month into the future)
3. When we close the position we marking it as a loss and moving forward.
4. When we are rolling the position out we may take a small loss or profit, at the expectation that the new position will become favorable over time.
5. Rolling Out, or rolling out & down, can be risky.  We are effectively racing the price action downwards betting it will reverse, or we can out run it.

Roll Out: 

| Stock | Price | Strike | Premium | Quantity | Duration   |
|-------|-------|--------|---------|----------|------------|
| ZZZ   | $50   | $40    | $0.50   | 10       | Monthly    |
| ZZZ   | $45   | $40    | ($0.75) | (10)     | Monthly    |
| ZZZ   | $45   | $40    | $0.75   | 10       | Monthly +1 |

Roll Out & Down

| Stock | Price | Strike | Premium | Quantity | Duration   |
|-------|-------|--------|---------|----------|------------|
| ZZZ   | $50   | $40    | $0.50   | 10       | Monthly    |
| ZZZ   | $45   | $40    | ($0.75) | (10)     | Monthly    |
| ZZZ   | $45   | $37.5  | $0.75   | 10       | Monthly +1 |

**Notes:**


🤞- Onto chapter 20 ...
