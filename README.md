DataCleaningProject
===================
This project for "Getting and Cleaning Data" takes different datasets about human activity recognition using smartphones and 30 volunteers doing 
6 different activities (e.g. walking, standing, laying).   The R script does the following:

1)  Merges the various data frames for training and test groups using the cbind() function.
2)  Merges the various data frames for the column headers, from those datasets including "features."
3)  Appends the headers, training data, and test data into one large file using teh rbind() function.
4)  Subsets the data frame from Step 3 to includde only the 66 of the 561 measures that involve mean or standard deviation.
5)  Creates a tidy data set from the resulting data frame.

Enjoy!
Justin Fortier
7/27/14
