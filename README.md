# Identify and classify Twitter bot accounts
This in-class kaggle competition is to solve an anomaly detection problem. Your task is to develop a machine learning model to distinguish bot users from genuine users based on a given dataset of Twitter accounts. This competition will give you hands-on experience with data preprocessing, feature engineering, model training, and evaluation.

Twitter bots can be used for a range of activities, from spreading spam to disinformation campaigns. Accurately identifying these bots is crucial for maintaining the integrity of social media platforms. You will be provided with a dataset containing various features extracted from Twitter profiles, and your goal is to use this data to build a predictive model that can detect bots.

## Files
- `train.csv` - the training set
- `test.csv` - the test set
- `sample_submission.csv` - a sample submission file in the correct format

## Columns
- `created_at` - The date and time when the Twitter account was created.
- `default_profile` - Indicates whether the user has a default profile settings.
- `default_profile_image` - Indicates whether the user has a default profile image.
- `description` - The user's profile description or bio.
- `favourites_count` - The number of tweets the user has liked.
- `followers_count` - The number of followers the user has.
- `friends_count` - The number of accounts the user is following.
- `geo_enabled` - Indicates whether the user has enabled location services.
- `id` - The unique identifier for the Twitter account.
- `lang (object)` - The language preference set for the account.
- `location (object)` - The location information provided by the user.
- `profile_background_image_url` - URL of the user's profile background image.
- `profile_image_url` - URL of the user's profile image.
- `screen_name` - The user's Twitter handle or username.
- `statuses_count` - The total number of tweets posted by the user.
- `verified` - Indicates whether the account is verified by Twitter.
- `average_tweets_per_day` - The average number of tweets posted per day.
- `account_age_days` - The age of the account in days.
- `target` - The classification label indicating whether the account is a bot or not. 1 means it is a bot.
