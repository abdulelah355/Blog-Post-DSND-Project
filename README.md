# Developer Insights and Compensation Analysis

## Project Overview

This project analyzes trends in developer tools, technologies, and compensation using survey data. The analysis follows the CRISP-DM framework, focusing on data exploration, cleaning, modeling, and visualization. The primary goals of the project are:

1. Identify trends in developer tools and technologies.
2. Predict developer compensation based on key features.
3. Provide actionable insights for stakeholders in the technology sector.

## Blog Post

A non-technical summary of this project is available in a blog post:

**Blog Title**: Developer Insights and Compensation: Navigating the Tech Landscape

[Read the full blog post on Medium](https://medium.com/@abdulelahalkhelaifi1/developer-insights-and-compensation-navigating-the-tech-landscape-d3655a393cac)

This post is tailored for a non-technical audience, highlighting key findings, visuals, and actionable business takeaways without delving into technical implementation details.

## Repository Contents

### Files in the Repository

- **`notebook.ipynb`**: The main Jupyter Notebook containing all the code, analysis, and visualizations for the project.
- **`data/survey_results_public.csv`**: The raw dataset used for the analysis, containing survey responses from developers worldwide.
- **`README.md`**: This file, which provides an overview of the project, its objectives, methodology, and results.

### Key Libraries Used

- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating visualizations.
- **seaborn**: For enhanced data visualizations.
- **scikit-learn**: For machine learning and data preprocessing.

## Methodology

### CRISP-DM Process

1. **Business Understanding**:

   - Investigate trends in programming languages, developer roles, and industries.
   - Identify how developer type and experience impact compensation.

2. **Data Understanding**:

   - Explore the structure, dimensions, and quality of the survey data.
   - Analyze missing values and data distributions.

3. **Data Preparation**:

   - Handle missing values using domain-specific knowledge.
   - Standardize compensation values by converting all currencies to USD.
   - One-hot encode categorical variables for modeling.

4. **Modeling**:

   - Use a linear regression model to predict developer compensation.
   - Evaluate model performance with metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.

5. **Evaluation**:

   - Assess the model's predictions to ensure they align with domain expectations.
   - Highlight key features affecting compensation.

6. **Deployment**:
   - Provide actionable insights and visualizations for stakeholders.

## Results and Insights

### Key Questions Answered

1. **What are the most common programming languages used by developers in different industries?**

   - JavaScript and Python are the most popular languages across industries, with their prevalence varying based on industry type.

2. **How does developer type impact total compensation?**

   - Developer types such as "Engineering Manager" and "Site Reliability Engineer" show higher average compensation.

3. **What is the preferred programming language for developers based on their role?**
   - Python is widely used by Data Scientists and Machine Learning Specialists, while JavaScript dominates among Front-End and Full-Stack Developers.

### Model Performance

- **Mean Squared Error (MSE)**: 1,135,047,637
- **Mean Absolute Error (MAE)**: 27,742
- **R-squared**: 0.084
- **Adjusted R-squared**: 0.082

### Feature Importance

Key factors influencing compensation include:

- Developer roles like "Blockchain" and "Site Reliability Engineer."
- Years of experience in development.

## Visualizations

- Heatmaps showcasing missing data patterns.
- Bar charts illustrating popular programming languages and their distribution across industries and roles.
- Compensation distributions by developer type and experience level.

## Acknowledgments

- The dataset used in this analysis is from the [Stack Overflow Developer Survey](https://insights.stackoverflow.com/survey).
- Special thanks to the open-source community for providing the tools used in this project.

Thank you for visiting this repository. We hope these insights prove valuable for your business, hiring, or personal career decisions. If you have any questions or suggestions, feel free to open an issue or submit a pull request.

## Contact

For questions or feedback, please reach out via the repository's issue tracker.

---
