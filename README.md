# Amazon Fine Food Reviews Analysis
Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews
Objective:
1. Given a review, determine whether the review is positive or negative.
2. How to determine if a review is positive or negative?
3. We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored.
4. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.
# Dataset
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.
Attribute Information:
There are a total of 10 columns in total in the Amazon Fine Food review dataset.
1. Id : Row Id
2. ProductId : Unique identifier for the product.
3. UserId : Unique identifier for the user.
4. ProfileName : Profile Name of the User.
5. HelpfulnessNumerator : Number of users who found the review helpful.
6. HelpfulnessDenominator : Number of users who indicated whether they found the review helpful or not.
7. Score : Rating between 1 and 5.
8. Time : Timestamp for the review.
9. Summary : Brief summary of the review.
10. Text : Text of the review.
