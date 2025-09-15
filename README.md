🚀 IBM Applied Data Science Capstone Project

This project is the final course of the IBM Data Science Professional Certificate and demonstrates the application of the complete data science methodology to a real-world scenario.

📌 Project Overview

SpaceX has disrupted the space industry by drastically reducing launch costs through the reusability of its Falcon 9 first stage. A single launch costs about $62 million, compared to over $165 million from competitors. Predicting whether the first stage will successfully land provides critical insights into cost savings and operational efficiency.

The goal of this project is to analyze SpaceX launch data and predict first-stage landing success using data science and machine learning techniques.

🎯 Key Questions

How do variables such as payload mass, launch site, orbit type, and flight count affect first-stage landing success?

Has the rate of successful landings improved over time?

Which machine learning algorithm performs best for this binary classification problem?

🔬 Methodology

Data Collection

Retrieved launch records using the SpaceX REST API.

Performed web scraping from Wikipedia to enrich the dataset.

Data Wrangling & Preparation

Filtered and cleaned raw datasets.

Handled missing values.

Applied One-Hot Encoding to categorical variables for ML compatibility.

Exploratory Data Analysis (EDA)

Used SQL queries to extract insights.

Built visualizations to explore relationships between payload mass, orbit, site, and landing outcome.

Interactive Visualization

Developed geospatial maps with Folium.

Created interactive dashboards with Plotly Dash for deeper exploration.

Predictive Modeling

Built and tuned multiple classifiers:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

Evaluated performance using accuracy, precision, recall, and F1-score.

Identified the most effective model for predicting landing outcomes.

🛠️ Tools & Technologies

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Folium)

SQL (SQLite)

APIs & Web Scraping (Requests, BeautifulSoup)

Dashboards (Plotly Dash)

Jupyter Notebooks

📈 Outcomes

Identified key factors influencing Falcon 9 first-stage landing success.

Demonstrated improvement trends in landing success over the years.

Compared machine learning models and highlighted the most effective approach for binary classification.
