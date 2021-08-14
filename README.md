# nba2k-exploratory-analysis
As professional sports, and in particular basketball, increasingly embrace analytics, the metrics used to assess players' performance become more numerous and complex. It is no longer sufficient to merely consider average points per game when assessing offensive ability or blocked shots when determining defensive prowess. More sophisticated metrics such as true shooting percentage, real adjusted player efficiency rating, and Per 87.5 have been developed in hopes of better quantifying a player's value. Yet, despite their mathematical sophistication, no collection of metrics will provide an objectively correct assessment. Instead of considering numerous complex statistics one could take a reductionist approach by creating a simple metric that sacrifices correctness for ease of use. Indeed, what if instead of developing increasingly advanced metrics we took the opposite approach? What if we sought to distill a professional basketball player's skill level to a single number? What would such a number look like? In fact, such a metric already exists.

The NBA 2K video game franchise has a released a game for each of the last 21 NBA basketball seasons and in each entry every active NBA basketball player is assigned a rating on scale from 1-99, where higher scores correspond to better players. In practice most players receive a score of 60 or above. In this way, each player's skill is summarized into a single number allowing for easy, interesting comparisons.

In this project I collect and analyze this player rating data which is web scraped using the popular html parser Beautiful Soup. Then using Pandas and Matplotlib I endeavor to reduce the last 21 years of NBA history into simplistic quantitative terms.
