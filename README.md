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

3. **Classification Modeling**:
   - Used machine learning techniques to classify comments and video content into claims or opinions.
   - Evaluated models based on accuracy, precision, recall, and F1 scores.

### Visualization
- Generated insightful visualizations to showcase patterns and relationships in the data.

## Requirements
The project utilizes the following Python packages:
- **pandas**: For data analysis and manipulation.
- **numpy**: For numerical operations.
- **scipy**: For statistical testing.
- **scikit-learn**: For regression and classification models.
- **matplotlib/seaborn**: For creating visualizations.

## Results
- **T-Test Analysis**: Determined the impact of verification status on video performance.
- **Regression Insights**: Identified user behavior trends among verified accounts.
- **Classification Accuracy**: Developed a robust model to differentiate claims from opinions in user comments.
