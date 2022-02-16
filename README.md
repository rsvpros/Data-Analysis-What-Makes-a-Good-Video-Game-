Ravi Shankar - 12/14/21


# Video Narration

[Go to the following link](https://www.loom.com/share/b98a06e92b04414f8a0991fd6158de7d) to watch the video narration of the data analysis. 

# Question

What makes a "good" (highly rated) video game? How do sales, platform, year of release, and age rating affect the composite critic and user score of the video game?

# GET

To Get the data in this project, the file 'Video_Games_Sales_as_of_22_Dec_2016.csv' is imported into the rshanka4.ipynb file.

[Data originally retrieved from this site](https://www.kaggle.com/rush4ratio/video-game-sales-with-ratings)

In the rshanka4 file it is cleaned and titles without ratings are dropped. A "Composite_rating" feature is added as well, averaging "User_rating" and "Critic_rating".

# Model

A bayesian bootstrap linear regression model is set up in the "rshanka4.ipynb" file. I reference the "models.py" resource for linear regression, created by Dr. Stephyn Butcher.

# Conclusion/Recommendations to Video Game Makers
The data suggest that to make video games with the highest user and critic rating, one should:

- Consider making an M-rated game. They tend to get higher scores on average (with a 95% bayesian confidence interval), possibly because they explore more complex themes than more age-friendly games.
- Consider developing for the PC gaming platform. PC games had higher scores on average, possibly because PCs tend to be more capable in terms of technological capability, which can possibly add to the game enjoyability.
- Genre makes a difference. My theory is games with more focus that fit into a preconcieved genre tend to recieve better scores. "Strategy" games had the highest rating on average of any genre, and "Miscellaneous" games had the lowest.
- Don't be afraid of selling a lot of games. Some may think that indie games with a niche community will score higher. However, since there was a positive correlation between sales and scores, commercial success does not tend to mean worse rating on average.


