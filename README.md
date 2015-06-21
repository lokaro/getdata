Course Project
=========================

All infos are in comments of run_analysis.R. I dublicate it here!

- I downloaded zip file: 
download.file("https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip ", destfile = "data.zip", method = "curl") 

- And Unzip it to "getdata" folder!

- I wrote 5 small sections:
1. Merge datas: X, Y and subject
2. Get mean and std from features.txt. Put it to X names
3. Read activities from activity_labels.txt and put it to Y names
4. Write all clean data
5. And write second variance of clean data

- setwd() to "getdata" folder

- source("run_analysis.R")

- and: write.table(result, "data_set_with_the_averages_without_header.txt", row.names = FALSE) 
