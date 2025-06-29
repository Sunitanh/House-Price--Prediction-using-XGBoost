# House-Price--Prediction-using-XGBoost
**Business Context:**
Accurate housing price prediction is essential in the real estate and financial sectors. Whether it’s a buyer evaluating property affordability, a seller setting a competitive price, or an investor assessing market trends, having a reliable prediction model supports smarter decisions. This project builds a machine learning model that leverages structured data and advanced regression techniques to forecast home prices in California.
________________________________________
**Problem Statement:**
Real estate prices are influenced by multiple factors such as location, age of the house, number of rooms, and household income. Traditional estimation methods often fall short due to their inability to capture non-linear patterns. 

This project aims to:

•	Develop a regression model using XGBoost to predict housing prices

•	Analyze key factors that drive house prices

•	Evaluate the model's accuracy using standard performance metrics
________________________________________
**Data Availability:**
The project uses the California Housing Dataset, which is:

•	Freely available through the Scikit-learn library

•	Contains features like:

o	MedInc: Median income

o	HouseAge: Median house age

o	AveRooms, AveBedrms: Average rooms and bedrooms

o	Population: Area population

o	Latitude, Longitude: Location information

o	MedHouseVal: Target variable (Median house value)
________________________________________
**Data Understanding:**
Initial exploration included:

•	Checking for missing or inconsistent values

•	Analyzing distribution and range of variables

•	Using visualizations (via Matplotlib & Seaborn) to:

  o	Understand correlation between variables

  o	Visualize geographic and income-based price trends

•	Observed high correlation between median income and house price

•	Identified regional trends using latitude and longitude
________________________________________
**Key Steps Performed:**

1.**Data Collection & Cleaning:**

  o	Loaded California Housing dataset via Scikit-learn

  o	Checked for missing/null values (none found)

  o	Derived features like rooms_per_household for better model performance

2.**Data Visualization:**

  o	Histograms to view distributions

  o	Correlation matrix to identify key influencers of price

  o	Scatter plots for relationships between income, location, and price

3.**Model Development:**

  o	Applied train-test split to evaluate model generalizability

  o	Used XGBoost Regressor from Scikit-learn for prediction

  o	Tuned basic hyperparameters for optimal accuracy

4.**Model Evaluation:**

  o	Evaluated using:

      1.**R² Score** – to measure how well variance in prices is explained

      2.**Mean Absolute Error (MAE)** – to measure average prediction error

  o	Visualized predicted vs. actual prices with a scatter plot
________________________________________
 **Technology Stack Used:**

•	Languages: Python

•	Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

•	Modeling Algorithm: XGBoost Regressor

•	Development Environment: Jupyter Notebook / Google Colab

•	Dataset Source: Scikit-learn California Housing Dataset
________________________________________
 **Key Outputs:**

•	Built a high-accuracy regression model for predicting house prices

•	Achieved strong R² score and low MAE, indicating good generalization

•	Identified key predictors: Median Income, Rooms per Household, Latitude, and Longitude

•	Delivered a well-documented, reproducible notebook with data exploration, modeling, and insights
________________________________________
**Challenges & Learnings:**

**Challenges:**

•	Handling relationships between geographic features and price (non-linear patterns)

•	Preventing overfitting due to outliers or multicollinearity in input features

**Learnings:**

•	Gained hands-on experience with XGBoost and its strengths in regression tasks

•	Learned how to evaluate regression models effectively using visual and statistical metrics
•	Understood the importance of feature engineering in improving model accuracy
•	Reinforced EDA best practices and how visualization can reveal critical insights

