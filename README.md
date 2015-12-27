# Getting and Cleanning Data

Coursera Course Project

Preparations for the project: download the dataset and unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive


Set the folder as the working directory and run run_analysis.R


# In the run_analysis.R, I followed the instuctions of the project and partitioned my code into five steps:
Step 1: Merges the training and the test sets to create one data set

Step 2: Extracts only the measurements on the mean and standard deviation for each measurement

Step 3: Uses descriptive activity names to name the activities in the data set

Step 4: Appropriately labels the data set with descriptive activity names

Step 5: Creates a 2nd, independent tidy data set with the average of each variable for each activity and each subject


Use data <- read.table("Cleaned_TidyData.txt.txt") to read the data, this is the result dataset I uploaded. 

It is 180x68 because there are 30 subjects and 6 activities
