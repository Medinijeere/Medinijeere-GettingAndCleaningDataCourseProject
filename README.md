# Medinijeere-GettingAndCleaningDataCourseProject
# Getting and Cleaning Data - Course Project

## Overview
This project is the course project for the Getting and Cleaning Data course on Coursera. The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set.

## The Dataset
The data linked to from the course website represents data collected from the accelerometers from the Samsung Galaxy S smartphone. 

## Files
- `run_analysis.R`: R script that performs the data cleaning and summarization
- `Final_Tidy_Data.txt`: A tidy dataset with the average of each variable for each activity and each subject
- `CodeBook.md`: Describes the variables, data, and transformations

## Script Summary
The `run_analysis.R` script:
1. Downloads and unzips the dataset
2. Loads training and test datasets and merges them
3. Extracts measurements on the mean and standard deviation
4. Uses descriptive activity names
5. Labels the dataset with descriptive variable names
6. Creates a second, independent tidy dataset with the average of each variable for each activity and each subject
