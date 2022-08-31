# 04 - Options and Related Definitions

This chapter is mostly technical with some defintions a new reader wouldn't be familiar with.  
Anyone that's familiar with options trading can safely skip this chapter.

Option Contracts:
- Normally 100x shares <-> 1x option contract
- Purchasing a call gives you the right to purchase shares at a price.
- Purchasing a put give you the right to sell shares at a price.
- Selling one of the above goes in the opposite direction.

Underlying stock
- This is the equity (stock) you are purchasing

Premium
- This is the total value of the option at the given price
- For example if the bid = $0.30 & the ask = $0.40, and you sell it at the mid = $0.35.  You have recived $350 in premium (100 * $0.35)

Strike Price Codes
- Strike prices will scale to match the value of a stock
- From $2.50 -> $25.00 the strike prices are in $2.50 increments (2.5, 5.0, 7.5, ... 22.5, 25.0)
- From $25.00 and up the strikes are normally in $5 increments
- There is some variation, so higher volume stocks may have $1.0 increments in the strike prices

Expiration Dates
- This is the date in which an option expires.
- For many options this is quarterly: Jan/April/July/October
- The options may be issued every month for a 3mo window.  
- For example:
- - Jan/April/July/October
- - Feb/May/Aug/Nov, or 
- - March/June/Sept/Dec
- All standard options expire on the 3rd Friday of the month (and are settled at 12pm the next day, Saturday)
- NOTE: This has changed since the publishing of the book, there are now options that expire daily or weekly

Option Chain
- This is the table of all available options for a stock.
- The table contains: Strike price, Symbol, Bid, Ask, Last price paid, Voluime, Open Interest


Open Interest
- This is the number of option contracts that are open and have not been settled. (for example there exists a Call that has been sold, but not bought to close).
- This is calculated nightly for the previous trading day, and doesn't update intraday.
- For example if there were 10k calls sold, 6k calls purchased, the open interest is 4k for the calls at EOD.
- NOTE: The lower the open interest the less volume there will be, this means it will be harder to open or close a position later.

Intrinsic Value
- This is the value of the option if we were to close it immediately.
- Normally this the Stock Price - Strike Price, eg current=40, strike=38, intrinsic=2
- If the current price is less than the strike price, the value is 0.00

Time Value
- This is the amount above the intrinsic value of the option.
- For example in the `Stock Price - Strike Price, eg current=40, strike=38, intrinsic=2` example, if the option was 2.5 then the intrinsic is 0.5 <-> 2.5 - 2.0

Time Factor
- Options are a purchasable entity that expires.
- This means that at some point in the future, the option will either expire worthless (strike is >= stock price) or in the money (strike is < stock price).
- The rate at which this entity decays is controlled by the time and the volatility of the stock, but generally we can say that the option gets less valuable as the expiration date approaches.

Trade Triggers
- A trigger is an order that can be placed automatically when certain conditions happen.
- These are useful for allowing you to close a postion automatically if the market reaches some value, ex if the current prices is $48 we could close the position at $45 to limit loss.

Placing Orders
- BTO <-> Buy to Open
- BTC <-> Buy to Close
- STO <-> Sell to Open
- STC <-> Sell to Close

LEAPS
- Long Term Equity Position.  
- This is an option that starts on the January of the next year.
- These are typically used to establish a long-term position over time, however Mr. Lee uses them as short-term positions.
- For example:
- - Google is at $290
- - STO a Jan $220 put, 65x @ $7.68, on 6/20
- - BTC the Jan $220 put, 65x @ $3.80, on 7.25
- - Net profit is $25,200 <-> $(7.68-3.80)*65*100 <-> (sell price - buy price) * contracts * shares-per-contract

🤞- Onto chapter 5 ...
