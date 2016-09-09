#About the R Code

File with R code "run_analysis.R" perform 5 following steps:

A. Merging the training and the test sets to create one data set.
  - Reading files
  - Reading trainings tables
  - Reading testing tables
  - Reading feature vector
  - Reading activity labels
  - Assigning column names
  - Merging all data in one set
   
B. Extracting only the measurements on the mean and standard deviation for each measurement
  - Reading column names

C. Using descriptive activity names to name the activities in the data set

D. Appropriately labeling the data set with descriptive variable names

E. Creating a second, independent tidy data set with the average of each variable for each activity and each subject
  - Making second tidy data set
  - Writing second tidy data set in txt file

#Variables:

1. x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
2. x_data, y_data and subject_data merge the previous datasets to further analysis.
3. features contains the correct names for the x_data dataset, which are applied to the column names stored in
