#Code Book

##Data Set Name
tidy_data

##File Type
Text file

##Title
Averages of Human Activity Recognition Using Smartphones Data Set

##Description
Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, they captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. 

This data set was created by doing two major transformations: 1) extracts the mean and standard deviation measurements of the Human Activity Recognition database mentioned above and 2) computes the average of each variable for each activity and each subject.

##Format
A data set with 180 observations on the following 88 variables. The following abbreviations are used in the variable names:
* acc - refers to accelerometer
* gyro - refers to the gyroscope
* mag - refers to magnitude
* jerk - refers to jerks
* leading 't'- refers to the time
* leading 'f" - refers to the frequency
* gravity - refers to gravity
* mean - refers to means (averages)
* std - refers to standard deviation
* X, Y, or Z - refers to the 3-axial linear acceleration or 3-axial angular velocity

The 88 variables are:
* subject: a numeric vector. ID of the subjects.
* activity_label: a factor with 6 levels LAYING, SITTING, STANDING, WALKING, WALKING_DOWNSTAIRS, WALKING_UPSTAIRS. Activity type.
* tBodyAccmeanX: a numeric vector.
* tBodyAccmeanY: a numeric vector.
* tBodyAccmeanZ: a numeric vector.
* tBodyAccstdX: a numeric vector.
* tBodyAccstdY: a numeric vector.
* tBodyAccstdZ: a numeric vector.
* tGravityAccmeanX: a numeric vector.
* tGravityAccmeanY: a numeric vector.
* tGravityAccmeanZ: a numeric vector.
* tGravityAccstdX: a numeric vector.
* tGravityAccstdY: a numeric vector.
* tGravityAccstdZ: a numeric vector.
* tBodyAccJerkmeanX: a numeric vector.
* tBodyAccJerkmeanY: a numeric vector.
* tBodyAccJerkmeanZ: a numeric vector.
* tBodyAccJerkstdX: a numeric vector.
* tBodyAccJerkstdY: a numeric vector.
* tBodyAccJerkstdZ: a numeric vector.
* tBodyGyromeanX: a numeric vector.
* tBodyGyromeanY: a numeric vector.
* tBodyGyromeanZ: a numeric vector.
* tBodyGyrostdX: a numeric vector.
* tBodyGyrostdY: a numeric vector.
* tBodyGyrostdZ: a numeric vector.
* tBodyGyroJerkmeanX: a numeric vector.
* tBodyGyroJerkmeanY: a numeric vector.
* tBodyGyroJerkmeanZ: a numeric vector.
* tBodyGyroJerkstdX: a numeric vector.
* tBodyGyroJerkstdY: a numeric vector.
* tBodyGyroJerkstdZ: a numeric vector.
* tBodyAccMagmean: a numeric vector.
* tBodyAccMagstd: a numeric vector.
* tGravityAccMagmean: a numeric vector.
* tGravityAccMagstd: a numeric vector.
* tBodyAccJerkMagmean: a numeric vector.
* tBodyAccJerkMagstd: a numeric vector.
* tBodyGyroMagmean: a numeric vector.
* tBodyGyroMagstd: a numeric vector.
* tBodyGyroJerkMagmean: a numeric vector.
* tBodyGyroJerkMagstd: a numeric vector.
* fBodyAccmeanX: a numeric vector.
* fBodyAccmeanY: a numeric vector.
* fBodyAccmeanZ: a numeric vector.
* fBodyAccstdX: a numeric vector.
* fBodyAccstdY: a numeric vector.
* fBodyAccstdZ: a numeric vector.
* fBodyAccmeanFreqX: a numeric vector.
* fBodyAccmeanFreqY: a numeric vector.
* fBodyAccmeanFreqZ: a numeric vector.
* fBodyAccJerkmeanX: a numeric vector.
* fBodyAccJerkmeanY: a numeric vector.
* fBodyAccJerkmeanZ: a numeric vector.
* fBodyAccJerkstdX: a numeric vector.
* fBodyAccJerkstdY: a numeric vector.
* fBodyAccJerkstdZ: a numeric vector.
* fBodyAccJerkmeanFreqX: a numeric vector.
* fBodyAccJerkmeanFreqY: a numeric vector.
* fBodyAccJerkmeanFreqZ: a numeric vector.
* fBodyGyromeanX: a numeric vector.
* fBodyGyromeanY: a numeric vector.
* fBodyGyromeanZ: a numeric vector.
* fBodyGyrostdX: a numeric vector.
* fBodyGyrostdY: a numeric vector.
* fBodyGyrostdZ: a numeric vector.
* fBodyGyromeanFreqX: a numeric vector.
* fBodyGyromeanFreqY: a numeric vector.
* fBodyGyromeanFreqZ: a numeric vector.
* fBodyAccMagmean: a numeric vector.
* fBodyAccMagstd: a numeric vector.
* fBodyAccMagmeanFreq: a numeric vector.
* fBodyBodyAccJerkMagmean: a numeric vector.
* fBodyBodyAccJerkMagstd: a numeric vector.
* fBodyBodyAccJerkMagmeanFreq: a numeric vector.
* fBodyBodyGyroMagmean: a numeric vector.
* fBodyBodyGyroMagstd: a numeric vector.
* fBodyBodyGyroMagmeanFreq: a numeric vector.
* fBodyBodyGyroJerkMagmean: a numeric vector.
* fBodyBodyGyroJerkMagstd: a numeric vector.
* fBodyBodyGyroJerkMagmeanFreq: a numeric vector.
* angletBodyAccMeangravity: a numeric vector.
* angletBodyAccJerkMeangravityMean: a numeric vector.
* angletBodyGyroMeangravityMean: a numeric vector.
* angletBodyGyroJerkMeangravityMean: a numeric vector.
* angleXgravityMean: a numeric vector.
* angleYgravityMean: a numeric vector.
* angleZgravityMean: a numeric vector.

##Source
Human Activity Recognition Using Smartphones Data Set: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
