# 10 - Let’s Start Trading

With chapter 10 we get more details on what Mr. Lee's method, selling naked PUTs.

## Crumb Method
Generally his method can be summed up as: sell out of the money PUTs far enough away from the current price to be unlikely to be executed.

This is called the crumb methods because it is effectively picking up crumbs from the table, and staying safely away from the action to be unlikely to be impacted.

**Note:** This is seen in other areas with CALLs as well. The typical analogy is picking up pennies in front of a steam roller, however based on his performance it may be more successful than the 
standard example.

## Capital
Generally you need at least $2k to open an options account, but his recommendation would be to start with as much capital (cash) as possible.

The more capital (cash) you have in your account, the more cushion you will have & the more you can increase your position sizing later on.

## Number of contracts you can sell
This gets back to the capital question.  If the broker uses the MAX(25% of current price, 10% of strike price) rule then the number of positions is a function of how much capital you have to work 
with.

For example:
- $10k in the account & 1x position
- $121 current price 
- Choose a strike 20% below the current price: $121 * .80 => $96.8 (round down to next strike) => $95 strike
- Assume the $95 strike has $0.50 premium

Margin calculation:
- $121 * 25% - out of the money + premium <=> ($121 * 0.25) - $26.0 + $0.50 <=> $30.25 - $26.0 + $0.50 ==> 4.75
- $95 * 10% + premium <-> $9.5 + $0.50 ==> 10
- Margin requirement is MAX(4.75, 10) == 10.00 per contract

Number of positions:
- Assuming we use all the available margin from $10k, we can have 10x contracts
- $10k capital / 10margin / 100shares ==> 10x PUT contracts

Position return:
- Using the assumptions above
- 10x PUTs * $0.50 per contract <=> 10puts * 100shares * $0.50 <=> $500 premium
- Return rate of 5% per month

Normally Mr. Lee claims to get 2.5-6% so this is a bit above average, but it does give a simple example of how this would work.
Using the rules of compounding interest we can see how this would grow rather quickly depending on the amount of starting capital.

The closing notes are to be cautious, getting greedy will result in your account being blown up and out of money.
This is about slow and steady growth, not explosive returns immediately.
If the position is returning something more than 6-7% avoid it, you are likely to get into trouble, and it will break your portfolio in the long run.

**Note:**
- The chapter closes on a warning, if the return is too good avoid it.
- Shoot for 3-4% return per position.
- If a PUT contract is returning more than that, move further away from the current strike price until it gets into the 3-4% range.

🤞- Onto chapter 11 ...
