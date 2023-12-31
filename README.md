# Bank-Loan-Study

A complete Data Science Project with Data Analysis and Machine Learning Model using the Bank Loan Dataset.

Provided two datasets of a finance company trying to figure out the attributes of customers who don't have a sufficient credit history but take advantage of this and default on their loans. Task is to use EDA to analyze patterns in the data, ensuring that capable applicants are not rejected with the help of a Machine Learning model that predicts if a loan applicant is likely to default or not.

 - Datasets Link - https://www.kaggle.com/datasets/amity024/data-sources
 - Excel file with analysis - https://docs.google.com/spreadsheets/d/1HxdeWxGIlmXDKtyBYdXbO7Vo3Gzt1GKh/edit?usp=drive_link&ouid=104137864428177038957&rtpof=true&sd=true

 - The first file is a presentation showcasing all the insights recieved from the EDA process on Excel as well as Python. The access to the Excel file with all the analysis is commented in the PDF on page number 4 as well.


 - The second file is the cleaning process of the datasets using python and merging the datasets for the model. Some parts of the analysis were also performed in the jupyter file.


 - Finally, the Machine Learning Model uses a Random Forest Regressor to predict the target(0 or 1) applicant, 1 representing a defaulter and 0 representing a repayor. The model has a Mean Absolute Error of only 0.02, achieving 98 accuracy on Validation Data.
