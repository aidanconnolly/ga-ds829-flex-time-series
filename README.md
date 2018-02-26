# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Working with Time Series Data

> Unit 4, Flex

***This flex lesson is a WIP***

---

## Materials We Provide

TODO


> Dataset Notes:

TODO

---

## Learning Objectives

After this lessons, students will be able to:

1. Explain how time series data is distinct and how to account for it
2. Create rolling means and plot time series data
3. Perform autocorrelation on sample time series data
4. Decompose time series data into trend and residual components
5. Bonus: Explain the benefits and drawbacks of ARIMA as compared to other methods

---

## Student Requirements

Before this lesson(s), students should already be able to:

1. Manipulate data with `pandas`
2. Create basic data visualizations with Matplotlib and seaborn
3. Understand correlation

---

## Lesson Outline

> TOTAL (190 min)

I. **Foundations** (TODO min total)
- Part 1: Time Series Data (TODO min)
    - What is time series data?
    - Examples of time series data and domains that find it useful
    - Trends and seasonality
    - Preprocessing time series data with `pandas`
    - Processing date information as `DateTime` objects
    - Filtering by date with `pandas`
    - Differencing/lagging
- Practice (TODO min)
- Part 2: Rolling Means and Plotting Time Series Data (TODO min)
    - What is a trend?
    - Visualizing trends
    - Computing aggregates with `pandas` `.resample` function
    - Computing rolling averages with `pandas` 
    - Other `pandas` window functions (rolling sum, rolling max, diff)
    - Exponentially weighted windows
    - Plotting time series data
- Practice (TODO min)
- Part 3: Autocorrelation on Time Series Data (TODO min)
    - Define autocorrelation 
    - Examples of autocorrelation
    - Computing autocorrelation
    - Using the `pandas` `autocorr` function 
    - Calculating and plotting ACF and PACF using `statsmodels`
- Part 4: Decomposing Time Series (TODO min)
    - Decomposing time series into trend, seasonality, cyclical, and residual components
    - Using the `.seasonal_decompose` function
    - Plotting the seasonal, trend, and residual components of a time series
- Closing and Recap (TODO min)
   
    
II. **Bonus** (TODO min)
- Time Series Forecasting Models(15 min)
    - What are time series models?
    - Properties of time series models
    - Assumption of stationarity
    - Compare/contrast time series forecasting models
- Closing and Recap (TODO min)

---

## Installation Notes

When applicable

---


## Additional Resources

If you are interested in more resources, check out the following:
- For more information about Pandas' datetime library, search for `.dt` [here.](http://pandas.pydata.org/pandas-docs/stable/api.html)
