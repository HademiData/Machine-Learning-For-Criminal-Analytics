# Criminal Justice Conviction Prediction Using Machine Learning

This project aims to evaluate the effectiveness of the criminal justice system by predicting whether the number of successful convictions for a specific offense is greater than or less than the number of unsuccessful convictions. Using machine learning techniques, we analyze conviction data from 2015 to 2018 across multiple quarters and offense types.

## 📊 Objective

We developed a binary classification model that forecasts the likelihood of successful convictions exceeding unsuccessful ones for various offense categories. These include:
- Homicide
- Sexual offenses
- Robbery
- Theft
- Fraud

## 🔍 Methodology

### 1. Data Collection & Target Engineering
The dataset, obtained from official UK crime reports, contains conviction outcomes for multiple offense types across different time periods. A new target label is created for each row:
- `1` if successful convictions > unsuccessful convictions
- `0` otherwise

### 2. Exploratory Data Analysis (EDA)
We perform:
- Univariate analysis to understand variable distributions
- Bivariate and multivariate analysis to explore correlations
- Trend analysis across time and offense types

### 3. Feature Engineering & Selection
- We identify and select features with strong correlation to the target label.
- Feature scaling and encoding are applied where necessary.

### 4. Model Development
Several classification models are trained to predict the target label. These include logistic regression, decision trees, and ensemble models. Model performance is evaluated using standard metrics such as accuracy, precision, recall, and F1-score.

## 🤖 Machine Learning Goals
- Forecast conviction outcomes for different offense categories
- Support policy-making and resource allocation in the criminal justice system
- Identify data patterns that reflect systemic strengths or gaps
