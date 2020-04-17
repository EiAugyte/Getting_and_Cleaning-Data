# Peer-graded Assignment: Getting and Cleaning Data Course Project

This is the course project for peer graded Assigment of Getting and Cleaning Data Coursera course.
The R script - `run_analysis.R`, perform following steps: 

1. Download and unzip the dataset from URL source, if it does not already exist in the working directory
2. Loads `activity` and `feature` info 
3. Loads training and testing datasets, but keeping only those columns which reflect a `mean` or `standard` deviation (accoring to instructions)
4. Loads `activity` and `subject` data for each dataset, and as well merges those columns with the mdataset
5. Merges two datasets
6. Converts activity and subject columns into factors
7. Creates a tidy dataset (file `tidy.txt`) that consists of the average (`mean`) value of each variable for each subject and activity pair
