1. Downloading the datasets callled UCI HAR Dataset

2. Assigning variables names to each data , such as 
      features <- features.txt    
      activities <- activities_labels.txt
      subject_test <- subject_test.txt
      x_test <- test/X_test.txt
      y_test <- test/y_test.txt
      subject_train <- test/subject_train.txt
      x_train <- test/X_train.txt
      y_train <- test/y_train.txt
 
3. Merging training ang test sets using rbind() and cbind()
 
4. Extracting the measurements on mean and standard deviation for each measurement
    tidydata is created by merged_data
  
5.  Appropriately labelling the datasets with variables names
 
6. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
      write out the tidy dataset to finaldata.txt  
 
