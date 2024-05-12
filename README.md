# Home-equity-loan-default-Adv-Excel-Project
Project: Analyzing Home Equity dataset for drawing inferences on loan defaults

Introduction: A home equity loan - also known as an equity loan, home equity installment loan, or second mortgage - is a type of consumer debt. Home equity loans allow homeowners to borrow against the equity in their homes. The loan amount is based on the difference between the home’s current market value and the homeowner’s mortgage balance due. Such loans tend to be of a fixed rate.

Learning Outcomes: 1) Analyze HMEQ data using MS Excel to draw meaningful insights on loan defaults
                   
                   2) Use MS Excel efficiently whilst dealing with various business problems to facilitate effective decision making

Scenario: The Home Equity dataset (HMEQ) contains baseline and loan performance information for 5,960 recent home equity loans. The target (BAD) is a binary variable indicating whether an applicant eventually defaulted or was seriously delinquent. This adverse outcome occurred in 1,189 cases (20%). For each applicant, 12 input variables were recorded.

Business objective: Analyze the Home Equity data captured by the bank and answer the analysis asks that can be implied to reduce loan defaults by the customers.

Data, Information for case analysis: Data is provided as an xlsx file. Below is the source and attribute information.
Source Link: https://www.kaggle.com/datasets/ajay1735/hmeq-data
Data Description:
   BAD: 1 = client defaulted on loan; 0 = loan repaid
   
   LOAN: Amount of the loan requested
   
   MORTDUE: Amount due on existing mortgage
   
   VALUE: Value of current property
   
   REASON: The purpose of loan application. DebtCon = debt consolidation; HomeImp = home improvement
   
   JOB: Six occupational categories
   
   YOJ: Years at present job
   
   DEROG: Number of major derogatory reports
   
   DELINQ: Number of delinquent credit lines
   
   CLAGE: Age of oldest trade line in months
   
   NINQ: Number of recent credit lines
   
   CLNO: Number of credit lines
   
   DEBTINC: Debt-to-income ratio

Analysis Asks: 1. What is the maximum amount of loan requested by a customer of the bank whose JOB falls under the “Office” category? (Use array formula)
               2. How many customers have their respective debt-to-income ratio greater than the average DEBTINC?
               3. Calculate the total amount of top five mortgage dues using appropriate functions in Excel.
               4. Determine the number of derogatory reports for the trade line with age 227.12990511 months, using Match and Index functions.
               5. What is the average value of property for a self-employed client who has defaulted on the loan? (Use array formula)
               6. Examine the relationship between the loan purpose and number of delinquent credit lines. Note down the inferences drawn.
               7. What can you deduct about the debt-to-income ratio in relation to job?
               8. Create a pivot table detailing the number of delinquent credit lines for each job category in relation to the reason column. Then determine the number of delinquent 
                  credit lines for the “ProfExe” job category where the reason is given as “HomeImp”.
               9. Design a pivot chart highlighting the total mortgage due across different job categories in relation with the reason for loan and show the results for loan defaulters. 
                  Note down the observations drawn.
               10. Create a dashboard with two pivot charts:
                        ● One showing the total number of credit lines taken across job categories for loan defaulters, using “REASON” column as slicer
                        ● Another for debt-to-income ratio across job categories with years at job as slicer
                   Slice and dice the charts where debt consolidation is cited as the reason along with a decade of job experience. Also, draw meaningful insights from the dashboard.

Inferences: Mentioned in the .XLSX file labled "Home equity loan default Adv Excel Project" for each problem statement seperately.
