# Week 4 Project for Getting and Cleaning Data
### The R script works as follows
1. Download the zip files and extract the UCI HAR Dataset
2. Read the activity_labels.txt for data on activities and features.txt for features
3. Use various string functions to extract only the relevant features describing the mean or standard deviation of the dataset
4. Read the train.txt and test.txt files for observations corresponding to relevant features
5. Use cbind to append the activities and features data from the respective folders
6. Use rbind to add both the datasets into one final dataset
7. Convert the activity and subject columns into factors
8. Since the final dataset includes the same variable in multiple columns, it is melted and recast into a dataframe with mean summaries for each subject and activity

The Codebook describing the features and summary results can be found [here](https://srotaswati.github.io/DataScience_3_project/Codebook.html)