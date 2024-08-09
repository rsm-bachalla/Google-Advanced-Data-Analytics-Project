# Employee Satisfaction and Retention Analysis

## Objective
The primary objective of this project is to analyze employee satisfaction and its impact on employee retention. By exploring various factors such as tenure, evaluation scores, and working hours, the project aims to identify key drivers of employee turnover and provide actionable insights to improve employee retention strategies.

## Data Preprocessing

**Handling Missing Values:** Median imputation was used for missing values in key columns to ensure data completeness.

**Outlier Detection and Removal:** Outliers were identified and removed to prevent skewing the analysis results.

**Feature Engineering:** New features were created to capture more granular insights, such as tenure groups and performance metrics.

## Key Performance Indicators (KPIs)
The project focuses on several KPIs to assess employee satisfaction and retention:

**Satisfaction Scores:** Mean and median satisfaction levels among employees who stayed versus those who left.

**Tenure Analysis:** Correlation between employee tenure and satisfaction, as well as the likelihood of leaving the company.

**Work Hours:** The impact of average monthly hours worked on employee evaluation scores and retention.

**Evaluation Scores:** Relationship between employee performance evaluations and their retention rates.

**Promotion Analysis:** The effect of promotions (or lack thereof) on long-term employee satisfaction and retention.

## Machine Learning Models
To enhance the analysis and provide predictive insights, the following machine learning models were utilized:

**Logistic Regression:** Used to predict the probability of employee turnover based on satisfaction scores, evaluation metrics, and other features. The model provided interpretable results, helping identify key factors influencing retention.

**Random Forest:** A more complex model used to capture non-linear relationships between features and employee retention. This model provided insights into feature importance, highlighting the most significant factors driving turnover.

**K-Means Clustering:** Employed to segment employees into distinct groups based on satisfaction levels, tenure, and performance metrics. This clustering helped in identifying specific cohorts of employees who might require targeted retention strategies.

## Analysis and Insights:

**Satisfaction Trends:** Employees with lower satisfaction scores were more likely to leave the company. Interestingly, there was a noticeable dip in satisfaction around the four-year mark of tenure.

**Workload Impact:** Overworked employees tended to have higher evaluation scores but also had a higher likelihood of leaving, indicating possible burnout.

**Promotion and Tenure:** Lack of promotions for long-tenured employees correlated with higher turnover, suggesting that career advancement opportunities are crucial for retention.

**Feature Importance:** The Random Forest model revealed that satisfaction score, evaluation metrics, and average monthly hours were the most significant predictors of employee retention.

## Recommendations
To improve employee retention, the following strategies are recommended:

**Cap Workload:** Implement limits on the number of projects employees can take on to prevent burnout.

**Promotion Policies:** Consider promoting employees who have been with the company for at least four years or investigate the reasons for dissatisfaction at this tenure.

**Reward Systems:** Align rewards with workload contributions to ensure that employees feel adequately compensated for their efforts.

**Transparent Communication:** Make overtime policies and workload expectations clear to all employees to manage expectations and improve job satisfaction.

## Future Enhancements

**Advanced Predictive Modeling:** Explore additional machine learning models, such as Gradient Boosting Machines or Neural Networks, to further enhance the predictive accuracy of employee turnover.

**Real-Time Analytics:** Implement real-time data tracking and analysis to continuously monitor employee satisfaction and retention, allowing for proactive interventions.

**Policy Impact Simulation:** Analyze how changes in company policies (e.g., promotion timelines, workload distribution) could impact overall employee satisfaction and retention.

## Conclusion
This project provides valuable insights into the factors influencing employee satisfaction and retention. By addressing the identified issues and implementing the recommended strategies, companies can improve employee satisfaction and reduce turnover, ultimately leading to a more engaged and productive workforce.

