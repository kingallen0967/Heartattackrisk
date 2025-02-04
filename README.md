# Heartattackrisk
Topic: Heart Attack Risk

Objective of the Analysis
This analysis is intended to provide an overview of the risk of heart attack of various age groups as well as cholesterol and liproprotein levels. The study also provides a predictive model for determining the likelihood of heart attacks.

Questions
1. What is the average distribution for total cholesterol, heart heart and diabetes levels across various age grades?
2. What is the relationship between Total Cholesterol and Heart Attack?
3. Determines if high cholesterol levels increase heart attack risk?
4. How does LDL and HDL infleunce Total cholesterol levels?
5. Generate the predictive model to determine likelihood of developing a heart attack?

Data collection and description
The dataset was obtained from https://www.kaggle.com/datasets/shriyashjagtap/heart-attack-risk-assessment-dataset
The data set consist of 10 column and 1000 rows.
Data transformation
The obtained csv file was imported into excel using the powerquery wizard and analyzed.
The columns were accessed and set to appropriate date  types.
A new column "Gender" was created grading 1 as Male and 0 as "Female" using power query(=if (sex)=1 then male else female and the data set was loaded into the excel.
The data set was evaluated to remove outliers from the age column by evaluating the lower and upper boundary.

=IF(A2<$N$6,"wrong",IF(A2>$N$7,"wrong","correct"))

