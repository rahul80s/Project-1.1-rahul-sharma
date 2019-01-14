# Project-1.1-rahul-sharma
Project-1.1-rahul-sharma

Use Excel and Functions
1. Find the best input variable for predicting FE using suitable statistical test(s).

2. Fit a Simple Linear Regression Model using the selected input variable. Use the formulas
discussed in the class to calculate the coefficients.

3. Observe the relationship between the Input variable and FE and analyze if they maintain
a linear relationship using a suitable chart in Excel.

4. Use appropriate transformation of input variable if the relation above is not linear. Build
the Regression model after transformation. Please ask the course instructor for help in
variable transformation, if you required so.

5. Calculate the MAPE (Mean Absolute percentage Error) and R2 of the model. Implement
the model on the test data and find out the test accuracy as well. The formula and small
note for the error calculation are given at the end of the document.

6. Use a random sampling method to divide the dataset in to 3 parts. Use rand() function.

a. Take 2 parts for modeling and 1 part for testing at a time randomly.

b. Check the modeling Error statistics (as given in previous point 5) of the model
and test on the 3rd part of the data for testing the error.

c. Iterate this process 3 time to cover all possible selection of 2 parts for modeling
and the 3rd part for testing. There are 3 possible combination in this way. So you
would end up with creating 3 models on three different dataset.

d. Calculate the average model accuracy (Use Error formulas from 5.) and average
test accuracy. Judge if they are consistent and provide your comment on what
you observe.

e. Compute the Beta coefficients by taking average of the three models.

f. Test the final Accuracy by implementing the model on 2011 dataset.

Use Excel Data Analysis tool

7. Use Data Analysis feature of Excel to bypass the co-efficient calculation formulas and
compute the Regression Model directly.

8. You should be able to repeat all the points asked under “Use Excel” using Data Analysis
tool. You may need to do the random sampling separately here as well.

Use MySQL

9. Upload the 2010 and 2011 dataset into a MySQL database named “fuel_economy”. The
table name should be “fe2010” and “fe2011” respectively.

10. You have already calculated the beta coefficients for the full 2010 dataset. Insert two
additional columns for the beta coefficients in the “fe2010” table and populate the
columns with beta values. You can just take the previously calculate beta values to
populate here. Remember the beta values will be constant for each column here.

11. Once point 10. is done, Calculate the Predicted value for “feb2011” table by using the
input variable from “feb2011” and beta coefficients from “feb2010” table. Insert the
predicted values in an additional column in table “feb2010”.

Ans 1 ->
