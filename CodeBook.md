Code book

The following describes the variables, the data and the changes made to clean the database.

1.The data is downloaded, and the tables that contain the data of interest are read. Then the data set is created from the training and test data

2. Variables are created:
    2.1 features:Contains the selected characteristics of the data set.
    2.2 activities: Contains the activities carried out by the test participants. 
    2.3 subject_test: contains the observed data of the participants' tests
    2.4 x_test: contains test feature data
    2.5 y_test: contains the activity codes of the tests
    2.6 subject_train: contains the observed data participants
    2.7 x_train: contains recorded features train data
    2.8 y_train: contains train data of activities’code labels
    2.9 X: Combine the x_test and x_train data
    2.10 Y: Combine the y_test and y_train data
    2.11 subject: Combine the subject_test and subject_train data
    2.12 Merge_data: Combine X, Y and subject data
    2.13 TidyData: creates a subset of data containing the mean, and the standard deviation of the measurements
    2.14 TidyData2: contains a grouping of measurements averages by participant and activity
