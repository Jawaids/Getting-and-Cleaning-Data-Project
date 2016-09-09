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

1. X (x_data), S (subject), and Y (y_data) contain the data from the downloaded files.
2. Features contains the correct names for the x_data dataset, which are applied to the column names stored.
