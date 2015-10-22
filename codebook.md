Variable Description

train: data set from the training partition
test: dat set from the test partition

data: data set merging training and test data

info: features or measurements names of each row of the data set

ndata1: subset of the data set with onbly the mean() of the measurements
ndata2: subset of the data set with onbly the std() of the measurements
ndata: subset with ndata1 and ndata2

actlev: activity levels and their codes

nrowt: code of activity levels for training data set
nrows: code of activity levels for test data set
nrow: code of activity levels for the whole data set

x:  assign the name of the activity to each row according to their respective code

data$activity: vector of activity in the data set and assigne the name of each activity

subtrain: subject number for the training data set
subtest: subject number for the training data set
subj: subject number for the whole data set

data$subject: vector of subject in the data set and assigne the code of each subject

tdata: independet tidy data set with the average of each variable for each activity and each subject

