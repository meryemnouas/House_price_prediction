**House Price Prediction in Delhi, India:**

**Objective:**

The primary goal of this project is to develop a predictive model to accurately estimate house prices in Delhi, India, based on key features such as house area, number of bedrooms, locality, and more. By analyzing these factors, the project aims to provide valuable insights to potential buyers and sellers in the real estate market, assisting them in making informed decisions.

**Dataset Description :**

The dataset used in this project contains detailed information about houses in Delhi, with each row representing the characteristics of a single property. The dataset includes the following attributes:

**Surf:** House area in square feet.

**Cham_c:** Number of bedrooms.

**Salle_bain:** Number of bathrooms.

**Ameublement:** Furnishing status of the property.

**Localité:** Locality of the house.

**Parking:** Number of parking spots available.

**Prix:** Price of the house.

**Statut:** Property status (ready to move or under construction).

**Transaction:** Indicates if the property is a new property or a resale.

**Type:** Type of property (e.g., apartment, floor in a house).

**Prix_sqft:** Price per square foot of the property.

**Approach :**

1. Data Preprocessing :

Handling Missing Values: Missing data imputation for features with incomplete records.

Feature Engineering: Transforming and encoding categorical variables (e.g., Ameublement, Statut).

Normalization: Scaling numerical data for improved model performance.

Outlier Detection: Identifying and managing anomalies in numerical features.

2. Exploratory Data Analysis (EDA) :

Analyzed relationships between key features and the target variable (Prix).

Visualized data distributions and feature correlations using tools like Matplotlib and Seaborn.

Identified locality-based pricing trends and other significant factors affecting house prices.

3. Predictive Modeling :

Built and evaluated machine learning model : Linear Regression.

Model Evaluation: Used metrics like R², Mean Absolute Error (MAE), and Root Mean Square Error (RMSE) to evaluate and compare model performance.

Tools and Technologies Used :

Languages: Python Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn Environment: Google collab

**How to Use :**

1.Clone the repository:

git clone https://github.com/meryemnouas/House_price_prediction.git
cd House_price_prediction

2.Install dependencies

Once inside the project folder, you can install the required dependencies.You can install the necessary libraries using pip:

!pip install requirements

3.Run the Gogle Collab for analysis and model training.
