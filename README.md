Project Overview: User Behavior Analysis
Objective:
To analyze user behavior related to app usage, battery drain, screen time, data usage, and other factors using exploratory data analysis (EDA).

Dataset Overview
File: user_behavior_dataset.csv
Library Imports: pandas, matplotlib.pyplot, seaborn, and numpy.
Initial Data Exploration
Loaded the dataset and displayed the first 10 rows.
Checked the dataset's structure using .info() and .describe().
Identified missing values with data.isnull().sum().
Obtained the dataset's shape.
Key Insights & Visualizations
App Usage Time vs. Battery Drain

Goal: Determine if users with higher app usage drain more battery.
Analysis:
Created a scatter plot to visualize the relationship.
Calculated correlation: correlation = data['App Usage Time (min/day)'].corr(data['Battery Drain (mAh/day)']).
Output: Correlation value indicating the strength of the relationship.
Average Screen-On Time by Gender

Goal: Compare screen-on time between male and female users.
Analysis:
Bar plot displaying average screen-on time by gender.
Average Screen-On Time by Age Group

Goal: Analyze screen time trends across different age groups.
Analysis:
Defined age groups and calculated average screen-on time.
Plotted results as a bar chart.
Installed Apps vs. Data Usage

Goal: Explore the relationship between the number of installed apps and data consumption.
Analysis:
Created a scatter plot to visualize the relationship.
Calculated correlation between installed apps and data usage.
Average Battery Drain by Operating System

Goal: Identify battery drain differences across operating systems.
Analysis:
Calculated and visualized average battery drain for each OS using a bar chart.
Gender Effects on App Usage Time

Goal: Compare app usage time between genders.
Analysis:
Calculated average app usage time by gender and plotted the results.
User Behavior Classes Distribution

Goal: Understand the proportion of users in different behavior categories.
Analysis:
Counted user behavior classes and visualized the distribution in a pie chart.
Conclusion
This project provides valuable insights into user behavior patterns related to app usage and its impact on device performance. The visualizations help in understanding differences across demographics and categories, which can inform future design and development decisions.

