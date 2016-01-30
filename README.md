##Getting and Cleaning Data

 this project demonstrates my ability to collect, work with, and clean a data set. I learned how to prepare tidy data that can be used for later analysis. I have submitted: 1) a tidy data set as described below, 2) a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data called CodeBook.md. 

In data science, wearable computing has become a craze. Companies are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is at the site where the data was obtained, which can be reached using his URL: 

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data for the project: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

I have created one R script called run_analysis.R that does the following: 
merges the training and the test sets to create one data set,
extracts only the measurements on the mean and standard deviation for each measurement,
uses descriptive activity names to name the activities in the data set,
appropriately labels the data set with descriptive variable names, and create another independent tidy data set with the average of each variable for each activity and each subject.

Tidy dataset is provided in tidydata.txt file.
