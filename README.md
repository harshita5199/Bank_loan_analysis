# Bank_loan_analysis

## Problem Statement:
In the context of the rapidly evolving financial sector, banks face significant challenges in accurately assessing the creditworthiness of loan applicants, leading to potential risks and financial losses. The issue lies in the reliance on traditional methods, which may not effectively capture the nuanced factors influencing a borrower’s ability to repay loans. This is particularly relevant as banks strive to balance growth with risk management, ensuring they extend credit to reliable customers while minimizing defaults. The objective of this analysis is to employ advanced data analytics techniques to evaluate and predict loan repayment behaviors, enabling banks to make more informed, data-driven decisions. By incorporating variables such as credit history, income levels, employment status, and demographic information, the goal is to improve the accuracy of loan approval processes, reduce default rates, and enhance overall financial stability.

### Objective & constraint:
  - **Business Objective:**
Enhance loan approval accuracy: To accurately assess and predict the creditworthiness of loan applicants using advanced data analytics techniques, thereby reducing default rates and enhancing the bank’s financial stability.

  - **Business Constraint:**
Regulatory compliance: Ensure the analysis complies with regulatory requirements and maintains high standards of data security and privacy while managing the complexity of integrating diverse data sources.

### Key Stakeholders: 
1. Bank Management: Interested in overall financial performance and risk management.Uses analysis to shape lending policies and strategies.
2. Loan Officers: Directly involved in the loan approval process.Benefits from improved decision-making tools and insights.
3. Risk Management Team: Focuses on minimizing financial risk and defaults.Utilizes analysis to identify high-risk applicants and develop mitigation strategies.
4. Data Analysts and Scientists: Responsible for conducting the analysis and developing predictive models.Provides actionable insights to improve the loan approval process.
5. IT Department: Ensures the technical infrastructure supports data analysis and model implementation. Manages data security and system integration.

## Approach:
1. Data Preparation: Import and clean the bank loan dataset. Transform data using Power Query Editor.
2. Exploratory Data Analysis (EDA): Generate summary statistics and initial visualizations.Segment data by key variables.
3. Interactive Dashboards: Develop dashboards for loan approval metrics, trend analysis, and risk analysis. Implement dynamic filters and slicers.
4. Key Performance Indicators (KPIs): Define and display crucial KPIs like default rates and approval ratios.
5. Advanced Analysis: Conduct correlation analysis and basic predictive insights with R or Python integration.
6. Reporting and Insights: Provide narrative summaries and actionable recommendations. Automate report updates and maintain relevance.
7. Collaboration and Sharing: Publish reports to the Power BI service for broader access. Share insights with stakeholders and establish a feedback loop for continuous improvement.

## Insights:
1: How does the ratio of good loans to bad loans compare, and what does this indicate about loan quality and debt-to-income ratios?
  - Good loans significantly outnumber bad loans, indicating overall positive loan quality, but the ratio is not ideal. The debt-to-income ratio of charged-off loan applicants is greater than that of fully paid applicants.

2: How do the loan ratio, debt-to-income ratio, and interest rates compare to ideal benchmarks?
  - Both the loan ratio and debt-to-income ratio are less than ideal, and most loans have an interest rate of 12%.

3: What is the repayment behavior of loan applicants in terms of their monthly income?
  -  Most loan applicants repay approximately 13% of their monthly income.

4: What are the statistics for loans applied for, settled, ongoing, and left unsettled in the 2021 fiscal year, and what was the recovery rate for charged-off loans?
  - In the 2021 fiscal year, approximately 38,000 loans were applied for, around 30,000 loans were settled, about 1,000 loans are currently ongoing, and around 5,000 loans were left unsettled. Only half the amount was recovered from charged-off loans.

5: How does the month-over-month ratio of funded amounts compare to received amounts?
  - The month-over-month ratio of funded amounts is less than the received amounts.

6: Which states and grades have the highest and lowest number of loan applications?
  - California has the highest number of loan applications, while Idaho has the least. Grade B has the highest number of loan applications, and Grade G has the least.

7: What are the trends in loan applications for various purposes, and which purposes have the least and highest number of applications?
  - Loan applications for renewable energy, cars, home improvement, houses, medical, small businesses, and weddings have negative month-over-month growth rates, indicating a decline in these fields. Renewable energy has the least number of loan applications, while debt consolidation has the highest.

8: Which month and state had the highest loan amount received, and what is the overall trend in loan amounts received?
  - December had the highest loan amount received, and the total loan amount received is gradually increasing across the months. California received the highest loan amount, while Nebraska received the least.

9: What is the trend in loan amounts for longer-term versus shorter-term loans and for different home ownership types?
  - More people take longer-term loans than shorter-term loans. In home ownership, mortgages make up the highest percentage of the total amount received, followed by rent.

10: What is the loan repayment likelihood based on work experience?
  - Applicants with 10+ years of work experience are most likely to fully repay their loans.

11: Which type of loan is the least in terms of total amount received?
  - Car loans are the least in terms of the total loan amount received.

12: How does Maine compare in terms of loans funded and what is the trend in Nebraska?
  - Maine has the least amount of loans funded. The total loan amount received in Nebraska gradually decreased from May onwards.

13: What is the trend in homeownership loan amounts received in California?
  - In California, rent is the highest, followed by mortgages in terms of total loan amounts received.


## Conclusion:
To enhance loan sanctioning rates and raise awareness of different loan types and interest schemes, the bank needs to increase its staffing levels. Targeted awareness campaigns should be launched in cities and states with low loan application rates to educate people about the available loan options and their benefits. Additionally, short-term loan schemes should be reviewed and redesigned to make them more attractive and accessible to potential borrowers. To minimize the number of unsettled loans, stricter control measures must be implemented to ensure timely repayment. Finally, declining loan segments should be reassessed, and more competitive interest rates should be offered to stimulate growth and attract more applicants.
