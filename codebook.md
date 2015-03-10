#Getting and Cleaning Data Course Project CodeBook#
This codebook describes the steps used to clean the data per the assignment instructions. 
***
The data was obtained from:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
***
The raw data file is:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
***
##Steps##
***
1.The run_analysis.R script performs the following steps to clean the data:
*Read X_train.txt, y_train.txt and subject_train.txt from the "./data/train" folder and store them in trainData, trainLabel and trainSubject variables respectively.
