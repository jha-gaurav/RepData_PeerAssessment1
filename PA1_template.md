# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data


```r
data1 <- read.csv("activity.csv", header = TRUE, stringsAsFactors = FALSE)
data1$date <- as.Date(data1$date, "%Y-%m-%d")
```
## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
