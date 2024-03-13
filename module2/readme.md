Data Analysis for the Life Sciences | Rafael A Irizarry and Michael I Love


HOMEWORK 
download the femaleMiceWeights.csv using downloader package in your path. 
1. Read in the file femaleMiceWeights.csv and report the body weight of the mouse in the exact name of the
 column containing the weights.
 2. The [ and ] symbols can be used to extract specific rows and specific columns of the table.
 What is the entry in the 12th row and second column?
 3.  You should have learned how to use the $ character to extract a column from a table and return it as a vector.
 Use $ to extract the weight column and report the weight of the mouse in the 11th row.
 4. The length function returns the number of elements in a vector. How many mice are included
 in our dataset?
 5. To create a vector with the numbers 3 to 7, we can use seq(3,7) or, because they are consecutive, 3:7. View
 the data and determine what rows are associated with the high fat or hf diet. Then use the mean function to
 compute the average weight of these mice.
 6. One of the functions we will be using often is sample. Read the help file for sample using
 ?sample. Now take a random sample of size 1 from the numbers 13 to 24 and report back the weight of the
 mouse represented by that row. Make sure to type set.seed(1) to ensure that everybody gets the same answer


HOMEWORK - 2 
library(ggplot2)
 data(msleep)
 1. Read in the msleep_ggplot2.csv file with the function read.csv and use the function class
 to determine what type of object is returned.
 2. Now use the filter function to select only the primates. How many animals in the table are primates?
 Hint: the nrow function gives you the number of rows of a data frame or matrix.
 3. What is the class of the object you obtain after subsetting the table to only include primates?
 4. Now use the select function to extract the sleep (total) for the primates. What class is this object?
 Hint: use %>% to pipe the results of the filter function to select.
 5. Now we want to calculate the average amount of sleep for primates (the average of the numbers
 computed above). One challenge is that the mean function requires a vector so, if we simply apply it to
 the output above, we get an error. Look at the help file for unlist and use it to compute the desired
 average.
