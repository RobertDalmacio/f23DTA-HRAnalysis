# f23DTA-HRAnalysis

## Project Setup

Here is the link to retrieve the IBM HR Analytics Employee Attrition & Performance dataset from Kaggle: \
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data\

1. Please register and sign up for a free Kaggle account.

2. Select the Download button near the top of the page.
<img width="198" alt="Screenshot 2023-12-02 at 7 04 34 PM" src="https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/3682c1a0-b2b8-43f7-933e-62c4cd319687">

***

## Data Transformation Activity

1. Created a new table “employee_sales” with columns: Attrition, Department, JobSatisfaction & MonthlyIncome. Also rounded the data found in the ‘MonthlyIncome’ column to the nearest $1000.
![DataTransformActivity-Step1](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/c4e3bc9c-567f-4208-a540-c8b693fc4036)

2.  Filtered the data to only show results from the ’Sales Department’.
![DataTransformActivity-Step2](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/ef4c31bf-d607-4f95-b137-4b830e72251e)

3. Ordered the data by ‘JobSatisfaction’ from highest to lowest.
![DataTransformActivity-Step3](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/30b49ea2-9007-42dc-8d12-b4cc82f2b86a)

Bonus: Confirmed 4 was the highest job satisfaction rating.
![DataTransformActivity-Bonus](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/d9e00bf2-ac1c-4370-966b-cc8f5451c591)

`Conclusion: From the dataset provided and data transformations performed we were able to see a positive correlation with employees from the sales department with no attrition having the highest job satisfaction.`

***

## Data Aggregation Activity

1. Created 2 tables: 1) Salespeople with Attrition, and 2) Salespeople without Attrition
![DataAggregation-Step1a-Salespeople with Attrtion](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/13b3b907-7705-4a34-9ca1-39d32edb8dd5)
![DataAggregation-Step1b-Salespeople without Attrition](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/cc1d4163-535d-40de-b3ee-777c141adb69)

2. Created 3 statistics tables (average, min, max) showing the monthly income for: 1) All Salespeople, 2) Salespeople with Attrition, and 3) Salespeople without Attrition
![DataAggregation-Step2-All Salespeople](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/bc600947-88b7-4dfc-b027-2abcf23ada37)
![DataAggregation-Step2-Salespeople wtih Attrition](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/3a213354-9840-407c-834e-395c0a1cbd9a)
![DataAggregation-Step2-Salespeople wtihout Attrition](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/b653458b-c769-404d-b3e4-688e7425f2de)

3. Created 2 tables containing the monthly income and count of salespeople making that monthly income for: 1) Salespeople with Attrition, and 2) Salespeople without Attrition
![DataAggregation-Step3a-Salespeople wtih Attrition](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/aad3957b-a7d7-4fea-9485-aa6b79140cd3)
![DataAggregation-Step3b-Salespeople wtihout Attrition](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/0919068a-4220-46d3-9a37-f3dba989df45)

`Conclusion: From the dataset provided and data aggregations performed we were able to see that sales employees with no attrition generally have a higher monthly income compared to sales employees with attrition.`

***

## Data Visualization Activity

Created a dashboard with a histogram comparing the distribution of monthly income for salespeople with and without attrition, 
and a pie chart with the count of salespeople with and without attrition.
![DataVisualization-Dashboard](https://github.com/RobertDalmacio/f23DTA-HRAnalysis/assets/99753940/8928f016-12e0-4ce8-a07d-17d5d6f5097c)

`Conclusion: From the dataset provided and data visualizations performed we were able to create a dashboard that showcases the monthly income comparison between sales employees with and without attrition. The pie chart also highlights that 79% of the employees within the sales department are without attrition whereas the remaining 21% have attrition.`
