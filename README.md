# starbucks_capstone

## Business Understanding

1: Based on the data, the coupon appeal to which group of people?

2: Based on the data, what is the most popular coupon type?

3: What features affect the popular coupon?

## Data Understanding

1: We can check the histogram of age and income. And calculate the gender ratio.

2: We can check the histogram of coupon type.

3: I pick some related features affected the review score rating below: 
 'time', 'difficulty', 'duration', 'reward_y', 'channel_email', 'channel_mobile', 'channel_social', 'channel_web', 'age', 'income', 'gender_F', 'gender_M', 'become_member_days'

## Prepare Data

1: clean data, expand value, and get dummy

2: drop NAN data (no information for these NAN)



## Data Modeling

Split training and testing data. Use 'offer complete' as y, the rest features as X. Apply linear regression to learn the data.

## Evaluate the Results

You can check [here](https://bamboojas1.medium.com/starbucks-popular-rewards-55fc453ba7a3) in medium.

## Summary the Results


1: Female prefer using coupon offer than male. Older prefer using coupon offer than male. People with high income prefer using coupon than low income.


2: The most popular coupon type is discount.


3: Sending offer through web and mobile, longer duration time can help more people finish the offer.


## File description: 
All the data is in data.zip
The data is contained in three files:
portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed

the code is in Starbucks_Capstone_notebook.ipynb

## python library

numpy

pandas

matplotlib.pyplot

sklearn

seaborn

## acknowledgments

This is Udacity data science nano degree capstone project.
