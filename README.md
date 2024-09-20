# 📊 Social Media Demographic Analysis: Predicting User Interests by Location 🌍

## Project Overview
This project explores how user demographics (urban, suburban, rural) impact social media engagement on platforms like Instagram. Using a dataset from Kaggle, we analyze the relationship between a user's location and their engagement with specific content categories (e.g., sports, entertainment, travel). By leveraging machine learning and statistical analysis, the project aims to predict user demographics based on content preferences.

## Key Questions ❓
Can we predict user demographics based on their social media behavior?
How do interests differ across urban, suburban, and rural users?

## Data 📊
Source: Kaggle
Variables: Demographics (urban, suburban, rural), Interests (lifestyle, travel, sports), and user engagement (likes, comments, reposts).
Data Preparation:
Cleaning duplicate entries.
Creating new features such as total engagement per user.
Aggregating data by content category and demographic type.

## Methodology 🧑‍💻
### Exploratory Data Analysis (EDA):
Visualized correlations using histograms and box plots to uncover trends.

### Predictive Modeling:
Implemented a Random Forest Model to predict user demographics based on engagement data.
Utilized Feature Engineering to include engagement ratios and time-based activity.

### Statistical Tests:
Conducted ANOVA and Chi-square tests to check significant differences in engagement across demographics.

## Visualizations 📈
Multi-group histograms show engagement by demographic type across different content categories.
Confusion matrix heatmap visualizes predictions from the Random Forest model, highlighting which content categories correlate with each demographic.

## Ethical Considerations 🔒
Informed Consent: Clear communication on how user data is handled.
Data Privacy: Anonymized data, compliant with privacy regulations.
Bias Mitigation: Balanced dataset to avoid skewed predictions.

## Challenges 🚧
Dataset Limitations: Only a few interest categories and focus on multiple countries, not just the U.S.
Dynamic Nature of Social Media: Trends shift rapidly, making continuous updates necessary.

## Future Work 🚀
Expand Dataset: Include more diverse interest categories and focus specifically on Instagram.
Improve Modeling: Explore advanced machine learning models.
Real-Time Analysis: Integrate real-time data for trend detection.
