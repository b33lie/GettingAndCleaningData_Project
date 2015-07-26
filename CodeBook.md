# Code Book

This code book summarizes the resulting data fields in `tidydata.txt`.

## Identifiers

* `subject` - The ID of the test subject
* `activity` - The type of activity performed when the corresponding measurements were taken

## Measurements

* Mean and Standard deviation for the time in Body Accelaration axis (XYZ)
	* `tBodyAccMeanX`
	* `tBodyAccMeanX`
	* `tBodyAccMeanY`
	* `tBodyAccMeanZ`
	* `tBodyAccStdX`
	* `tBodyAccStdY`
	* `tBodyAccStdZ`
* Mean and Standard deviation for the time in Gravity Acceleration axis (XYZ)
	* `tGravityAccMeanX`
	* `tGravityAccMeanY`
	* `tGravityAccMeanZ`
	* `tGravityAccStdX`
	* `tGravityAccStdY`
	* `tGravityAccStdZ`
* Mean and Standard deviation for the time in body linear acceleration and angular velocity derived in time to obtain Jerk signals (all axis (XYZ))
	* `tBodyAccJerkMeanX`
	* `tBodyAccJerkMeanY`
	* `tBodyAccJerkMeanZ`
	* `tBodyAccJerkStdX`
	* `tBodyAccJerkStdY`
	* `tBodyAccJerkStdZ`
	* `tBodyGyroJerkMeanX`
	* `tBodyGyroJerkMeanY`
	* `tBodyGyroJerkMeanZ`
	* `tBodyGyroJerkStdX`
	* `tBodyGyroJerkStdY`
	* `tBodyGyroJerkStdZ`
* Mean and Standard deviation for the time in body gyroscope axis (XYZ)
	* `tBodyGyroMeanX`
	* `tBodyGyroMeanY`
	* `tBodyGyroMeanZ`
	* `tBodyGyroStdX`
	* `tBodyGyroStdY`
	* `tBodyGyroStdZ`
* Mean and Standard deviation for the time in Magnitude calculated using the Euclidean norm according to all the axis
	* `tBodyAccMagMean`
	* `tBodyAccMagStd`
	* `tGravityAccMagMean`
	* `tGravityAccMagStd`
	* `tBodyAccJerkMagMean`
	* `tBodyAccJerkMagStd`
	* `tBodyGyroMagMean`
	* `tBodyGyroMagStd`
	* `tBodyGyroJerkMagMean`
	* `tBodyGyroJerkMagStd`
* Mean and Standard deviation for the frequency applied using Fast Fourier Transform (FFT) in Body Accelaration axis (XYZ)
	* `fBodyAccMeanX`
	* `fBodyAccMeanY`
	* `fBodyAccMeanZ`
	* `fBodyAccStdX`
	* `fBodyAccStdY`
	* `fBodyAccStdZ`
* Mean and Standar deviation for the frequency applied using Fast Fourier Transform (FFT) in Body Gyroscope axis (XYZ) 
	* `fBodyGyroMeanX`
	* `fBodyGyroMeanY`
	* `fBodyGyroMeanZ`
	* `fBodyGyroStdX`
	* `fBodyGyroStdY`
	* `fBodyGyroStdZ`
* Mean and Standard deviation for the frequency applied using Fast Fourier Transform (FFT) in Body Accelaration and angular velocity based on previous Jerk values
	* `fBodyAccJerkMeanX`
	* `fBodyAccJerkMeanY`
	* `fBodyAccJerkMeanZ`
	* `fBodyAccJerkStdX`
	* `fBodyAccJerkStdY`
	* `fBodyAccJerkStdZ`
* Mean and Standard deviation for Magnitude calculated using the Euclidean norm and using FFT frequency
	* `fBodyAccMagMean`
	* `fBodyAccMagStd`
	* `fBodyAccMagMeanFreq`
	* `fBodyBodyAccJerkMagMean`
	* `fBodyBodyAccJerkMagStd`
	* `fBodyBodyAccJerkMagMeanFreq`
	* `fBodyBodyGyroMagMean`
	* `fBodyBodyGyroMagStd`
	* `fBodyBodyGyroMagMeanFreq`
	* `fBodyBodyGyroJerkMagMean`
	* `fBodyBodyGyroJerkMagStd`
	* `fBodyBodyGyroJerkMagMeanFreq`

## Activity Labels
* `WALKING` (value `1`): subject was walking during the test
* `WALKING_UPSTAIRS` (value `2`): subject was walking up a staircase during the test
* `WALKING_DOWNSTAIRS` (value `3`): subject was walking down a staircase during the test
* `SITTING` (value `4`): subject was sitting during the test
* `STANDING` (value `5`): subject was standing during the test
* `LAYING` (value `6`): subject was laying down during the test
