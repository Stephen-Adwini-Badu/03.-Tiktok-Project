# TikTok Project

## Overview
This project explores user engagement and content performance on TikTok by analyzing the relationship between account verification status, video view counts, and user behavior. It incorporates statistical testing, regression modeling, and classification analysis to derive actionable insights.

## Objectives
### Objective 1: Two-Sample T-Test
- **Hypotheses**:
  - **Null Hypothesis (H₀):** There is no significant difference in video view counts between verified and non-verified users.
  - **Alternative Hypothesis (H₁):** There is a significant difference in video view counts between verified and non-verified users.
- **Insight Goal**: Understand the impact of verification status on video viewership.

### Objective 2: Regression Modeling
- **Goal**: Develop a regression model to analyze user behavior within verified accounts.
- **Use Case**: Identify patterns and factors influencing user engagement among verified creators.

### Objective 3: Classification Modeling
- **Goal**: Create classification models to distinguish between claims and opinions in TikTok comments and videos.
- **Use Case**: Enhance content moderation and insight extraction by accurately categorizing user-generated content.

## Methodology
### Data Preparation
- Import essential libraries and prepare the dataset for analysis.
- Clean and preprocess data, ensuring consistency and quality.

### Analysis and Modeling
1. **Two-Sample T-Test**:
   - Compare video view counts between verified and non-verified users.
   - Perform hypothesis testing to determine statistical significance.

2. **Regression Modeling**:
   - Perform exploratory data analysis (EDA) to identify key predictors.
   - Train and validate the regression model on the verified user subset.
     
![Image](https://github.com/user-attachments/assets/d942bab8-eb15-4b2b-870c-316ad12a9378)

3. **Classification Modeling**:
   - Used machine learning techniques to classify comments and video content into claims or opinions.
   - Evaluated models based on accuracy, precision, recall, and F1 scores.
   - Utilized confusion matrices to visualize model results
     
![Image](https://github.com/user-attachments/assets/b8200788-813d-41bb-a522-62c80e3ec677)

### Feature Importance
- Generated visualizations to showcase the most impactful variables in each model.
  
![Image](https://github.com/user-attachments/assets/7f7160f0-8af8-41a8-926d-b64608a4fb07)

## Results
- **T-Test Analysis**: Determined the impact of verification status on video performance.
- **Regression Insights**: Identified user behavior trends among verified accounts.
- **Classification Accuracy**: Developed a robust model to differentiate claims from opinions in user comments.
