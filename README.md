# NYC-Taxi-Cab-Predictive-Analysis
**TaxiCabTipPredict**: A data analysis and machine learning project exploring NYC taxi cab rides, predicting tip amounts, and enhancing understanding of customer payment behavior.The project utilizes a dataset of yellow taxi trips taken in NYC during 2017 and applies multiple linear regression and random forest models.

**New York Taxi Cab Ride Analysis: Predicting Tips and Revenue**

This project focuses on exploring and analyzing a dataset of New York City (NYC) taxi cab rides to gain insights into customer payment behavior and predict tip amounts. The dataset provides valuable information on various attributes, including trip distance, total amount, fare amount, and payment type, among others.

**Business Understanding:**
According to salary.com the average salary for a New York Taxi Driver is around $45,000. This salary is significantly low compared to a median rent value of $6,500 per month. It is important to understand what factors encourage riders to leave tips in order to help drivers obtain a livable wage. 

**Data Understanding:**
The NYC Taxi and Limousine Commission data came from NYC.gov. The data consisted of approximately 408k unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type. The bar chart below shows the breakdown of how many generous tippers (>20%) versus non-generous tippers that exist in the data set. 


**Data Exploration and Visualization:**
- Exploratory Data Analysis (EDA) was performed to understand the dataset, identify outliers, and prepare it for further analysis.
- Visualization was used to uncover important patterns and trends in the data.
- Outliers were identified and considered in the analysis.
- Credit card payments were observed to generate higher revenue for taxi cab drivers.

**Project Conclusions:**
1. **Importance of Exploratory Data Analysis (EDA):**
- EDA plays a crucial role in understanding the data, identifying outliers, handling missing values, and preparing the dataset for modeling.
- Provides valuable insights for feature selection and modeling decisions.

2. **Predictive Modeling and Feature Selection:**
- Multiple linear regression was used to estimate a dependent continuous variable from independent variables.
- Numeric and categorical features were selected based on insights gained from EDA.

3. **Model Evaluation and Improvement:**

- Models were evaluated by meeting linear regression assumptions and assessing MAE and RMSE scores.
- Feature engineering suggestions were made, such as trip distance categorization and a fare amount ratio.

4. **Limitations and Future Considerations:**

- The dataset has limitations, such as the lack of information on past tipping behavior and accurate tip values for cash payments.
- Predictive models rely on the presence of meaningful predictive signals in the data.

**Project Recommendations:**
- Carefully consider the application of the predictive model.
- While the model may not be highly accurate, it can provide valuable insights to taxi drivers regarding the likelihood of receiving a good tip.
- Testing the model with a select group of taxi drivers and gathering their feedback can further refine its utility.

**Conclusion:**
This project showcases the exploration and analysis of NYC taxi cab ride data to gain insights into customer payment behavior and predict tip amounts. By leveraging exploratory data analysis techniques and predictive modeling, this project offers valuable information for taxi cab drivers to optimize their revenue and improve their understanding of customer tipping patterns.

