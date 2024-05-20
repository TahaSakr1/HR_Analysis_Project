# HR Analysis Project

This repository contains a comprehensive HR analysis report focusing on employee attrition within our organization. The analysis was performed using Power BI, a powerful business intelligence tool, to gain valuable insights into HR data, identify trends, patterns, and correlations, and provide actionable recommendations.

## Files

- `HR_Anlysis.pbix`: The main Power BI report file.
- `HR Analysis Report documentation.pdf`: Detailed documentation for the HR analysis report.

## Objectives

The primary objective of this report is to inform and guide decision-making processes to create effective strategies for retaining valuable employees and improving overall organizational performance. The report aims to:

- Analyze employee turnover rates.
- Identify factors contributing to employee attrition.
- Provide actionable recommendations to address these challenges.

## Methodology

### Data Preparation

1. **Model Creation**: A star schema was utilized to create a robust data model, including a fact table `F_HR_Employee_Attrition` and various dimension tables.
2. **Data Cleaning**: Non-essential columns were removed, and data values were understood and categorized to ensure accurate analysis.

### Analysis

1. **Measures and Facts Identification**: Both degenerated and conformed dimensions were used to provide meaningful insights.
2. **Use Case Analysis**: 
   - Relationships between attrition and factors such as overtime, education level, and training were examined.
   - Employee personas were created based on department, job role, and age group.
   - Outlier analysis was conducted using the interquartile range (IQR) method.

## Key Findings

1. **Attrition and Overtime**: More than 53% of employees who left worked overtime compared to 24% who stayed.
2. **First-Year Employees**: 30% of employees leaving due to overtime were in their first year.
3. **Gender and Age**: Males and employees aged 25-40 had the highest attrition rates.
4. **Relationship Satisfaction**: Low relationship satisfaction correlated with higher attrition.
5. **Salary Increases**: 50% of departed employees had salary increases of 11-17%.
6. **Job Level**: Lower job levels saw higher attrition rates.
7. **Tenure**: Attrition rates were highest in the first year and almost non-existent after ten years.
8. **Stock Options**: 64% of employees who left had zero stock options, and 87% had stock option levels of 0 or 1.

## Recommendations

- **Overtime Management**: Distribute overtime duties evenly and reduce overtime pressure on first-year employees.
- **Employee Surveys**: Conduct surveys before, during, and after employment to identify additional factors affecting attrition.
- **Gender-Specific Strategies**: Develop strategies to address higher attrition rates among male employees.
- **Salary Review**: Investigate salary competitiveness and job difficulty, especially for sales executives.
- **Job Level Support**: Provide additional support and development opportunities for lower job levels.
- **Retention Strategies for New Employees**: Focus on retention strategies during the critical first year of employment.

## View the Report Online

You can view the Power BI report online [here](https://app.powerbi.com/view?r=YOUR_EMBED_LINK).

## View the Report as PDF

You can view the report in PDF format [here](HR_Analysis_Report.pdf).

## Get
