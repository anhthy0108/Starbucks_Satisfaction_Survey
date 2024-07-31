# Starbucks Satisfaction Survey Analysis - PYTHON
## 1. Introduction
  This project focuses on analyzing customer perceptions of Starbucks, one of the largest coffeehouse chains in the world, headquartered in Washington, USA. Established in 1971, Starbucks has gained recognition for its product quality and services, classifying it as a premium coffeehouse chain. To understand customer experiences and determine if Starbucks provides the value expected for an average price of $2.75-$3 per drink, we analyzed survey data from 122 Starbucks customers in Malaysia.

## 2. Overview of the Dataset
  The dataset, titled "Starbucks Customer Survey," was uploaded by Mahira Hamzah on Kaggle. It contains 122 observations with 20 questions divided into three main categories:

- Customer demographics
- Current shopping behavior at Starbucks
- Starbucks' features and facilities affecting customer behavior
  The dataset comprises 22 columns:

1. Timestamp: Survey response timestamp
2. Your gender: Customer gender (Male; Female)
3. Your age: Customer age (Below 20; From 20 to 29; From 30 to 39; 40 and above)
4. Are you currently...: Employment status (Student; Self-Employed; Employed; Housewife)
5. What is your annual income?: Annual income (Less than RM25,000; RM25,000 – RM50,000; RM50,000 – RM100,000; RM100,000 – RM150,000; More than RM150,000)
6. How often do you visit Starbucks?: Visit frequency (Daily; Weekly; Monthly; Never)
7. How do you usually enjoy Starbucks?: Consumption method (Dine In; Drive-thru; Take away; Never; Others)
8. How much time do you normally spend during your visit?: Visit duration (Below 30 mins; 30 mins to 1h; 1h to 2h; 2h to 3h; More than 3h)
9. The nearest Starbucks’s outlet to you is...?: Distance to the nearest outlet (Within 1 km; 1 km to 3 km; More than 3 km)
10. Do you have a Starbucks membership card?: Membership status (Yes; No)
11. What do you most frequently purchase at Starbucks?: Products purchased (Coffee, Cold Drinks, Pastries, Juices, Sandwiches, Other products) (Yes; No)
12. On average, how much would you spend at Starbucks per visit?: Average spending per visit (Zero; Less than RM20; RM20 to RM40; More than RM40)
13-19. Rate 1-7: Ratings (1: Very Bad; 5: Excellent) for various factors - product, price, promotion, store ambiance, Wi-Fi quality, service quality, and using Starbucks as a meeting or gathering spot.
13. How do you come to hear of promotions at Starbucks?: Channels through which promotions are received (Starbucks app, social media, email, transaction sites, word of mouth, in-store displays, billboards, other channels) (Yes; No)
14. Will you continue buying at Starbucks?: Customer loyalty (Yes; No)
## 3. Objectives
In this report, we aim to:

1. Preprocess the Dataset: Handle missing values, split the columns “10. What do you most frequently purchase at Starbucks?” and “19. How do you come to hear of promotions at Starbucks?”.
2. Descriptive Statistics: Identify key characteristics of the dataset, including distribution shapes, variable correlations, etc.
3. Data Visualization: Use appropriate charts to visualize the data.
4. Statistical Tests: Conduct tests such as One-way ANOVA, Chi-squared, and PCA to find highly correlated variables and reduce data dimensions.
