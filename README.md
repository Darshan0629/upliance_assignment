# Assignment

## Objective
The goal of this assignment was to analyze datasets related to:
- User behavior.
- Cooking preferences.
- Order trends.

The task included:
1. Cleaning and merging datasets.
2. Analyzing relationships between cooking sessions and user orders.
3. Identifying popular dishes.
4. Exploring demographic factors influencing user behavior.
5. Creating visualizations and a report to showcase key insights and provide business recommendations.

## Datasets Used
1. **UserDetails**: Contains user demographic information.
2. **CookingSessions**: Includes details about cooking sessions.
3. **OrderDetails**: Provides information on user orders.

## Methodology
1. **Data Cleaning**:
   - Missing values in the `Rating` column were filled with the mean rating.

2. **Data Merging**:
   - Datasets were merged using `User ID` and `Session ID` for a comprehensive view.

3. **Exploratory Data Analysis (EDA)**:
   - Relationships were explored between `Duration (mins)` (cooking session duration) and `Amount (USD)` (order amount).
   - Popular dishes were identified based on the frequency of orders.
   - Demographic factors, such as age groups, were analyzed to understand their impact on user behavior.

4. **Predictive Analysis**:
   - A simple linear regression model was developed to predict the order amount (`Amount (USD)`) based on cooking session duration (`Duration (mins)`).

5. **Visualization**:
   - Created bar plots, scatter plots, and other visualizations to present insights effectively.

6. **Summary Report**:
   - Findings and business recommendations were compiled into a text-based report.

## Key Findings
1. **Popular Dishes**:
   - The top 5 dishes ordered most frequently were identified and visualized.

2. **Relationship Between Cooking Sessions and Orders**:
   - A correlation of **X.XX** was found between cooking session duration and order amount.

3. **Demographic Insights**:
   - Users in the age group **25-35** placed the highest number of orders.

4. **Predictive Insights**:
   - The model achieved an **R-squared (R2)** value of **Y.YY**, indicating the strength of prediction.
   - For a 45-minute cooking session, the predicted order amount was **$ZZ.ZZ**.

## Business Recommendations
1. **Marketing Strategy**:
   - Focus on promoting the top 5 popular dishes.
   - Tailor marketing campaigns for users aged **25-35**.

2. **Operational Efficiency**:
   - Optimize cooking durations without compromising order quality.

3. **Future Predictions**:
   - Use the regression model to forecast order trends and optimize resources.

## Visualizations
### 1. Top 5 Popular Dishes
A bar plot showing the most frequently ordered dishes.

### 2. Cooking Duration vs. Order Amount
A scatter plot highlighting the relationship between cooking session duration and order amount.

### 3. Orders by Age Group
A bar plot showcasing the distribution of orders across different age groups.

## Conclusion
The analysis provided actionable insights into user behavior and preferences. By leveraging these findings, the business can make data-driven decisions to improve customer satisfaction and operational efficiency.

## Files Generated
- **Visualizations**: Various plots summarizing key insights.
- **Summary Report**: Saved as `summary_report.txt` for detailed findings and recommendations.
