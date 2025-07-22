# Ahmedabad Air Quality Analysis & Prediction

## Project Goal
The initial objective was to analyze air quality in Ahmedabad and build a model to predict daily pollution levels.

## The Challenge & Pivot
This project demonstrates resilience in the face of real-world data acquisition problems. The initial plan to use a real-time API was halted due to a widespread data outage for Indian cities on the OpenAQ platform.

To overcome this, the project was successfully pivoted to use a robust, historical dataset for Ahmedabad sourced from Kaggle. This showcases adaptability and a commitment to completing the project goals despite unforeseen challenges.

## Key Findings
* Performed exploratory data analysis (EDA) to identify key pollution trends.
* Discovered a strong seasonal pattern in pollution levels using data visualizations created with Matplotlib and Seaborn.
* Found a high correlation between `PM2.5`, `PM10`, and `CO` levels.

## Modeling & Results
A Linear Regression model was developed and trained to predict the next day's PM2.5 level based on the current day's pollutant values. The final model achieved a **Mean Absolute Error of approximately 24.75 µg/m³**.

## Technologies Used
* **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Tools:** Jupyter Notebook, Git, GitHub
