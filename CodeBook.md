---
title: "CodeBook"
output: html_document
---
##The original data for this project come from:  

 
 =================================================================================================== 
 Human Activity Recognition Using Smartphones Dataset 
 Version 1.0 
 =================================================================================================== 
 Jorge L. Reyes-Ortiz(1,2), Davide Anguita(1), Alessandro Ghio(1), Luca Oneto(1) and Xavier Parra(2) 
 1 - Smartlab - Non-Linear Complex Systems Laboratory 
 DITEN - Universit???  degli Studi di Genova, Genoa (I-16145), Italy.  
 2 - CETpD - Technical Research Centre for Dependency Care and Autonomous Living 
 Universitat Polit???cnica de Catalunya (BarcelonaTech). Vilanova i la Geltr??? (08800), Spain 
 activityrecognition '@' smartlab.ws  
 =================================================================================================== 
 
 
 Notes:  
 ====== 
 - Features are normalized and bounded within [-1,1]. 
 - Each feature vector is a row on the text file. 
 - The units used for the accelerations (total and body) are 'g's (gravity of earth -> 9.80665 m/seg2). 
 - The gyroscope units are rad/seg. 
 - A video of the experiment including an example of the 6 recorded activities with one of the participants can be seen in the following link: http://www.youtube.com/watch?v=XOEN9W05_4A 
 
 
###Features and Activities data sets have been combine along with Test/Training data sets to create a single file 
 
 
###Names of Activities have been cleaned up to make it easy to understand 
 
 
###Finally a tidy data set with the average of each variable for each activity and each subject was created  
 
 
###The tidy data set has the following variables: 
 
 
 "Subjects"                      "Activity"                      "tBodyAcc_mean_X"               
 "tBodyAcc_mean_Y"               "tBodyAcc_mean_Z"               "tBodyAcc_std_X"                
 "tBodyAcc_std_Y"                "tBodyAcc_std_Z"                "tGravityAcc_mean_X"            
 "tGravityAcc_mean_Y"            "tGravityAcc_mean_Z"            "tGravityAcc_std_X"             
 "tGravityAcc_std_Y"             "tGravityAcc_std_Z"             "tBodyAccJerk_mean_X"           
 "tBodyAccJerk_mean_Y"           "tBodyAccJerk_mean_Z"           "tBodyAccJerk_std_X"            
 "tBodyAccJerk_std_Y"            "tBodyAccJerk_std_Z"            "tBodyGyro_mean_X"              
 "tBodyGyro_mean_Y"              "tBodyGyro_mean_Z"              "tBodyGyro_std_X"               
 "tBodyGyro_std_Y"               "tBodyGyro_std_Z"               "tBodyGyroJerk_mean_X"          
 "tBodyGyroJerk_mean_Y"          "tBodyGyroJerk_mean_Z"          "tBodyGyroJerk_std_X"           
 "tBodyGyroJerk_std_Y"           "tBodyGyroJerk_std_Z"           "tBodyAccMag_mean"              
 "tBodyAccMag_std"               "tGravityAccMag_mean"           "tGravityAccMag_std"            
 "tBodyAccJerkMag_mean"          "tBodyAccJerkMag_std"           "tBodyGyroMag_mean"             
 "tBodyGyroMag_std"              "tBodyGyroJerkMag_mean"         "tBodyGyroJerkMag_std"          
 "fBodyAcc_mean_X"               "fBodyAcc_mean_Y"               "fBodyAcc_mean_Z"               
 "fBodyAcc_std_X"                "fBodyAcc_std_Y"                "fBodyAcc_std_Z"                
 "fBodyAcc_meanFreq_X"           "fBodyAcc_meanFreq_Y"           "fBodyAcc_meanFreq_Z"           
 "fBodyAccJerk_mean_X"           "fBodyAccJerk_mean_Y"           "fBodyAccJerk_mean_Z"           
 "fBodyAccJerk_std_X"            "fBodyAccJerk_std_Y"            "fBodyAccJerk_std_Z"            
 "fBodyAccJerk_meanFreq_X"       "fBodyAccJerk_meanFreq_Y"       "fBodyAccJerk_meanFreq_Z"       
 "fBodyGyro_mean_X"              "fBodyGyro_mean_Y"              "fBodyGyro_mean_Z"              
 "fBodyGyro_std_X"               "fBodyGyro_std_Y"               "fBodyGyro_std_Z"               
 "fBodyGyro_meanFreq_X"          "fBodyGyro_meanFreq_Y"          "fBodyGyro_meanFreq_Z"          
 "fBodyAccMag_mean"              "fBodyAccMag_std"               "fBodyAccMag_meanFreq"          
 "fBodyBodyAccJerkMag_mean"      "fBodyBodyAccJerkMag_std"       "fBodyBodyAccJerkMag_meanFreq"  
 "fBodyBodyGyroMag_mean"         "fBodyBodyGyroMag_std"          "fBodyBodyGyroMag_meanFreq"     
 "fBodyBodyGyroJerkMag_mean"     "fBodyBodyGyroJerkMag_std"      "fBodyBodyGyroJerkMag_meanFreq" 
  
