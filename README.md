# ML-LOGISTIC_REGRESSION
REGRESSION ANALYSIS

1)Predicting Price of Used Car, CART :-

The file ToyotaCorolla.xlsx contains the data on used cars (Toyota Corolla) on sale during late summer of 2004 in The Netherlands. It has 1436 records containing details on
38 attributes, including Price, Age, Kilometers, HP, and other specifications. The goal is to predict the price of a used Toyota Corolla based on its specifications
Data Preprocessing: Create dummy variables for the categorical predictors (Fuel Type
and Color). Split the data into training (50%), validation (30%), and test (20%) datasets.
Ran a regression tree (RT) with the output variable Price and input variables Age_08_04, KM, Fuel_Type, HP, Automatic, Doors, Quarterly_Tax, Mfg_Guarantee, Guarantee_Period, Airco, Automatic_Airco, CD Player, Powered_Windows, Sport_Model, and Tow_Bar.Compare the prediction errors of the training, validation, and test sets byexamining their RMS error and by plotting the three boxplots.
Noted the effect of turning the price variable into a categorical variable. Created a new variable that categorizes price into 20 bins of equal counts and repartitioned the data keeping Binned Price instead of Price. 
Ran a classification tree(CT) with the same set of input variables as in the RT, and with Binned Price as the output variable. Compared the tree generated by the CT with the one generated by the RTCompare the predictions in terms of the predictors that were used, the magnitude of the difference between the two predictions, and the advantages and disadvantages of the two methods

2)Financial condition of banks, Logistic Regression :-

The file Banks.xlsx includes data on a sample of 20 banks. The Financial Condition (Y)column records the judgment of an expert on the financial condition of each bank. This
dependent variable takes one of two possible values -- weak or strong -- according to thefinancial condition of the bank. 
The predictors are two ratios used in the financial analysis of banks: TotLns&Lses/Assets (X1) is the ratio of total loans and leases to totalassets and TotExp/Assets (X2) is the ratio of total expenses to total assets. The target is to use the two ratios for classifying the financial condition of a new bank.
Ran a logistic regression model (on the entire dataset) that models the status of a bank as a function of the two financial measures provided. Specify the success class as weak
(this is similar to creating a dummy that is 1 for financially weak banks and 0 otherwise),and use the default cutoff value of 0.5.

3)Identifying good system administrators, Logistic Regression :-

A management consultant is studying the roles played by experience and training in a system administrator's ability to complete a set of tasks in a specified amount of time. In
particular, she is interested in discriminating between administrators who are able to complete given tasks within a specified time and those who are not. Data are collected
on the performance of 75 randomly selected administrators. They are stored in the file System Administrators.xlsx.
The variable Experience (X1) measures months of full-time system administrator experience, while Training (X2) measures the number of relevant training credits. The dependent variable Completed (Y) is either Yes or No, according to whether or not the administrator completed the tasks.
