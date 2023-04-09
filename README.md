# new-car-price-prediction
I have a dataset containing complete car details such as name,company,year,Price,kms_driven	and fuel_type 

Firstly i clean the data, then create a model  and finally i predict price of a new car

Cleaning Dataset:  i go through all the columns i found all columns are object type , nan values are in dataset etc.

My tasks are *remove catogorical values from year column and convert it into numerical value  
*remove 'ask for price' value from price column and convert into numerical
*remove kms from each value of kms column and convert into numerical
*remove nan from fuel type column
*change car name to first 3 words of each value

modeling:after cleaning my data split to train and test, apply OneHotEncoder in columns name, company, fuel_type using column transfer , then make pipeline using linear regression and transformed columns

fix random state for getteing a good model (good r_2 score) 

Finally predict new car price


