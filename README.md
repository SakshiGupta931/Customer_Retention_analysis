# Customer Retention Hypothesis Testing: Impact of Loyalty Programs

## Project Overview
This project explores whether customers enrolled in a loyalty program are more likely to be retained compared to non-members. Using hypothesis testing on customer data, we determine if the observed difference in retention rates is statistically significant.

## Research Question
**Does being part of a loyalty program increase customer retention compared to non-members?**
The objective is to statistically validate if loyalty program membership has a measurable effect on customer retention.

## Defining Hypotheses
- **Null Hypothesis (H₀):**  
  There is no difference in retention rates between loyalty members and non-members.  
  *p₁ ≤ p₂*

- **Alternative Hypothesis (H₁):**  
  Loyalty members have a higher retention rate than non-members.  
  *p₁ > p₂*

Where:  
- *p₁* = retention rate of loyalty members  
- *p₂* = retention rate of non-members

## Dataset and EDA
- Sample Size: 500 customers (dummy data)
- Key Features:
  - `Loyalty_Member` (1 = Yes, 0 = No)
  - `Retained` (1 = Yes, 0 = No)

### Exploratory Steps:
- Checked for null values, duplicates, and proper data types
- Analyzed:
  - Overall retention rate
  - Loyalty vs non-loyalty customer counts
  - Retention rate by group

## Visualizations
- **Bar Plot:** Group-wise retention comparison
The visuals clearly show loyalty members are more likely to be retained than non-members.

## Hypothesis Testing Results
- **Z-statistic:** 5.234  
  The difference is 5.234 standard deviations away from the null hypothesis.
  
- **P-value:** < 0.00001  
  Since p ≪ α (0.05), we reject the null hypothesis.

## Conclusion
There is strong statistical evidence that loyalty program members have significantly higher customer retention rates than non-members. This validates the effectiveness of the loyalty program.

## Business Insights
- Loyalty programs are effective in increasing customer retention.
- Recommended strategies:
  - Continue investment in loyalty programs
  - Enhance rewards or personalized benefits
  - Target non-members with special offers to encourage loyalty enrollment

## Tools Used
- Python (Pandas, NumPy, SciPy, Seaborn, Matplotlib)
- Hypothesis Testing: Proportion Z-test
- Google Coalb Notebook

## Project Files
- `loyalty_retention_analysis.ipynb`: Google Colab notebook with full analysis
- `customer_data.csv`: Sample dataset 
- `README.md`: Project documentation

## Author
Sakshi Gupta  
Data Analyst | Python | SQL | Statistics | Excel  
New Delhi, India
