# Ford GoBike Tripdata Analysis
## by Bex


## Dataset

> Ford GoBike dataset contains almost 520k unique rides information divided into 13 columns. This dataset provides insights into each rides duration, start and end times, start and end stations as well as whether the user was just a customer or a member.


## Summary of Findings

While exploring the dataset, lots of interesting trends were found. First of all, majority of rides lasted between 5-50 minutes with large outliers like 23 hours. For the analyses to be correct and not biased, only that group of the data was the focus throughout the rest of the investigation. Secondly, the magnitude of user types differed significantly where there almost 100k customers, the subscribers were 4 times more. However, the average ride durations were longer for customers throughout the year 2017. Also, autumn was the best season for biking in that year. When looked at the rental counts in each day of the week, it turned out that weekdays had always seen much higher numbers. Contrastingly, although there were much more rides during weekdays, the rides in weekedns tend to be much longer.


## Key Insights for Presentation

Several plot types have been used to communicate the key findings. The distribution of duration times were plotted using a histogram with a logarithmic transform. Clustered bar charts were used to depict the duration and number of rentals versus user types. To look at three features of rides at the same time, Seaborn's FacetGrid plot type was very handy.

## Links

The dataset used in this project can be found [here](https://s3.amazonaws.com/baywheels-data/2017-fordgobike-tripdata.csv.zip)