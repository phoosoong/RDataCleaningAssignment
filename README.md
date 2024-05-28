# RDataCleaningAssignment

original data sets used in this project is downloaded from [this link](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)  
details of the original data sets can be found in "README.txt" in the zipped files

the full data set can be found [archive.ics.uci.edu](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) (not used in this project)

## What does it do
the code **run_analysis.R** is used to generated **tidyData.txt**, a tidied up version of the original data sets  

the details about the generated data set can be found in Codebook.md  

to use the run_analysis.R code, placed the already unzipped folder "getdata_projectfiles_UCI HAR Dataset" in the working directory  

the structure should be

    workingDir/run_analysis.R
    workingDir/getdata_projectfiles_UCI HAR Dataset/UCI HAR Dataset
    
## Notes: license terms copied from original data sets  
License:
========
Use of this dataset in publications must be acknowledged by referencing the following publication [1] 

[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. International Workshop of Ambient Assisted Living (IWAAL 2012). Vitoria-Gasteiz, Spain. Dec 2012

This dataset is distributed AS-IS and no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.

Jorge L. Reyes-Ortiz, Alessandro Ghio, Luca Oneto, Davide Anguita. November 2012.
