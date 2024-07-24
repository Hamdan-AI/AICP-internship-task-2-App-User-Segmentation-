# AICP-internship-task-2-App-User-Segmentation-


## User Behavior Analysis

This repository contains a Python script for analyzing user behavior on an application. The analysis includes exploratory data analysis, visualization, clustering, and anomaly detection.

### Prerequisites

- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

### Data

The dataset `userbehaviour.csv` is used in this analysis, which contains the following features:
- `Average Screen Time`
- `Average Spent on App (INR)`
- `Status` (Installed/Uninstalled)
- `Ratings`
- `New Password Request`
- `Last Visited Minutes`

### Steps Performed

1. **Loading Data and Initial Analysis:**
   - Load the dataset and check for null values.
   - Display column information and descriptive statistics.

2. **Screen Time and Spending Analysis:**
   - Calculate and display the highest, lowest, and average screen time.
   - Calculate and display the highest, lowest, and average amount spent on the app.

3. **Visualization:**
   - Scatter plot of Spending Capacity vs. Screen Time categorized by user status (Installed/Uninstalled).
   
   ![Spending Capacity vs. Screen Time](https://github.com/Hamdan-AI/AICP-internship-task-2-App-User-Segmentation-/blob/main/Spending%20capacity%20vs%20screen%20time.png)
   
   - Scatter plot of Ratings vs. Average Screen Time categorized by user status.
   
   ![Ratings vs. Average Screen Time](https://github.com/Hamdan-AI/AICP-internship-task-2-App-User-Segmentation-/blob/main/ratings%20vs%20average%20screen%20time.png)
   
   - Clustering of users based on selected features using K-means clustering.
   - Scatter plot of user segmentation.
   
   ![User Segmentation](https://github.com/Hamdan-AI/AICP-internship-task-2-App-User-Segmentation-/blob/main/user%20segmentation.png)
   
   - Correlation matrix to visualize relationships between features.
   
   ![Correlation Matrix](https://github.com/Hamdan-AI/AICP-internship-task-2-App-User-Segmentation-/blob/main/corelation%20matrix.png)

4. **Clustering:**
   - Select relevant features and standardize them.
   - Apply K-means clustering and visualize the segments.

5. **Correlation Analysis:**
   - Convert the `Status` column to numeric values.
   - Compute and plot the correlation matrix.

6. **Anomaly Detection:**
   - Apply Isolation Forest for anomaly detection.
   - Display anomalies detected in the dataset.

### Code

```python
# (Include your code here)
