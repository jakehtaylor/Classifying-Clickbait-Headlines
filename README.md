# Classifying Clickbait Headlines #

#### Jake Taylor, Anthony English ####

### Guiding Questions ###

1. Are articles with clickbait hedalines more popular on social media platforms than non-clickbait articles?
2. Do certain topics have more clickbait article headlines than others?
3. Do certain topics receive a particular facebook 'reaction' disproportionately? 
4. How does clickbait status effect 'reactions' on Facebook?

### Objectives ###

Develop a classification model to determine the clickbait status of the most popular news articles of the past month across 10 different topics. Compare the number of article headlines across the different topics that are classified as clickbait. Compare the popularity of clickbait articles to other articles posted and/or shared on Facebook. Compare the Facebook likes and 'reactions' across different topic areas and clickbait classifications.

### Process ###

For each of the ten selected topics: **BLM, Biden, Covid, Entertainment, Food, Health, Politics, Science, Sports,** and **Trump**, we downloaded the 10,000 most popular articles of the past six months from [Buzzsumo's](https://buzzsumo.com) database, and parsed down the columns to what was relevant to our research:

- title
- url
- evergreen score (metric of popularity 30 days after article's publishing date)
- total facebook shares
- facebook comments
- facebook shares
- facebook likes
- wow count (facebook reaction)
- love count (facebook reaction)
- haha count (facebook reaction)
- sad count (facebook reaction)
- angry count (facebook reaction)
- number of words in article




