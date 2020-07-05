# The-Android-App-Market-on-Google-Play:iphone:
Did a comprehensive analysis of the Android App market by comparing over ten thousand apps in Google Play across different categories. 

The [data](https://www.kaggle.com/lava18/google-play-store-apps) for this project was scraped from the [Google Play](https://play.google.com/store/apps) website.

The data files are as follows:
- [apps.csv](datasets/apps.csv) contains all the details of the applications on Google Play. There are 13 features that describe a given app.
- [user_reviews.csv](datasets/user_reviews.csv) contains 100 reviews for each app. The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.

I did the following things for Exploratory Data Analysis:

## 1. Exploring App Categories
   - Which category has the highest share of (active) apps in the market?
   - Is any specific category dominating the market?
   - Which categories have the fewest number of apps?

## 2. Distribution of App Ratings
   - Looked at how apps perform on an average.

## 3. Size and Price of an App
   - Does the size of an app affect its rating?
   - Do users really care about system-heavy apps or do they prefer light-weighted apps?
   - Does the price of an app affect its rating?
   - Do users always prefer free apps over paid apps?
   
## 4. Relationship between App Category and App Price
   - Tried to look at how the category of an app can affect the pricing.

## 5. Popularity of Paid Apps vs Free Apps
   - Are paid apps installed as much as free apps?

## 6. Sentiment Analysis of User Reviews
   - Applied Sentiment Analysis to determine how people feel about an app by plotting sentiment polarity scores of user reviews for paid and free apps.
   
Lastly, I would like to thank [DataCamp](https://www.datacamp.com/) for this amazing project!
