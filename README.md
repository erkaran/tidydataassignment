# tidy data assignment

This is my submission for the course project of the Getting and Cleaning Data Coursera course from Johns Hopkins University.
The R script, `run_analysis.R` can be run as long as the "UCI HAR Dataset" (i.e. where data is present) is  your working directory. It does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The end result is shown in the file `tidy.txt`.

IMPORTANT requires plyr package
