# NHL Expected Goals Model
NHL Expected Goals model using play by play data

This is my expected goals model! I was first drawn to analytics and programming through its applications in sports (more specifically hockey). One of the dominating metrics in hockey analytics is the concept of expected goals. Using a classification model, we can allocate a probability of a shot being a goal. Aggregating those expected goals for and substracting expected goals against gives a good idea of which team was controlling play. We can also look at the individual player level and see what is their expected goals ratio when they are on the ice to see whether or not they are having a positive impact (to be taken with the caveat that team play mathers a lot here).

For this model, I am using play by play data scraped from the NHL's website using Evolving Wild's scraper. I am inspiring myself from the article written by Matthew Barlowe titled NHL Expected Goals Model to start with the basics of the model. I will be building models using the MLR package and try to find which algorithm produces the best results.

In future updates, I would like to play around with visualization (shot heatmaps).

Evolving Wild's github
https://github.com/evolvingwild/evolving-hockey

NHL Expected Goals Model - Matthew Barlowe
https://rstudio-pubs-static.s3.amazonaws.com/311470_f6e88d4842da46e9941cc6547405a051.html 
