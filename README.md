**Loan Approval Prediction Using Decision Tree Classifier**

**Project Overview**
This project aims to predict loan approval for a user based on various financial and personal attributes using a Decision Tree Classifier. The dataset includes features such as age, job, marital status, education, balance, housing status, duration of the contact, and the number of contacts during the campaign. The target variable, approval, indicates whether a loan was approved or denied. The model achieved an accuracy of 0.866.

**Features**
The model considers the following variables to make predictions:

**age**: The age of the user.   
**job**: The type of job the user holds (e.g., management, technician, etc.).   
**marital**: Marital status of the user (e.g., single, married, divorced).    
**education**: Level of education (e.g., primary, secondary, tertiary).   
**balance**: The account balance of the user.   
**housing**: Whether the user has a housing loan (yes/no).   
**duration**: Duration of the last contact in seconds.   
**campaign**: Number of contacts performed during the campaign.   
**approval**: Target variable indicating if the loan was approved (encoded as 0 or 1).   
**Model Performance and Accuracy:**   The model achieved an accuracy score of 0.866, indicating that it correctly predicts loan approval 86.6% of the time on the test data.

**Installation and Usage**   
To run this project locally, follow the steps below:  

**Clone the repository:**          
  git clone https://github.com/A-Pavan-Kumar/Loan_Approval_Classifier.git        
  cd Loan_Approval_Classifier      
**Run the model:**      
  Use the following script to train the Decision Tree model and predict loan approval:      
    python loan_approval_model.py   

**File Structure**    
  **loan_approval_model.py**: Contains the code to preprocess data, train the model, and make predictions.      
  **data/**: Folder containing the dataset used for training the model.       
  **README.md**: Project description and usage instructions.    

**How to Contribute**   
If you find any issues or want to improve the project, feel free to fork the repository and submit a pull request. Contributions are welcome!
