##Airline Data Analysis Using Python

##Overview:

This project analyzes airline data to uncover insights about flight routes, durations, 
pricing trends, and travel patterns. Using Pandas, Matplotlib, Seaborn, and Scikit-learn, 
I cleaned, processed, and visualized the dataset to extract meaningful business intelligence.

##Key Features & Analysis:

✅ ##Data Cleaning & Transformation:

Handled missing values in the Total_Stops and Price columns.

Converted Duration from hours & minutes to total minutes for better numerical analysis.

Applied Label Encoding on categorical variables like Airline for machine learning compatibility.

✅ ##Exploratory Data Analysis (EDA):

Visualized flight distribution per source & destination using bar plots.

Identified price trends based on flight duration & stops using Seaborn heatmaps.

Analyzed seasonal variations in airfare using Month & Year features.

✅ ##Feature Engineering & Predictive Modeling:

Created new time-based features (Arrival & Departure minutes) for enhanced analysis.

Built a Regression Model (Random Forest/XGBoost) to predict flight prices.

Optimized model performance using Hyperparameter Tuning.

✅ ##Insights & Business Takeaways:

Direct flights tend to be cheaper over long distances but costly for short routes.

Evening and midnight departures often have lower pricing compared to morning flights.

Airlines with more layovers usually show price spikes due to operational costs.
