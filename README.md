# Time-series-Wellness
Child Mind Institute — Problematic Internet Use (Kaggale Competition)

Project Overview
The goal of this project is to predict the SII-a measure for Problematic Internet Use using time-series data combined with various physical activity indicators. This includes training a machine learning model to extract from physical activity data those behavioral patterns that are associated with excessive use of the internet.

Dataset Description
The dataset includes:

Time-series Actigraphy Data: Wrist-worn accelerometer data for physical activity tracking.
Demographics: Age, gender, and other personal details.
Physical Measures: Heart rate, BMI, and blood pressure.
Internet Use Metrics: Daily hours spent online and internet addiction test results.

Key Steps in the Project

Data Loading & Cleaning:
Handled missing data.
Cleaned time-series data using Python libraries like pandas and numpy.

Feature Engineering:
Extracted relevant features like average activity levels, step counts, and ENMO (Euclidean Norm Minus One).
Generated rolling averages and moving windows for time-series analysis.

Model Development:
Implemented models using both Machine Learning and Deep Learning
Applied supervised learning techniques for classification.

Visualization:
Used Matplotlib, Seaborn, and Plotly for data exploration.
Time-series plots for activity patterns across different age groups.

Evaluation Metrics:
Performance measured using Quadratic Weighted Kappa (QWK).
Other metrics: RMSE, MAE, and F1-Score.

Tools & Libraries Used
Python: Pandas, NumPy, Scikit-Learn, Pytorch
Visualization: Matplotlib, Seaborn, Plotly
Time-Series Handling: Statsmodels, Scipy, Scikit-Multiflow
Data Management: Parquet, CSV

Results & Insights
Identified a correlation between reduced physical activity and higher internet use.
Time-series data revealed activity dips during periods of excessive internet usage.

