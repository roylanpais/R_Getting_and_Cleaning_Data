* Submission project for the Getting and Cleaning Data Coursera course.

Dataset: "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"

* The included run_analysis.R which performs the data preparation and then followed by these steps required as described in the  project requirements:

1. Download the dataset from web if it does not already exist in the working directory.
2. Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.
3. Load feature and activity and extract columns named mean and SD.
   Also, modify column names to descriptive. (`-mean` to `Mean`, `-std` to `Std`, and remove symbols like `-`, `(`, `)`)
4. Extract data by selected columns(from step 3), and merge x, y(activity) and subject data.
   Also, replace y(activity) column to it's name by refering activity label (loaded step 3).
5. Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity.
   The result is shown in the file `tidy_dataset.txt`.
6. From the data set in step 5, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
   FinalData.txt is the exported final data after going through all the sequences described above.