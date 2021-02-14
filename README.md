# TradeSkillMaster - New Price Sources
A fork of Tradeskillmaster for Wow that allows me to create my own custom Price Sources

## smartAvgSell
This source takes the average sell price for the last 30 days of history.  The intent of this Price Source is to smooth out volatile pricing, especially towards the beginning of a new expansion.

## numBelow[price]
The source will return the number of auctions below a given price.  The value can be a static gold amount, a formula, or another Price Source.  This Price Source will allow decisions to be made based on factors such as Sale Rate and Average Price.  If only a few auctions are listed under the average price, one may be able to assume that those auctions will be bought soon and therefore it is safe to list at the Average price.
