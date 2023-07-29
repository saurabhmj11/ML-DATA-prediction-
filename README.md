# 🛫 Airline Booking Data Project Overview 🛬

## 📌 Introduction:
The "Airline Booking Data" project aims to predict whether a customer will book a ticket or not, utilizing a dataset obtained from Kaggle. The primary focus of this project is to build a machine learning model that can accurately determine the likelihood of a booking based on various features and customer attributes.

## 📌 Data Preprocessing:
The dataset consists of 14 columns and 50,000 rows. As part of the data preprocessing steps, the following actions were performed:

1. **Handling Missing Values**: Fortunately, there were no missing values in the dataset, alleviating the need for imputation.

2. **Removing Duplicates**: Some duplicate entries were identified and subsequently removed to ensure data integrity.

3. **Data Visualization**: Basic visualizations were employed to gain insights into the dataset, such as data types and statistical analysis.

## 📊 Explore Data Analysis (EDA) Process 📈:
This phase involved conducting a comprehensive exploratory data analysis to extract valuable insights from the dataset. Various data visualizations were used, including bar charts, pie charts, and histograms, to gain a deeper understanding of the data. Key findings from the EDA include:

1. **Booking Channels**: The majority of tickets are booked through the Internet, with a smaller portion being booked through other means.

2. **Booking Frequency**: Only 8% of customers booked their tickets, while the rest did not.

3. **Influence of Promotions**: Advertisements, discounts, and coupons were found to influence customers to make bookings.

4. **Impact of Additional Features**: Offering extra baggage, meal options, and preferred seats increased the likelihood of customers making a booking.

5. **Peak Booking Day**: The group by function was utilized to determine the day with the highest ticket sales.

## 📊 Machine Learning Model:
The final phase involved building a machine learning model to predict customer behavior for airline ticket bookings. The following steps were undertaken:

1. **Data Preprocessing**: Categorical columns were converted into numerical values using label encoding. The data was then split into dependent and independent variables and normalized using standard scaling.

2. **Train-Test Split**: The data was divided into 70% training and 20% testing sets to evaluate the model's performance.

3. **Model Selection**: Various classification algorithms, including logistic regression, random forest, decision trees, XGBoost, and CatBoost, were applied to the dataset.

4. **Model Evaluation**: The accuracy score was used to assess the performance of each model. Notably, logistic regression, XGBoost, and CatBoost achieved an accuracy score of 85%.

## 📋 Conclusion:
The "Airline Booking Data" project provides valuable insights into predicting customer behavior for airline ticket bookings. Through careful data preprocessing, exploratory data analysis, and the application of machine learning models, we were able to develop a model that can accurately predict whether a customer will book a ticket or not. This project has significant implications for airlines, as it helps them understand customer preferences and optimize their marketing and promotional strategies.
