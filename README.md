# Xbox-Game-Pass
A breakdown of the Xbox Game Pass (XGP) game catalog into easily digestible trends and visualizations, to gain a better understanding of what this service includes and to quantify its value to a typical subscriber. The bulk of the data used herein was scraped from Microsoft's own Xbox Game Pass [website](https://www.xbox.com/en-US/xbox-game-pass/games), using the Beautiful Soup and Requests Python modules.

### Game Access By Subscription Tier

A bit of background on the service in question, XGP is offered in one of three tiers: console-only for $9.99 / month each, PC-only for $9.99 / month, or the aggregate of the two for $14.99 / month. Games included in this service fall into one of two main categories, those available on both Xbox and PC (dual platform), and those available on only one platform or the other (single platform). As of 09/27/20, the service included 296 games, with 52% (154) falling in that "dual platform" category. Of the remaining 48% (142) of games, the breakdown is: 31% (92) Xbox-only and 17% (50) PC-only. Subscribers to the Xbox-only and PC-only tiers would have access to 83% (246) and 69% (204) of the grand total games. Based on the equivalent price structure for the segmented tiers, one would have expected a tighter spread between the two.

### Microsoft Store Price Analysis

Using game prices scraped from the [Microsoft Store](https://www.xbox.com/en-US/microsoft-store), the total value accessible to each of the three subscription tiers would look to be rather impressive. Combined, highest tier subscribers gain access to $10120.76 worth of games, branching off into $5321.06 and $6524.04 for PC-only and Xbox-only subscribers, respectively. Remember here that since there is some overlap in game availability for both platforms, the sum of the segmented tiers will be greater than the value of the highest subscription. Some other quick stats here: 
  * most common game price is $19.99 with 108 games, followed not too closely by ($29.99, 51), ($39.99, 46), and ($14.99, 43)
  * average game price is $26.36
  * a total of 26 unique game prices

Based solely on the sums and subscription prices above it would take 532, 562, and 675 months to break even (assuming no other games were added). Realistically, if the potential subscriber were diligent on picking up games when on sale then this figure would be far, far lower. But, just how much lower are we talking? From this point onwards we deal with PC-only and dual platform games since Xbox hardware do not currently support games from third-party game distribution services (like Steam, GOG Galaxy, Epic Games Store, and so on). Historical lows for all PC-only and dual platform XGP games were scraped from a [PC game price comparison website](https://isthereanydeal.com), summing to $2034.33. This $3286.73 price delta highlights two things: how stagnant / high the prices are for games on the Microsoft Store across the board, and also the tangible benefit of waiting to purchase games as prices drop over time. Both these topics are outside the scope of this analysis, though this would perhaps be another interesting avenue to explore at a later time: which games stores had greater sales, more frequent sales, or were consistently underpricing other game stores.

### Developer, Publisher, And Game Genre Trends

This section remains incomplete, to be filled in at a later time.
