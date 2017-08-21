# austin-yelp-coffee-reviews
Nearly 7,000 reviews scraped from yelp.com about Austin coffee shops, attributes replaced, sentiments around attributes

## Methodology ##
Collect reviews on coffee shops from Austin from Yelp.com with a row for each review, and columns with the following data:
- Coffee shop name
- Review text
- Review Score

Ran a word frequency analysis script to determine what common “attributes” are discussed in relation to coffee shops. Used a “find and replace” macro to merge attributes that mean the same thing.

Parsed phrases including each attribute (4 word buffer) to run through SentiStrength, sentiment scores are listed by attribute in this data set.
