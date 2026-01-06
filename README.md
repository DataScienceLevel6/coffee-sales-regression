# Coffee Sales – Linear Regression Project

This project explores how transactions from a coffee shop can be used to predict customer spend per purchase using a linear regression model. The dataset contains 3,547 transactions between March 2024 and March 2025, including details such as coffee type, time of day, weekday, and payment method. The aim was to identify which factors most influence spend and to demonstrate how a regression model can support data driven decision making.

## Project Objectives
1. Clean and prepare the dataset for analysis  
2. Explore spending patterns using visualisations  
3. Train a linear regression model to predict transaction value (£)  
4. Interpret which features have the biggest influence on spend  
5. Save the cleaned data and model for reuse

## Tools Used
The following libraries were used throughout the project:

Pandas - for data manipulation, filtering, and one-hot encoding of categorical variables.
matplotlib and seaborn - for visualisation, enabling the creation of bar charts.
scikit-learn - for training and evaluating the Linear Regression model, including splitting the dataset, fitting the model, and calculating performance metrics (R2 and RMSE).

## Repository Structure
notebook/Coffee_Sales.ipynb
data/Coffee_Sales.csv
images/Visualisations and charts
README.md/Project overview

## Data Cleaning
Removed unused columns
Standardised date formats
Converted values into numeric where required
Checked for missing or invalid records

##  Exploratory Data Analysis

Included charts such as:

Average spend by coffee type

<img width="354" height="217" alt="AvgSpendbyCoffeeType" src="https://github.com/user-attachments/assets/8e82441d-ec59-4547-a628-24f544b6faca" />

Average spend by month 

<img width="354" height="217" alt="AvgSpendbyMonth" src="https://github.com/user-attachments/assets/94ce3572-a3d4-4fb3-a521-2bc843be4c75" />

Average spend by time of day   

<img width="354" height="217" alt="AvgSpendbyTimeofDay" src="https://github.com/user-attachments/assets/d01920d1-4679-47ca-b241-e5603adc482a" />

Transactions by coffee type  

<img width="354" height="217" alt="TransactionsbyCoffeeType" src="https://github.com/user-attachments/assets/d8298a8d-ec8d-4628-834e-765c0e0f5489" />

The following charts were also created in Google Colab but were not used as they showed very little insights to what was being shown in the above

Heatmap
Boxplots

# Model

A Linear Regression model was trained using one-hot encoded features.  
Model performance was evaluated using:

R2 (Coefficient of Determination)
RMSE (Root Mean Squared Error)

Cooefficient

<img width="130" height="176" alt="Coefficient" src="https://github.com/user-attachments/assets/e08b6963-bf84-4ee6-b919-a3938e0be081" />

Linear Regression

<img width="354" height="365" alt="LinearRegression" src="https://github.com/user-attachments/assets/216f6997-9016-42c0-a105-4fe77a738791" />


The model achieved strong performance and showed that coffee type had the biggest impact on spend.

# Closing Statement

This project shows practical data science skills including:

cleaning and preparing real-world data  
using Python for EDA and modelling  
interpreting regression results  
explaining findings clearly  

# Future Improvements
Future improvements could include:

testing alternative models 
analysing promotions or loyalty behaviour
building a dashboard for business users






