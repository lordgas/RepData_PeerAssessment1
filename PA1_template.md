Reproducible Research: Peer Assessment 1
================================================

## Loading and preprocessing the data

```r
activity<-read.csv("activity.csv")

activity$date<-strptime(activity$date, format="%Y/%m/%d")
str(activity)
```

```
## 'data.frame':	17568 obs. of  3 variables:
##  $ steps   : int  NA NA NA NA NA NA NA NA NA NA ...
##  $ date    : POSIXlt, format: NA NA ...
##  $ interval: int  0 5 10 15 20 25 30 35 40 45 ...
```



## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
