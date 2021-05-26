# GettingAndCleaningDataProject


This is the course project of getting and cleaning data. The pruprose of this assignment is to collect, work with, and clean the given dataset that has been provided. You can access the link given below to get information on the dataset we have worked on.
<http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones>

### Files in the Project
- run_analysis.R : The R script file which is used to collect and tidy the data
- CodeBook.md : A code book that describing all the variables used, the data used, the result, and transformations performed to clean up the data.
- tidydata.txt : The final document that contains the required solution.

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

You should create one R script called run_analysis.R that does the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
#In the run_analysis.R script, were recreated each step.

This file 'run_analysis.R' contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file.

About this R script
File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work):

### Merging the training and the test sets to create one data set.
1.1 Reading files

1.1.1 Reading trainings tables 

1.1.2 Reading testing tables

1.1.3 Reading feature vector

1.1.4 Reading activity labels

1.2 Assigning column names

1.3 Merging all data in one set

### Extracting only the measurements on the mean and standard deviation for each measurement

2.1 Reading column names

2.2 Create vector for defining ID, mean and standard deviation

2.3 Making nessesary subset from setAllInOne

3 Using descriptive activity names to name the activities in the data set

4.1 Appropriately labeling the data set with descriptive variable names

4.2 Creating a second, independent tidy data set with the average of each variable for each activity and each subject

5.1 Making second tidy data set

5.2 Writing second tidy data set in txt file
