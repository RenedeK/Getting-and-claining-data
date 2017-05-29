# Getting-and-cleaning-data
## Programming assignment

## Included in this repository are **4** files:

- `README.md` - this file provides an overview of the project and files included in this repository

- `Codebook.md` - describes the variables

- `run_analysis.R` - code that downloads the data, processes it, and uploads a clean dataset

- `Dataset_with_averages.txt` - final tidy dataset with the average values of each variable of each activity and each subject

## The R script "run_analysis.R" does the following:

- set the workdir to the assigned directory

- Download the dataset if it does not already exist in the working directory

- Merge the training and test datasets

- Load the activity and feature info

- Extract only the columns which reflect a mean or standard deviation

- clean the column names and use descriptive names

- Merge the two datasets and uploads a textfile with averages

## The dataset that is used can be downloaded [here](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip). 
