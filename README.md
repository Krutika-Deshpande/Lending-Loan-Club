# Lending Loan Club - Dataset from Kaggle Competition

Analyzed the data to identify and interpret factors contributing to loan amount, status, purpose of the loan and performed classification using Decision Tree and Random Forest classification


<img width="1000" height="300" src = "https://blog.lendingclub.com/wp-content/uploads/2017/05/LC-Logo-Official-min.png">

## About Dataset
 Dataset is available at https://www.kaggle.com/wendykan/lending-club-loan-data/data for download.\
 It contains **74** columns and **887379** rows.\
 The dataset contains information of the loan borrowers such as the personal details of the borrower member,listed amount of the loan   applied for by the borrower, Interest Rate on the loan, category provided by the borrower for the loan request and current status of the loan, etc.
 
## Data Preprocessing
 
 1. Columns with 70 % missing values and those with descriptive information like 'url' and 'desc' are deleted which reduces the number of columns to 52.
 2. Data Dictionary gives the column description which helps in further data pre processing.
 3. Columns with randomly generated field, redundant information and leaking information from the future are dropped with 36 columns in the dataframe.

## Exploratory Data Analysis
 
  1. Average amount loan given based on loan grade
  2. Interest rate of the loan  loan grade
  3. Distribution of loan amount by loan status
  4. Frequency and Percentage Distribution of loan status 
  5. Employment tenure of borrowers for issued loan
  
 ## Machine Learning
 
 Loan status "Current",                                           
        "Fully Paid" ,                                            
        "Charged Off",                                             
        "Late (31-120 days)",                                    
        "Issued",                                                  
        "In Grace Period",                                         
        "Late (16-30 days)",                                      
        "Does not meet the credit policy. Status:Fully Paid",       
        "Default",                                                  
        "Does not meet the credit policy. Status:Charged Off" , 
  is predicted based on the loan amount, the purpose of loan, employment tenure of the loan borrower, their annual income, etc.
  
  1. Decision Tree Algorithm
     Decision tree - Normal data set
     Accuracy : 0.931943196387549
    
 
  2. Random Forest Algorithm
     Random Forest - Normal data set
     Accuracy : 0.9594426418116397
 


## Conclusion
 With the implementation of decision tree and random forest model, we can predict the loan status for borrowers and the likelihood of loan approval considering the factors like annual income, employment status, years of experiennce, purpose of the loan. 
   
 
  
 
