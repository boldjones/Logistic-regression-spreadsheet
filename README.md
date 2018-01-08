# Logistic-regression-spreadsheet
Sample logistic regression spreadsheet I did that calculates the risk profile of customers using 4 independent beta variables. The 4 input variables are

 1). Auto EFT payments: binomial, enter either 1 or 0
 2). FRP CL: Customer's credit limit, enter any value positive value
 3). Segment Code: enter any value 
 4). Prepay customer: binomial, enter either 1 or 0
 
The data used originally was real customer data, but for this GH upload purposes, I have modified it to mock data. Cox-Snell and Nagelkerke r^2 values were calculated with a surprisingly high degree of fit at least on the original data. Regression was done in Excel using Excel's Solver addon.
The Data and the regression related coefficients and values are on the tab titled "Data and Regression" of the uploaded Excel spreadsheet, while the "Input Sheet" can be used to enter values to see the final regression values in action.
