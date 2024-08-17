# Housing-Price-Prediction
This project aims to provide insights into the factors that significantly impact housing prices, offering valuable information for prospective homebuyers. Using a dataset of 545 entries with 13 features, the project employs data mining techniques to build a predictive model that classifies houses as high-value or low-value.

**Dataset**

Rows: 545
Columns: 13
Features: Includes categorical variables such as furnishing status, which were converted into dummy variables for analysis.
Source: The dataset was sourced from Kaggle Datasets.

**Project Goals**

Predict Housing Prices: Accurately estimate property values based on features such as size, location, and the number of amenities.
Classify Properties: Differentiate between high-value and low-value houses using a variety of statistical models.
Identify Key Influencers: Determine the most significant factors that influence the selling prices of houses.

**Methodology**

Exploratory Data Analysis (EDA)
Conducted extensive EDA to understand the distribution and relationships between variables.
Identified that furnished houses tend to have higher prices with more variance compared to semi-furnished and unfurnished houses.

Modeling
Applied Multi-Linear Regression to model the relationship between house features and prices.
Converted categorical variables into dummy variables to fit the regression model.
Achieved an R-squared value of 0.682, indicating that 68.2% of the variation in house prices can be explained by the model.

Classification
Built a classification model to differentiate between high-value and low-value houses.
Performance Metrics:
Precision: 0.85 (Low-Value), 0.79 (High-Value)
Recall: 0.85 (Low-Value), 0.79 (High-Value)
F1-Score: 0.85 (Low-Value), 0.79 (High-Value)
Accuracy: 83%


Certainly! Here's the updated README with instructions on how to clone the repository and a note about the requirements.txt file.

README.md
Housing Price Prediction and Classification Model

Overview

This project aims to provide insights into the factors that significantly impact housing prices, offering valuable information for prospective homebuyers. Using a dataset of 545 entries with 13 features, the project employs data mining techniques to build a predictive model that classifies houses as high-value or low-value.

Dataset

Rows: 545
Columns: 13
Features: Includes categorical variables such as furnishing status, which were converted into dummy variables for analysis.
Source: The dataset was sourced from Kaggle Datasets.
Project Goals

Predict Housing Prices: Accurately estimate property values based on features such as size, location, and the number of amenities.
Classify Properties: Differentiate between high-value and low-value houses using a variety of statistical models.
Identify Key Influencers: Determine the most significant factors that influence the selling prices of houses.
Methodology

Exploratory Data Analysis (EDA)
Conducted extensive EDA to understand the distribution and relationships between variables.
Identified that furnished houses tend to have higher prices with more variance compared to semi-furnished and unfurnished houses.
Modeling
Applied Multi-Linear Regression to model the relationship between house features and prices.
Converted categorical variables into dummy variables to fit the regression model.
Achieved an R-squared value of 0.682, indicating that 68.2% of the variation in house prices can be explained by the model.
Classification
Built a classification model to differentiate between high-value and low-value houses.
Performance Metrics:
Precision: 0.85 (Low-Value), 0.79 (High-Value)
Recall: 0.85 (Low-Value), 0.79 (High-Value)
F1-Score: 0.85 (Low-Value), 0.79 (High-Value)
Accuracy: 83%
Key Findings

Significant Predictors: Area, number of bathrooms, stories, main road access, guestroom, basement, air conditioning, and hot water heating were identified as significant predictors of house prices.
Non-Significant Predictor: Number of bedrooms did not show a strong correlation with house prices.
Facilities Impact: Air conditioning and hot water heating were found to significantly increase house values, with air conditioning having a more pronounced effect.

**Conclusion**

The project successfully demonstrates the application of data mining techniques to predict housing prices and classify properties based on their value. The insights gained can help homebuyers make informed decisions and assist real estate professionals in market analysis.

**Repository Contents**

Project.ipynb: Jupyter Notebook containing the code for data preprocessing, EDA, modeling, and classification.
Housing.csv: The dataset used in this project, sourced from Kaggle Datasets.
DM_final_presentation.pptx: Final presentation summarizing the project findings and insights.

**How to Run**
1. Clone the Repository :git clone https://github.com/rachanap0/Housing-Price-Prediction.git
2. Install the Required Dependencies:
   cd repository-name
   pip install -r requirements.txt
3. Open and Run the Jupyter Notebook : jupyter notebook

**License**

This project is licensed under the MIT License - see the LICENSE file for details.

**Contact**

If you have any questions or suggestions, feel free to contact me via email: pandeyrachana08@gmail.com


   
