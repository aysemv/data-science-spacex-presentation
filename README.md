INDTRODUCTION

Welcome to the Space Y Data Analysis project! In this repository, we explore the viability of the new company Space Y to compete with Space X. We employ machine learning models, web scraping, and data visualization techniques to gain insights into launch cost dynamics, predict successful landings, and compare the performance of Space Y with the established giant, Space X.

OBJECTIVE

The primary objective of this project is to assess Space Y's competitiveness with Space X in the space exploration market. We focus on the following key aspects:

Machine Learning Models: We utilize GridSearchCV to find the best hyperparameters for four machine learning models: Logistic Regression, Support Vector Machine, Decision Tree Classifier, and K-Nearest Neighbors. These models play a pivotal role in predicting successful landings for Space Y's missions based on historical data.

Data Collection: We leverage web scraping techniques and the SpaceX API to gather essential data on historical space missions, including launch costs and landing outcomes. This data forms the basis of our analysis.

Data Visualization: Data visualization is a crucial tool in understanding relationships and trends. We use SQL queries and Matplotlib to create scatterplots, line charts, and bar charts that enable us to compare and analyze the collected data effectively.

METHODOLOGY

Data Collection: We utilize web scraping techniques to gather historical launch cost data from various space missions, including Space X and other competitors. Additionally, we access the SpaceX API to obtain data on successful and unsuccessful landings.

Data Preprocessing: The collected data is cleaned, processed, and structured to ensure consistency and accuracy in the analysis. Missing values are handled appropriately, and feature engineering is performed if needed.

Machine Learning Models: We train four machine learning models - Logistic Regression, Support Vector Machine, Decision Tree Classifier, and K-Nearest Neighbors - using the historical landing data. GridSearchCV is employed to optimize the hyperparameters of these models, ensuring their best performance.

Visualizing Model Accuracy: The accuracy scores of all four machine learning models are visualized to provide a clear comparison of their performance in predicting successful landings.

Exploratory Data Analysis (EDA): We employ SQL queries and Matplotlib to explore relationships and trends within the data. Scatterplots, line charts, and bar charts aid in gaining insights into the launch cost dynamics and other key factors.
