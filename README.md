# Data Wrangling

This project aims to analyze Twitter account data **@dog_rates**, also known as "**WeRateDogs**".
For this, in addition to the open Twitter data, we will use an API to collect more data needed for a better and more complex analysis.
<br>

The data we have for each tweet are:
- tweet text
- dog rating(used by twitter account and its followers)
- dog's life stages(doggo, floofer, pupper e puppo)
- number of favorites
- number of retweets
- some extra data from API twitter

<br>

The organization of this project will be based on four points and its duly marked in the file `wrangle_act.ipynb`:
1. Gather
2. Assess
3. Clean
4. Analyze

<br>

After all these steps we can present some interesting results:
- the number of occurrences od dog's life stages:

![ALT](/pics/img1.ext "dogs's life stages count")
***Here, we see that the number of puppers is much larger than the other 3 types***

- the correlation between number of retweets and favorites:

![ALT](/pics/img2.ext "retweets vs favorites")
***We noticed a good correlation (r = 0.86) between these two variables, which indicates that the more retweets, the more favorites this tweet will have***

- dog with the biggest rating numerator

![ALT](/pics/img3.ext "biggest rating numerator")
***Atticus is the name of the dog with the biggest rating_numerator(1776). He had 2637 retweets and 5379 favorites. What a style!***

- some avarage of posts

![ALT](/pics/img4.ext "some metrics")
***The average retweets per post is between 2000 and 3000, while average favorites per post is greater than 8000***

