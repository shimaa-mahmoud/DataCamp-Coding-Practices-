# Marketing campaign Analysis Basics

## Data Description
* `user_id`: object, unique user id
* `date_served`: object, The date when the user got the advertisement  
* `marketing_channel`: object, the advertisement method *(House ad, Facebook, instagram, Push or Email)*
* `variant`: object,  What group does the user in *(control, Personalization)*
* `converted`: bool, whether the user converted to the new product or not
* `language_displayed`: object, The ad's language
* `language_preferred`: object, User preferred language
* `age_group`: object, WHat age group the user belong to
* `date_subscribed`: object, User subscription date
* `date_canceled` object, User subscription cancelation date
* `subscribing_channel`: object, Which channel the user subscribed to
* `is_retained`: bool: does the user has the subscription
* `DoW`:float64, Day of the week
* `channel_code`: float64, The encoding of the marketing_channel
* `is_correct_lang`:object, whether the preferred language is the language_displayed

## what we want to do
1. Analyzing Marketing campaign and trying to find out of few of the business ques like:
2. How did this campaign perform?
3. Which channel is referring the most subscribers?
4. Why is a particular channel underperforming?
5. preform A/B test on the personalized emails
