#Part 1:
* First combine the respective data in training and test data sets corresponding to subject, activity and features.
* The data in features, activity and subject are then merged and the complete data is now stored in completeData.

#Part 2:
* First extract the column indices that have either mean or std in them.
* Then add activity and subject columns to the list.
* And create extractedData with the selected columns in requiredColumns.

#Part 3:
* Change activity field in extractedData which is originally of numeric type to character.
* This is so that it can accept activity names. 
* The activity names are taken from metadata activityLabels.
* Then factor the activity variable once the activity names are updated.

#Part 4:
Replacing: 
* Acc with Accelerometer
* Gyro with Gyroscope
* BodyBody with Body
* Mag Magnitude
* Character f with Frequency
* Character t with Time

#Part 5:
* First set Subject as a factor variable.
* Then create tidyData as a data set with average for each activity and subject. 
* Then order the enties in tidyData and write it into data file Tidy.txt. 
