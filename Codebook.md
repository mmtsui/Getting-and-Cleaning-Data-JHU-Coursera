# Codebook for Getting and Cleaning Data Course Project

## Introduction
This is a codebook describing the final dataset. 

The data was collected for the UCI research project titled: "Human Activity Recognition Using Smartphones Data Set". The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

For more information on the project, please visit: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Below are more descriptions on the variables in the final dataset. 

## Activity Labels
These are the conditions each participant completed and it's respective codings.

1. WALKING: subject walked during the experiment
2. WALKING_UPSTAIRS: subject walked up a staircase during the experiment
3. WALKING_DOWNSTAIRS: subject walked down a staircase during the experiment
4. SITTING: subject was sitting during the experiment
5. STANDING: subject was standing during the experiment
6. LAYING: subject was laying during the experiment

## Variables
These are the variables or feature signals selected for the database. The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. Measures for each of these variables were collected for every subject during the performance of an activity. 

- tBodyAcc-XYZ
- tGravityAcc-XYZ
- tBodyAccJerk-XYZ
- tBodyGyro-XYZ
- tBodyGyroJerk-XYZ
- tBodyAccMag
- tGravityAccMag
- tBodyAccJerkMag
- tBodyGyroMag
- tBodyGyroJerkMag
- fBodyAcc-XYZ
- fBodyAccJerk-XYZ
- fBodyGyro-XYZ
- fBodyAccMag
- fBodyAccJerkMag
- fBodyGyroMag
- fBodyGyroJerkMag

The set of variables that were estimated from these signals are: 
- mean(): Mean value
- std(): Standard deviation

Abbreviations: 
- t = "time"; These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz.
- f = "frequency"; Indicates frequency domain signals.
- Mag = "magnitude"
- Acc = "Accelerometer"
- Gyro = "Gyroscope"
