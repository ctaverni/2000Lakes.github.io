---
title: "Sentimental Analysis"
weight: 10

header_menu: true
---


In order to better understand the relationship that Swiss citizens have with the lakes, it seems important to see their vision and the feelings that emerge from the images they post on notrehistoire.ch.
For this, we will perform a sentimental analysis using a lexicon and rule-based sentiment analysis tool that is specifically tuned to sentimentsexpressed in social media.

For each of the descriptions, we obtain 4 scores: the first three (’neg’, ’neu’, ’pos’) summing up to 1 show the tendency of the text to be positive, neutral or negative. The last one, ’compound’, brings the three together to show a general feeling:
- a positive sentiment, compound ≥ 0.05
- a negative sentiment, compound ≤ −0.05
- a neutral sentiment, the compound is between ] − 0.05, 0.05[.

By taking the average of each of the scores, we obtain the following results:
- negative: 0.028440677966101696
- neutral: 0.8995649717514125
- positive: 0.07198870056497175
- compound: 0.18087401129943503

We therefore notice that in general, the descriptions of the images are neutral. This shows that they want to be objective, that they show a reality and not the emotion that arises from the photo and its context. However, it is the role of the historian to explain the facts of the past, without judging the actions of the characters of the past and to strive as much as possible for impartiality. Once again, without it being a primary desire, the Swiss population as an entity becomes a historian.

Nevertheless, the ‘compound’ score still shows a slight bias that tends towards positive sentiment. This is surely due to the photos tagged ’Personal’ and which have often been taken in happy moments in the life of Swiss people.
For example, the description “In January 2006. A sunny Sunday. Skaters. Hot air balloon. A dream landscape.” shows a concise and factual description of the image, but it ends with a very positive overall impression.