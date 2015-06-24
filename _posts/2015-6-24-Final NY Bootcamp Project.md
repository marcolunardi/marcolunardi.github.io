---
layout: post
title: Metis NY Data Science Bootcamp - Final Project!
---

###  Optimizing Options Trading 


The idea for the final project came to me quite easily.

Through the past 5 years I developed a bunch of indicators that are working quite well in real trading on stocks and future markets,
so, this was the right occasion for me to translate them into Python and to draw an automatic "signal caller" from them.

I decided to choose Options as target of the trading signals in order to aim the predictions to "range of prices" instead of
"exact prices", since the second task is much harder to be accomplished than the first one.
In fact, while the model turned out to be very good in designing a range of price movement through a month, was pretty lost
when focused on predicting the exact final price of the month, as expected.

I tried various machine learning algorithms to train my model, but finally the Ridge, Lasso and Elastic Net variants
on the generalized Regression models got the job done in the best way, with results even more accurate than I was expecting.

Check "final_project" folder into my Metis repository to see the outcomes!
