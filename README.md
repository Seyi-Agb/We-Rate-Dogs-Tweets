# WeRateDogs Tweet Data Analysis

## Dataset
The data was obtained from tweets from WeRateDogs Twitter Account. WeRateDogs is a Twitter account that comments on and rate dogs based on pictures shared directly with the account by their owners. The ratings often have a denominator of 10 and it is common to see numerators over 10 in their ratings e.g. 13/10. Tweets analysed were from inception of the account to August 1, 2017.

### Data Sources
1.	Enhanced Twitter Archive (twitter_archive)
Prior to me accessing the data, the data was programmatically downloaded and tweets with ratings were filtered for and the variables extracted.
2.	Additional Data via the Twitter API (add_info)
This dataset was obtained from the Twitter API (using tweepy) and following variables were extracted from the resulting txt file.
3.	Image Predictions File (image_pred)
This dataset was downloaded programmatically (using the request library) and was saved as a tsv file. The dataset contains dog breed prediction carried out by passing the dog images from the tweets through a neural network.

## Assessment & Cleaning
Assessment was carried out by visual inspection and programmatically. 11 quality and 2 tidiness issues were identified.

## Summary of Findings
1.	Based on the cleaned data, 98% of the tweets from the WeRateDogs account were from an iPhone
2.	12/10 was the most popular rating used on the account, whereas 6/10, was the least popular rating on the account
3.	There is a positive correlation between Retweet/Favorite Count and WeRateDog Rating for WeRateDog Rating greater than 9/10, while  no correlation for ratings less than 9/10
4.	Golden retrievers, Labrador retrievers, and Pembroke breeds are the most reviewed dog breed by WeRateDog Twitter account. In terms of the WeRateDogs Rating, the highest retweeted/favorited dog breeds are: English Springer (13/10), Italian Greyhound (12/10) and Great Pyrenees (11/10)
5.	12a.m. – 2 a.m. were popular times for tweets from the WeRateDog Twitter account. However, the Twitter account tweeted mainly between 12a.m. - 5a.m. and 3p.m. - 11p.m. The mean highest retweet/favorite count occurred at 6 a.m.
6.	The retweet/favorite count also increased on yearly basis, indicating increased popularity of the Twitter account
