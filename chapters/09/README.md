# 09 - Intrinsic and Related Time Value

This chapter can be skipped for anyone who is familiar with Option pricing already.

Intrinsic Value
- This is the amount by which the strike price is below the stock price for a CALL, and above the strike price for a PUT.
- For example, strike=40, stock=41, call=1.15 then the intrinsic value is $1.00 per contract:  MAX(stock-strike, 0) = 1.00
- For example, strike=40, stock=39, call=1.15 then the intrinsic value is $0.00 per contract:  MAX(stock-strike, 0) = 0.00

Time Value
- This is the rest of the option premium for the CALL or PUT
- For example, strike=40, stock=41, call=1.15 then the time value is $0.15 per contract:  optin - MAX(stock-strike, 0) = 0.15
- For example, strike=40, stock=39, call=1.15 then the time value is $1.15 per contract:  optin - MAX(stock-strike, 0) = 1.15

🤞- Onto chapter 10 ...
