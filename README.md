# 5-BRIGHT-AUTOMOTIVE-COMPANY-CLASSIFICATION
1. Introduction
5 Bright Automotive Company is a business entity that operates within the automotive sector. This report analyzes the dataset provided, which includes various demographic and financial attributes of customers. The primary goal is to draw insights from the data that could help in understanding the customer base, their financial status, and their potential interest in automotive products.

2. Dataset Overview
The dataset contains 30 rows and 15 columns with the following attributes:

Age
Gender
Profession
Marital_status
Education
No_of_Dependents
Personal_loan
House_loan
Partner_working
Salary
Partner_salary
Total_salary
Price
Make
Sample Data
The first and last five rows of the dataset are displayed below to provide a quick glimpse of the data.

First 5 Rows
Age	Gender	Profession	Marital_status	Education	No_of_Dependents	Personal_loan	House_loan	Partner_working	Salary	Partner_salary	Total_salary	Price	Make
53	Male	Business	Married	Post Graduate	4	No	No	Yes	99300	70700	170000	61000	SUV
53	Female	Salaried	Married	Post Graduate	4	Yes	No	Yes	95500	70300	165800	61000	SUV
53	Female	Salaried	Married	Post Graduate	3	No	No	Yes	97300	60700	158000	57000	SUV
53	Female	Salaried	Married	Graduate	?	Yes	No	Yes	72500	70300	142800	61000	?
53	Male	NaN	Married	Post Graduate	3	No	No	Yes	79700	60200	139900	57000	SUV
Last 5 Rows
Age	Gender	Profession	Marital_status	Education	No_of_Dependents	Personal_loan	House_loan	Partner_working	Salary	Partner_salary	Total_salary	Price	Make
35	Male	Salaried	Divorced	Graduate	0	No	No	Yes	89500	60700	150200	61000	SUV
38	Female	Salaried	Divorced	Graduate	1	No	No	Yes	90500	70300	160800	57000	SUV
41	Male	Business	Married	Post Graduate	2	Yes	Yes	Yes	80000	60700	140700	57000	SUV
44	Male	Business	Married	Post Graduate	2	No	No	No	85000	NaN	85000	61000	SUV
51	Male	Salaried	Divorced	Graduate	0	No	No	Yes	72000	60700	132700	61000	SUV
3. Data Analysis
3.1 Demographic Distribution
Age Distribution
The dataset covers a range of ages, with customers primarily in their 30s to 50s. This indicates that the target market for 5 Bright Automotive Company comprises mature individuals who likely have a stable financial background.

Gender Distribution
There is a mix of male and female customers, with a slight predominance of males. This could suggest that marketing strategies need to be slightly more focused on male customers, but should not neglect female customers.

3.2 Financial Analysis
Salary Distribution
The dataset reveals a wide range of salaries among customers, indicating a diverse economic background. The presence of both high and low-income customers suggests that the company can offer a variety of products to meet different financial capabilities.

Total Salary
The total salary, combining individual and partner salaries, shows that many customers have substantial household incomes. This suggests that the company can target higher-end products to customers with higher combined incomes.

3.3 Loan Status
Personal and House Loans
A significant portion of the customers do not have personal or house loans, indicating financial stability. However, those with loans might be more cautious with large expenditures, so tailored financial offers could be beneficial.

4. Key Insights
Target Demographics: The primary customers are aged between 30 and 50 years, with a mix of both genders. Marketing campaigns should be designed to appeal to this age group.
Financial Stability: Most customers have a high total salary, indicating they can afford premium automotive products.
Loan Products: Many customers do not have existing personal or house loans, suggesting they have the financial capability for new investments. However, customized loan products could attract those who do have existing loans.
Education Level: A significant number of customers are post-graduates, indicating they might be more receptive to detailed product specifications and quality assurance information.
5. Recommendations
Marketing Strategy: Focus on customers aged 30-50 with high household incomes. Use targeted advertisements that highlight the premium features and quality of the automotive products.
Financial Products: Introduce flexible financial products, such as low-interest loans or installment payment plans, to attract customers who are currently servicing other loans.
Product Range: Ensure a variety of products that cater to both high-income and moderate-income customers. Premium products can target high-income customers, while more economical options can appeal to those with moderate incomes.
6. Conclusion
The analysis of the dataset for 5 Bright Automotive Company provides valuable insights into the demographics and financial status of its customers. By leveraging this data, the company can tailor its marketing strategies, financial products, and product offerings to better meet the needs and preferences of its customer base, ultimately driving sales and customer satisfaction.
How to Run the Analysis
Clone the repository:

{git clone <repository-url>
cd <repository-directory>
Install the required libraries:}

{
pip install pandas numpy matplotlib seaborn
Run the analysis script:}

{
python analysis.py
The analysis script will read the dataset, perform the analysis, and output the results.}

This report offers a comprehensive analysis of the dataset provided, highlighting key insights and actionable recommendations to help 5 Bright Automotive Company optimize its business strategies.
