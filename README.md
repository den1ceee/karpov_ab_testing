# Karpov.Courses A/B testing analysis projects
Hello! Here I store my 2 A/B analysis projects completed during my study on Karpov.Courses <br>
Date - 04/2023

## 1st Case Description 
*Case #1 - Dating App*

You work as an analyst in an online dating application. The mechanics of the app is as follows: users see each other's profiles in the app and can give each other likes or dislikes. If users like each other, it's called a match, and users have the opportunity to get to know each other.

The app team developed a new algorithm to find the most suitable profiles. To test the algorithm, an AB test was conducted. All users were divided into two groups. The users in group 0 used the app with the old algorithm. All users in group 1 used the app with the new algorithm to search for questionnaires.

Your task is to evaluate whether the new algorithm has improved the quality of the service. To do this you need to choose one or more metrics which are responsible for the service quality, and statistically compare these metrics in two groups.

The result of your work is an analytical opinion answering the question of whether to include the new questionnaire search system for all users.

### Data

The data contains the logs of users' interactions with each other. For each user pair, you can see which AB test group they are from and whether they have had a match or not.

## 2nd Project Description

*Case #2 - Delivery app*

You work as an analyst for a grocery delivery app. The team has implemented a smart product recommendation system in the app - it is supposed to help users work more efficiently with the app and better find the products they need.

To test the effectiveness of the recommendation system, an AB test was conducted. Group 1 included users with the new recommendation system, while group 0 included users with the old version of the app, which had no recommendation system.

Your task is to assess whether the new recommendation system has been able to benefit the business and users of the app. To do this you need to select one or several metrics which are responsible for the service quality and statistically compare these metrics in two groups.

The result of your work is an analytical report answering the question of whether the new recommendation system is worth including for all users.

### Data

In the data you will find the order logs of users:

ab_users_data - history of users' orders, this table has information about what orders were created and cancelled by users<br>
ab_orders - detailed information about the contents of the order; here for each order there is a list of the id of the products that were included in the order<br>
ab_products - detailed information about products, their name and price<br>
