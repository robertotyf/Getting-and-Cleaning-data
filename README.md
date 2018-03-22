<h1>Getting and Cleaning Data </h1> 

<h2>Course Project </h2>

<h3>You should create one R script called run_analysis.R that does the following.</h3>

1.  Merges the training and the test sets to create one data set.
2.  Extracts only the measurements on the mean and standard deviation for each measurement.
3.  Uses descriptive activity names to name the activities in the data set
4.  Appropriately labels the data set with descriptive activity names.
5.  Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

<h3>Steps to work on this course project</h3>

1.  Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
2.  Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
3.  Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.

<h3>Dependencies</h3>

run_analysis.R file will help you to install the dependencies automatically, plyr package is used.
