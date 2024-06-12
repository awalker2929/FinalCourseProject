# CodeBook for UCI HAR Dataset

## Download dataset
### Dataset downloaded and extracted

## Assign data to variables
### features <- features.txt : 561 rows, 2 columns  ### activities <- activity_labels.txt : 6 rows, 2 columns  ### subject_test <- test/subject_test.txt : 2947 rows, 1 column  ### x_test <- test/X_test.txt : 2947 rows, 561 columns  ### y_test <- test/y_test.txt : 2947 rows, 1 columns  ### subject_train <- test/subject_train.txt : 7352 rows, 1 column  ### x_train <- test/X_train.txt : 7352 rows, 561 columns  ### y_train <- test/y_train.txt : 7352 rows, 1 columns
## Merge training and test sets into one
### X (10299 rows, 561 columns) is created by merging x_train and x_test using rbind() function 
### Y (10299 rows, 1 column) is created by merging y_train and y_test using rbind() function 
### Subject (10299 rows, 1 column) is created by merging subject_train and subject_test using rbind() function 
### Merged_Data (10299 rows, 563 column) is created by merging Subject, Y and X using cbind() function 

## Extract only measurements on mean and standard deviation
### TidyData (10299 rows, 88 columns) is created by selecting columns: subject, code and the measurements on the mean and standard deviation (std) for each measurement 

## Use descriptive activity names
### Entire numbers in code column of the TidyData replaced with corresponding activity taken from second column of the activities variable 

## Appropriately label the dataset
### code column in TidyData renamed into activities 
### All Acc in column’s name replaced by Accelerometer 
### All Gyro in column’s name replaced by Gyroscope 
### All BodyBody in column’s name replaced by Body 
### All Mag in column’s name replaced by Magnitude 
### All start with character f in column’s name replaced by Frequency 
### All start with character t in column’s name replaced by Time 
  ## Create a second, independent tidy data set with the average of each variable for each activity and each subject  
### FinalData (180 rows, 88 columns) is created by summarizing TidyData, taking the means of each variable for each activity and each subject

##Export final dataset
### Export FinalData into FinalData.txt file
