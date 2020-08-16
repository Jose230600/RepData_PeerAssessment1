Project1
=========================================

 ## *"This assignment will be described in multiple parts. You will need to write a report that answers the questions detailed         below".*


## Loading and preprocessing the data

 1. Loading and preprocessing the data
  
    1. Load the data (read.csv())
    2. Process/transform the data (if necessary) into a format suitable for your analysis


**1) Code for reading in the dataset and/or processing the data**

 once the file are in your directory through read.csv function, we read the file "activity.csv"
 

```r
  setwd("D:\\econimoia 2\\Big data\\Curso10") 
  ## once the file are in your directory
  Question1 <- read.csv("activity.csv") # 1.1 Load the data (read.csv())
```

## What is mean total number of steps taken per day?

2. What is mean total number of steps taken per day?
  
    1. Calculate the total number of steps taken per day
    2. If you do not understand the difference between a histogram and a barplot, research the difference between them. Make a histogram of the total number of steps taken each day
    3.Calculate and report the mean and median of the total number of steps taken per day
    
    
    **2) Histogram of the total number of steps taken each day**

 through tapply function, we get the total of steps (sum) for each day (date), with the result we create a data frame, where the total column is the total number of steps taken each day, this information is for  the histogram





































