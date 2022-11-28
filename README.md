# UDOT EIS NLP

Recently UDOT release the second round of comments for the EIS on the transportation recommendations for Little Cottonwood Canyon. This is meant to alleviate congestion during the ski season and make the canyon safer. Initial NLP includes a word frequency plot and a word cloud. 

![EIS_Word_Frequency](https://user-images.githubusercontent.com/95090904/204173885-370b9939-d988-4513-8358-e65a29cdd8c0.png)

![image](https://user-images.githubusercontent.com/95090904/204173925-dc9dd91b-9132-4e0b-82b5-e9b6b09849ec.png)

In addition to this I'm going to perform a token to vector transformation in order to plot word association. This will then lead into a transformer summarization using the spacy model. All the comments were combined into a single corpus for analysis so it should be interesting to see what comes out of it.
