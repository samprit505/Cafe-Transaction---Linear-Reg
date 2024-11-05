                              Steps Involved:
Dropped the POS Bill ID, customer profile name, Date, Time columns as they are not useful for linear reg
Removed duplicate rows from the entire dataset
Converted the categorical columns into Dummy variables through One Hot Encoding
Scaled the data points using StandardScaler to bring them to a similar scale
Obtained correlation matrix to check if any 2 Independent Variables (X) are highly correlated. Removed one of them if found 
After doing all the above steps, performed the linear regression
