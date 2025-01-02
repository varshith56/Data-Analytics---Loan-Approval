# Data-Analytics---Loan-Approval
This project optimizes loan approval processes for financial institutions using data analytics and machine learning. By predicting loan approval outcomes based on historical data, it helps banks make data-driven decisions, reduce risks, and improve efficiency. Key techniques include logistic regression, decision trees, and data visualization.
## project objective
This project aims to optimize loan decision-making processes using machine learning techniques. The goal is to develop and compare different predictive models to automate and improve the accuracy of loan approval decisions based on historical data from L&T Financial services. The project focuses on leveraging machine learning algorithms to extract patterns and insights from financial data, making the loan approval process more efficient, objective, and less susceptible to human biases.
## Dataset Used
Source: Kaggle - L&T Financial Services Dataset
Size: Around 5,000 financial records
 - <a href = "https://github.com/varshith56/Data-Analytics---Loan-Approval/blob/main/loan_approval_dataset.csv"> Dataset</a>
## Questions
- What factors most significantly influence loan approval decisions?
- How do different machine learning models compare in predicting loan approval?
- What is the relationship between CIBIL scores and loan approval rates?
- How do factors like education and self-employment status impact loan approval?
## Process
- Data Preprocessing
   - Removal of irrelevant columns (loan_id)
   - Checking for missing values
   - Encoding categorical variables (education, self_employed, loan_status)
   - Dataset split: 70% training, 30% testing
- Models Implemented
   - Logistic Regression (91.6% training accuracy, 91.2% validation accuracy)
   - Discriminant Analysis (91.7% training accuracy, 91.8% validation accuracy)
   - Neural Network (99.5% training accuracy, 95.75% validation accuracy)
- Statistical Analysis
   - Descriptive statistics
   - Hypothesis testing
   - Multicollinearity analysis
   - Visualization of key metrics
## Insights
 - CIBIL Score Impact
   - 52% of loan entities have CIBIL scores between 707-744
   - Strong correlation between higher CIBIL scores and loan approval
 - Income and Loan Amount Relationship
   - Balanced relationship between annual income and requested loan amount crucial for approval
   - Higher income generally favors loan approval
 - Asset Influence
   - Luxury assets showed unexpected significance in approval decisions
   - Residential and commercial asset values serve as strong indicators of financial stability
 - Educational Impact
    - Graduates showed consistently higher loan approval probabilities
    - Education level serves as a relevant indicator of financial stability
 - Self-Employment Considerations
    - Self-employment status impacts approval based on stability and nature of business
    - Complex assessment required for self-employed applicants
## Conclusions
   The neural network model emerged as the most effective predictor with the highest accuracy rates (95.75% validation accuracy). The project demonstrates that machine learning can significantly improve loan approval decisions by:
   - Streamlining the approval process
   - Reducing processing times
   - Making lending decisions more equitable
   - Providing transparent insights into approval factors
     
The implementation of these models can enhance efficiency in financial institutions while maintaining accuracy in risk assessment. However, it's important to note that models should be regularly updated and monitored to adapt to changing financial landscapes.
