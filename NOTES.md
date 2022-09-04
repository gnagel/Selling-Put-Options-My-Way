# 12 - Trading Strategies

## How to pick a stock that fits

The key feature to look for is stocks that have enough volatility in their option premiums to be a good fit.
- Mr. Lee is indicating that he's looking for stocks with above average open interest.
- The filter we are looking for is above average premiums for out-of-the-money PUT contracts.

## Stock Filters:

1. Mr. Lee usually uses a stock in the $50-500 range. Below $50 & the relative move can quickly overtake your position. Above $500 there is no reason listed, but it's likely the lack of volume
   above this price range.
2. Strike price filter is 20%. Mr. Lee's filter is that the strike price of a PUT option must be at least 20% away from the current price of the equity. The general rule is to ROUND_DOWN
   (current_price % 0.80)
3. Avoid if there are earnings during the option's lifetime. Many companies will report earnings quarterly, this means that 4 months out of the year they are not something you can trade, honor
   this rule and avoid the stocks during this time.
4. Look back 2x years (min) to check for a pattern of monthly drops. If the stock has a pattern of dropping during a specific period, for instance a big-box chain may drop in the summer because the
   holiday season is many months away, then avoid the stock in those months.
5. Check the analyst recommendations. When the analysts are all bullish (uptrend), then it's a candidate for trading. When the analysts are bearish (downtrend), then it's out. As an addendum,
   avoid stocks that have a single factor pushing them, such as a biotech stock waiting on a single drug.
6. P/E (price to earnings) is king, the PE multiple is the number of years the company would need to grow in order to pay back the current equity price. The PE will tell you if a stock is
   overvalued or undervalued. A positive PE indicates a profitable company, but a NULL PE indicates an unprofitable company.  
   This is important because some companies can be skewed by financial tooling, e.g. AMZN @ 1000x PE.
7. Will the return of the position be covered by the maintenance cost of a position? For example, a $125 strike would require $1075 in maintenance and has a $0.75 premium, this results in a $0.
   75/10.75 <=> 0.069 return for the position. This is close enough to the target range of 3-6% that it's acceptable for the portfolio.
8. Open interest, if the O/I is less than 100 avoid it. This is a general rule for options traders since you want to avoid positions that have low volumes and can't be exited easily.

## Rules

Skip the PUT option if any of the following are a NO:
1. Is the stock within the allowed range [50,500], avoid if it is out of this range.
2. Is there earnings within the given option period, avoid the option.
3. Is there a history of downward price movement within the given option period, avoid when negative.
4. Is the analyst sentiment positive for the stock & industry, avoid when negative.
5. Is the P/E reasonable, avoid if it is overly inflated or too low for the industry.
6. Is the return for the position within the target range of 3-6% (premium / maintenance requirement) to cover the position, avoid when it is out of this range.
7. Is there 100x or Open Interest contracts, avoid if it is below this range.

---

# 18 - Naked Calls
- The rules for CALLs and PUTs are the same, just opposite directions.
- Make sure to have at least 50% of the strike in capital to purchase the stock in the event of a negative move (price moves up).

---

# 19 - Ways to Maximize Your Profits
1. When a position goes against you there are 3x choices: close the position, roll out, or roll out & down.
2. Generally the best move is to close the position.
3. Rolling out, or rolling out & down, can be done but should be avoided. 

---

# 21 - Options Traps That Might Mislead You

Red flags you should be wary of & avoid trading:
1. If there is an upcoming stock split, skip the position.
2. If the stock is a candidate for a merger or acquisition, skip the position.
3. If there are no options with sufficient premiums ratios (premium / maintenance requirement), skip the position.
4. If the stock continues to go up, so you would pick a riskier strike for more premium, skip the position.
5. If the conditions are perfect and there is a large premium, skip the position. and
6. If the stock and premium have dropped through the close trigger, but you want to hold on longer, close the position.
7. If your instincts are to close the position, but you want to hold on longer, close the position.

---

# 25 - Summary

**Rules:**
1. Do not get greedy (stick to the 3-6% ratio of premium / maintenance)
2. Use mostly stocks in the $50 - $500 range (too low and there's not enough volume, too high & it can fall faster than you can catch)
3. Use a strike price 20% or MORE below the current price (for PUTs, CALLs are 20%+ more)
4. Make sure no major news is upcoming: earnings, mergers, splits, dividends, acquisitions
5. A history of good price movement during this annual period (look back several years to compare seasonal price action)
6. Use stocks that have BUY recommendations from the analyst(s) (the more bullish the analysis is the more the stock tends to go up, which is good for PUT contracts)
7. Use stocks with a reasonable P/E (make sure the valuation of the stock makes sense for what they do & their industry)
8. Do not let looses run away from you (stick to the rules and close out a position early, rather than letting it run and wiping you out)
9. Never hesitate to take profits or losses when there are doubts about a position (if there is a profit to be made now, it's better than a loss to be made later)
10. Be suspicious if the premiums are "too good" (stick to the 3-6% ratio of premium / maintenance, if it's more than this move to a differient strike or stock)
