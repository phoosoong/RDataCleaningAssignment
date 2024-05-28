## Code book for tidyData.txt

this code book outline steps taken on original data sets to create tidyData.txt\
original data sets used in this project is downloaded from [this link](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)  
details of the original data sets can be found in "README.txt" of the zipped files

the full data set can be found [archive.ics.uci.edu](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) (not used in this project)

the tidyData.txt is generated from the following steps:  
the original data sets contains training data sets an  
1. extract only the columns "-mean()" and "-std()" from the X_train and X_test data
2. rename the columns to give more descriptive name, using feature names from features.txt
3. combine the label data (prefix y-) and subject data (prefix subject-) to their respective X\_ data
4. append the data sets from step 3. together
5. summarise by average of each variables, group the result data set by SubjectID and ActivityNames 

to use the run_analysis.R code, placed the already unzipped folder "getdata_projectfiles_UCI HAR Dataset" in the working directory
this tidyData.txt contains the following:
- 181 rows, 69 columns
- 1st row is the column names
- row 2 to 181 contain each record grouped by SubjectID and Activity 
- 1st column is the SubjectID, as Integer ranging from 1 to 30 
- 2nd column is the ActivityName,containing string such as WALKING or STANDING, total of 6 activities 
- 3rd column is ActivityID, as Integer ranging from 1 to 6 
- columns 4 to 69 are average of each variables in the original data sets, as Numeric  

full features list of tidyData.txt can be found in TidyFeatures.txt

