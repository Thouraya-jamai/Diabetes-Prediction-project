# Diabetes Prediction project

Features of the data set:
1. Number of pregnancies (NumTimesPrg)
2. Plasma glucose concentration (PlGlcConc)
3. Blood pressure (BloodP)
4. Thickness of triceps skin fold (SkinThick)
5. Insulin level (TwoHourSerIns)
6. Body mass index (BMI)
7. Diabetes pedigree function: heredity (DiPedFunc)
8. Age (age)
The last "HasDiabetes" column of the database (9th column) indicates whether the person is
diagnosed (1) with diabetes or not (0).
# Data Exploration
Step 1 : Read the Data!
First, we want to read and inspect the data in the database. The "pima-indians-diabetes.data.csv" 
database is supplied in CSV (Comma Separated Values) .
This is the most common format for importing and exporting spreadsheets and spreadsheets and databases.

#2.Assign each column the name of the corresponding attribute

#3.Show the structure of the base

#4. Show the data type of each variable

#5. Show first 10 lines

#6.Show only blood pressure values ("BloodP" attribute) for all individuals.

#7. show the values of ("Bloodp","age" and "HasDiabets") for the first 10 lines 

#8. Obtain statistics on individuals in the database using the "describe()" function.

#9. Create a matrix that only contains the attribute data (separate the attribute values from their membership classes).

#10. Check that the dataset does not contain empty fields.

#11. Show the number of people who have diabetes and the number of people who do not.

#12. Display the average insulin level of people with diabetes and compare it with that of people with diabetes

#13. What is the maximum body mass index for a person with diabetes.

#14. determine the most common age among people with diabetes

#15. What is the youngest person with diabetes.

#16. the average of plasma glucose concentration in diabetics and non-diabetes

#17. show the blood pressure in diabetics aged over than 30 years

#18. show the blood pressure in diabetics aged over than 30 years and have BMI over than 25

#19. show the blood pressure in diabetics aged over than 30 years or have BMI over than 25

#20. show the correlation between columns


# Data visualisation

#1. show the plasma glucose concentration and thr blood pressure in diabetics and non diabetics

#2. #show blood pressure in relation to age

#3. #Show the distribution of values for each attribute

#4. #show the distribution of HasDiabetes

# Data preparation
   # Data cleaning
     #Filter the values of the ‘SkinThick’ attribute to determine non-zero values.
     #Calculate the median of these values
     #Replace zero values of the "SkinThick" attribute with the median.
     #Why can't we do the same thing with the "NumTimesPrg" attribute?
  # Data Rescaling
  # Data standardization
  #Construct the new dataset (100 individuals and 2 attributes).
  #data normalization of the new dataset
# K-means
# K-medoids
# FCM


