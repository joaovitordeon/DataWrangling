# Data Wrangling

This project aims to analyze data of Twitter account **@dog_rates**, also known as "**WeRateDogs**".
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
1. Gather: Process of obtaining the data. Here, we get data from tree different sources.
    - csv 
    - url
    - Twitter API 
2. Assess: The assessment is separated into two distinct stages.
    - quality: where we note the quality problems
    - tidiness: where we note the mess issues
3. Clean: In this step we cleaned the data marked in the assess process.
    - define: definition of quality or tidiness issue
    - code: code the issue
    - test: test to be sure of cleaning process with code
4. Analyze: Process of study and visualization of the information produced.

<br>

After all these steps we can present some interesting results:
- the number of occurrences of dog's life stages:

![ALT](/pics/img1.png "dogs's life stages count")<br>
***Here, we see that the number of puppers is much larger than the other 3 types***

- the correlation between number of retweets and favorites:

![ALT](/pics/img2.png "retweets vs favorites")<br>
***We noticed a good correlation (r = 0.86) between these two variables, which indicates that the more retweets, the more favorites this tweet will have***

- dog with the biggest rating numerator

![ALT](/pics/img3.png "biggest rating numerator")<br>
***Atticus is the name of the dog with the biggest rating_numerator(1776). He had 2637 retweets and 5379 favorites. What a style!***

- some avarage of posts

![ALT](/pics/img4.png "some metrics")<br>
***The average retweets per post is between 2000 and 3000, while average favorites per post is greater than 8000***
<br>

