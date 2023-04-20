# Kenyas-Maize-Output-Time-Series
This is a time series project that utilizes Facebook prophet to predict what Kenya's Maize Output will be in 2027

![image](https://user-images.githubusercontent.com/63351043/230066193-4e79fbc5-46d2-4f1a-a881-a90b404944b1.png)

I recommend on getting this book to understand how to analyze Time Series like a Pro !!

![image](https://user-images.githubusercontent.com/63351043/231533189-1ebbbe73-c3cf-4dab-b1e4-29acbf147d1c.png)

## Handling Missing Data 
The most common methods to address missing data in time series are: 

### Imputation
When we fill in missing data based on observations about the entire data set.

### Interpolation
When we use neighboring data points to estimate the missing value. Interpolation can also be a form of imputation.

### Deletion of affected time periods
When we choose not to use time periods that have missing data at all


## Smoothing Data
Smoothing data can be done for a variety of reasons, and often real-world time series data is smoothed before analysis, especially for visualizations that aim to tell an understandable story about the data. 

While outlier detection is a topic in and of itself, if you have reason to believe your data should be smoothed, you can do so with a moving average to eliminate measurement spikes, errors of measurement, or both. Even if the spikes are accurate, they
may not reflect the underlying process and may be more a matter of instrumentation problems; this is why it’s quite common to smooth data.
#### Therefore Smoothing data is the process of removing noise from a dataset

![image](https://www.investopedia.com/thmb/AlWZjs7tasYiBJGyzVOl1cObsKU=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/dotdash_Final_Strategies_Applications_Behind_The_50_Day_EMA_INTC_AAPL_Jul_2020-03-4913804fedb2488aa6a3e60de37baf4d.jpg)

#### Pros
- Helps identify real trends by eliminating noise from the data
- Allows for seasonal adjustments of economic data
- Easily achieved through several techniques including moving averages
#### Cons
- Removing data always comes with less information to analyze, increasing the risk of errors in analysis
- Smoothing may emphasize analysts' biases and ignore outliers that may be meaningful

This being said, it is essential to smooth data despite its cons.