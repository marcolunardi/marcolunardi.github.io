---
layout: post
title: Metis NY Data Science Bootcamp - 4th Project!
---

###  Twitter in a glance  


This is something very simple, but that I needed very much, and then I made it myself.

In addition to the very useful bootcamp lectures, I started also from the lessons I learnt from my previous NLP project (click here to see the [presentation](http://www.rpubs.com/marcoluna/68241) and the [app](https://marcolunardi.shinyapps.io/Text_Prediction)); it was written in R, and not so accurate, 'cause also of training data size constraints imposed by the shinyapps website.

The new app I wrote in Python gathers the 200 most recent tweets from the account of your choice, stores them into a MongoDB database, and then returns the 10 nouns that are mostly used into them, along with the 10 most used combinations of 2,3 and 4 words.

This provides you with a quick view about the most present subjects into the chosen twitter account.

Once you got a view about all the recent tweets, you can now choose the noun of your interest (the "keyword"), and the app will select just the tweets containing that noun out of all the 200 gathered tweets.

The app then will return the 5 most used verbs, adjectives, nouns (excluded the keyword), and adverbs in order to 
likely compose a "most used sentence".

Along with that, the app will return the 5 most present combinations of 2,3, and 4 words used into the selected tweets.

This app is quite useful to me in order to get a very quick view of the most clear trends developed through the day
into the main financial markets. Since I created it a few days ago, I'm using it on a daily basis, mostly on Yahoo Finance and Market Watch Twitter accounts, and I'm very satisfied with the outcomes.

But it works quite well even on other accounts, not related to financial matters.

A good thing about this app is that it doesn't require to gather historical data to work well, since it's focused on recent events, and so it's also very fast in its responses.

Finally, this very simple app is the starting point of one out of the two projects I'm considering as my final project for the Metis Bootcamp.

Check the [ipython notebook in "fletcher_deliverables" folder](https://github.com/marcolunardi/metis/tree/master/fletcher_deliverables) into my Metis repository to see a preview of how the app works!

Very soon I will add a flask app based upon the same notebook.

Analysis Tools: Natural Language Processing, APIs, Tweepy, MongoDB 
