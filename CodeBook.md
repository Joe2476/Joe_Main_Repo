# Joe_Main_Repo
x_data <- combines x data,
y_data <- combines y data,
subject_data <- combines subject data,

mean_and_std_feature <- finds mean and standard D for data and puts them in a table
names(x_data) <- matches name with the data 

names(y_data) <- Uses descriptive activity names to name the activities in the data set

all_data <- cbind(x_data, y_data, subject_data) ## Appropriately labels the data set with descriptive variable names

averages_data <- and the code below ## (# Creates a second, independent tidy data set with the average of each variable for each activity and each subject)

write.table(averages_data, "TidyData.txt", row.name=FALSE)
