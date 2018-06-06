# diabetes_patients_readmission_prediction

'''Predict hospital readmission probabilites for diabetes patients.
I have used python libraries-pandas,numpy and sk-learn to predict the reorder probabilities.
a.) Data preprocessing: I have done data preprocessing to clean the data and impute the missing values. 
For example: The age is given in the format: [10,20). I have used regex operators to extract the age and approximated it to 25.
b.) I converted the categorical variables using Lableencoder.
c.) It is intersting to note that the data set is unbalanced. The readmitted cases are very less.
So I used SMOTE- Synthetic minority over sampling technique to balance the classes. 
d.) Finally I used random forests to predict the reorder probabilities. '''
