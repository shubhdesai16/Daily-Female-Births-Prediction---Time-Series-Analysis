**Daily Female Births Prediction - Time Series Analysis**

**Overview**
This repository focuses on the analysis and prediction of the number of daily female births using the Daily Female Birth dataset. The project employs supervised learning techniques specifically designed for time series data.

**Contents**
**Business Understanding**

**Problem Statement:** Predict the number of female births on any given day.

**Importance:** Accurate predictions can enhance planning and resource allocation in healthcare and related sectors.

**Data Source**
The dataset, named "Daily Female Births," includes the number of daily female births along with the date.

**Data Preparation**

**Features Extraction:** Extracted relevant features from the date column, such as the day of the week and month.
**Handling Missing Values and Outliers:** Ensured data integrity by addressing missing values and outliers.
**Normalization/Standardization:** Applied normalization or standardization where necessary.

**Methodology**

**Time Lag & Window Sizes:**
Analyzed different configurations of time lags and window sizes.

**Evaluated multiple configurations:** 1 time lag & 3 window size, 6 time lag & 8 window size, 7 time lag & 9 window size.

**Univariate Analysis:** Examined patterns and trends within the date column.

**Modeling Process**
**Algorithm Selection:** Utilized various regression algorithms including Linear Regression, Lasso Regressor, ElasticNet, SVM Regressor, Dummy Regressor, and K Neighbors Regressor.

**Evaluation Metrics:** Used metrics like Mean Squared Log Error, Median Absolute Error, Mean Absolute Error (MAE), and Mean Squared Error (MSE) to evaluate model performance.

**Results**
**Best Model:** Linear Regression with 1 time lag and 3 window sizes, demonstrating the lowest error rate and best prediction accuracy.
**Model Performance:** Detailed performance metrics for the best model:

Mean Squared Log Error: 0.02162
MAE: 5.32119
MSE: 6.45583
Median Absolute Error: 4.75796

**Conclusions**

**Future Improvements:** Suggestions for incorporating more features, advanced models, or refining the current model.
**Real-life Application:** Potential applications in hospital staffing and resource planning.
**Value to Client:** Enhanced planning and resource allocation for stakeholders.
**Key Learnings**: Summarized insights and learnings from the project.

Author
Shubh Desai
