# Twitter US Airline Sentiment Analysis
### Background and Context:
Twitter possesses 330 million monthly active users, which allows businesses to reach a broad population and connect with customers without intermediaries. On the other hand, there’s so much information that it’s difficult for brands to quickly detect negative social mentions that could harm their business.

That's why sentiment analysis/classification, which involves monitoring emotions in conversations on social media platforms, has become a key strategy in social media marketing.

Listening to how customers feel about the product/service on Twitter allows companies to understand their audience, keep on top of what’s being said about their brand and their competitors, and discover new trends in the industry.

### Data Description:
A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").

### Dataset:

The dataset has the following columns:

tweet_id
airline_sentiment
airline_sentiment_confidence
negativereason
negativereason_confidence
airline
airline_sentiment_gold
name
negativereason_gold
retweet_count
text
tweet_coord
tweet_created
tweet_location
user_timezone

### Problem Statement:

Build Classification Model to classify sentiment of the tweet of US Airlines.
Identify the reasons for negative sentiment, so that Airlines can focus on those

### Opinion and Views

This dataset will help airlines to understand what type of negative reviews people are giving.
Since it contains data for different airlines. The airline which got poor reviews can compare with other airlines and try to find out ways to improve it.
The location, time, etc. datapoints will help Airlines understand when and where negative reviews they recieved and try to compare that with any relavant event happened in the airline service. For e.g., due to weather, the Austin flight cancelled and people gave negative reviews on customer service when they tried to reschedule the flight. The airline can analyze these types of events and improve their customer service when airline is cancelling.
