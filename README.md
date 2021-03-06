The dataset is derived from the Human Activity Recognition Using Smartphones Dataset
Version 1.0 (www.smartlabs.ws) [1]
=====================================================================================

Description of the original data and code book for variables in the new data set are in file CodeBook.md

The code in run_analysis.R creates a new data set from the original one by:
1. merging the test and train data from the original datasets,
2. selecting only the mean and standard deviation values for each measurement, 
3. creating a tidy data set with the averages of each variable grouped by activity and test subject.

(The specific transformations are described in comments in the file.)

The new data set is in file run_analysis.txt



=====================================================================================
[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012