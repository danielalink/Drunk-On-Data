# Sentiment Analysis_2018 World Cup_Twitter
World Cup is one of the biggest sport events worldwide. 
Everyone shares their thoughts and emotions to each other especially when their own team is having a game.
We wanted to visualize the change of people's emotions from their team's performance.

We have used **pandas**, **tweepy**, **vaderSentiment**, and **gmaps** for our tools for this project.

## Limitations

1. The tweets we collected are only those written in English. This was because we wanted to equalize the language of our analysis. This might not represent the exact sentiments for countries whose most used language isn't English.

2. Need to be a paid user to pull data more than 30 days ago

## About

We wanted to see how people feel after their team play the World Cup games, but we had to set a standard to collect the tweets that we could consider as target samples.

We came up with the idea to collect the tweets that has been generated from 15KM from the center of the capitals.

We figured out that there are some built in commands in twitter, and we used one of them to search in certain radius of a coordinate.

Also, bear in mind that the coordination format is different from gmaps and twitter so you need to add 7 zeros in order to make this function work.

After we collected tweepy data, we pulled out the scores of sentimental analysis and displayed them as heatmaps using gmaps.

