# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Working with Time Series Data

> Flex Lesson

---

## Materials We Provide

| Topic | Description | Link |
| --- | --- | --- |
| Lesson | Lesson, part 1: Time Series Intro | [Link](./01_time_series.ipynb)|
| Lesson | Lesson, part 2: Rolling Statistics | [Link](./02_rolling_statistics.ipynb)|
| Lesson | Lesson, part 3: Autocorrelation | [Link](./03_autocorrelation.ipynb)|
| Lesson | Lesson, part 4: Decomposition | [Link](./04_decomposition.ipynb)|
| Lesson | Lesson, part 5: Practice Activity | [Link](./05_independent_practice.ipynb)|
| Lesson | Lesson, part 6: Bonus Section on Modeling | [Link](./06_bonus_time_series_models.ipynb)|
| Data Sets | Lesson, Part X | [Link](X)|
| Data Sets | Lesson, Part X | [Link](X)|
| Data Sets | Lesson, Part X | [Link](X)|
| Solutions | Solution code, Part 1 | [Link](./solution-code/01_time_series_solutions.ipynb)|
| Solutions | Solution code, Part 2 | [Link](./solution-code/02_rolling_statistics_solutions.ipynb)|
| Solutions | Solution code, Part 3 | [Link](./solution-code/03_autocorrelation_solutions.ipynb)|
| Solutions | Solution code, Part 4 | [Link](./solution-code/04_decomposition_solutions.ipynb)|
| Solutions | Solution code, Part 5 | [Link](./solution-code/05_independent_practice_solutions.ipynb)|


> **Data description**: Here are some descriptions of the datasets we're including in the `data` folder, including what they are, why we chose them, and where they are used.

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
3. Define and demonstrate techniques for correlating data points

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


## Additional Resources

If you are interested in more resources, check out the following:
- In Pandas' "datetime" library, [search for more information on`.dt` here](http://pandas.pydata.org/pandas-docs/stable/api.html).
- For additional review of these concepts, see [some inspiration from the Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/03.11-working-with-time-series.html).
- There are lots of additional tutorials on ARIMA models out there; [here is a good one](http://www.statsref.com/HTML/index.html?arima.html).
