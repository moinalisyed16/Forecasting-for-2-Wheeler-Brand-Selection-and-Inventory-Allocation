# Forecasting-for-2-Wheeler-Brand-Selection-and-Inventory-Allocation
This project aims to predict the sales success of 2-wheelers based on various factors, such as bike features, city variables, and brand preferences. The model uses machine learning techniques to generate precise forecasts, assisting in decision-making for inventory allocation, pricing strategies, and business planning.

**Project Overview**
The primary goal of this project is to develop a model that predicts the likelihood of a 2-wheeler’s success in a particular market based on several influencing factors:

Bike Features: Including price, kms driven, power, and other specifications.

City Variables: Such as city demographics and preferences.

Brand Preferences: Insights into which brands perform better in specific locations.

Using these features, a machine learning model (KMeans clustering and Naive Bayes) has been built to segment bikes and predict their success probability. The project also provides insights for optimizing pricing and inventory management strategies.

**Key Techniques**
Data Preprocessing: Categorical variables like bike brand and owner type were one-hot encoded to prepare data for modeling.
Clustering: KMeans clustering was used to segment bikes based on various features, helping to identify market trends and patterns.
Classification: Naive Bayes classifier was applied to predict sales success (sold or not sold).
Visualization: Various visualizations were created to understand the relationships between bike features, city variables, and sales success, including heatmaps, ROC curves, and confusion matrices.

**Applications**
Sales Forecasting: Predicting which bike configurations are more likely to succeed in specific markets.
Inventory Allocation: Identifying optimal inventory levels based on forecasted sales success.
Pricing Strategies: Recommending pricing strategies tailored to city-specific demands and bike configurations.
