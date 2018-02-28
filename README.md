# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Working With Time Series Data

> Flex Lesson

---

## Materials We Provide

| Topic | Description | Link |
| --- | --- | --- |
| Lesson | Lesson, Part 1: Time Series Intro | [Link](./01_time_series.ipynb)|
| Lesson | Lesson, Part 2: Rolling Statistics | [Link](./02_rolling_statistics.ipynb)|
| Lesson | Lesson, Part 3: Autocorrelation | [Link](./03_autocorrelation.ipynb)|
| Lesson | Lesson, Part 4: Decomposition | [Link](./04_decomposition.ipynb)|
| Lesson | Lesson, Part 5: Practice Activity | [Link](./05_independent_practice.ipynb)|
| Lesson | Lesson, Part 6: Bonus Section on Modeling | [Link](./06_bonus_time_series_models.ipynb)|
| Data Sets | Lesson, Part X | [Link](X)|
| Data Sets | Lesson, Part X | [Link](X)|
| Data Sets | Lesson, Part X | [Link](X)|
| Solutions | Solution Code, Part 1 | [Link](./solution-code/01_time_series_solutions.ipynb)|
| Solutions | Solution Code, Part 2 | [Link](./solution-code/02_rolling_statistics_solutions.ipynb)|
| Solutions | Solution Code, Part 3 | [Link](./solution-code/03_autocorrelation_solutions.ipynb)|
| Solutions | Solution Code, Part 4 | [Link](./solution-code/04_decomposition_solutions.ipynb)|
| Solutions | Solution Code, Part 5 | [Link](./solution-code/05_independent_practice_solutions.ipynb)|


> **Data description**: Here are some descriptions of the data sets we're including in the `data` folder, including what they are, why we chose them, and where they are used.

---

## Learning Objectives

After this lessons, students will be able to:

- Explain how time series data are distinct and how to account for that.
- Create rolling means and plot time series data.
- Perform autocorrelation on sample time series data.
- Decompose time series data into trend and residual components.
- Bonus: Explain the benefits and drawbacks of ARIMA as compared to other methods.

---

## Student Requirements

Before this lesson(s), students should already be able to:

- Manipulate data with Pandas.
- Create basic data visualizations with Matplotlib and Seaborn.
- Define and demonstrate techniques for correlating data points.

---

## Lesson Outline

> TOTAL (190 min)

I. **Foundations** (TODO min total)
- Part 1: Time Series Data (TODO min)
    - What is Time Series Data?
    - Examples of Time Series Data and Domains That Find it Useful
    - Trends and Seasonality
    - Preprocessing Time Series Data With Pandas
    - Processing Date Information as `datetime` Objects
    - Filtering by Date With Pandas
    - Differencing/Lagging
- Practice (TODO min)
- Part 2: Rolling Means and Plotting Time Series Data (TODO min)
    - What is a Trend?
    - Visualizing Trends
    - Computing Aggregates With Pandas' `.resample()` Function
    - Computing Rolling Averages With Pandas
    - Other Pandas Window Functions (Rolling Sum, Rolling Max, Diff)
    - Exponentially Weighted Windows
    - Plotting Time Series Data
- Practice (TODO min)
- Part 3: Autocorrelation on Time Series Data (TODO min)
    - Define Autocorrelation 
    - Examples of Autocorrelation
    - Computing Autocorrelation
    - Using the Pandas `autocorr()` Function 
    - Calculating and Plotting ACF and PACF Using StatsModels
- Part 4: Decomposing Time Series (TODO min)
    - Decomposing Time Series Into Trend, Seasonality, Cyclical, and Residual Components
    - Using the `.seasonal_decompose()` Function
    - Plotting the Seasonal, Trend, and Residual Components of a Time Series
- Closing and Recap (TODO min)
   
    
II. **Bonus** (TODO min)
- Time Series Forecasting Models (15 min)
    - What are Time Series Models?
    - Properties of Time Series Models
    - Assumption of Stationarity
    - Compare/Contrast Time Series Forecasting Models
- Closing and Recap (TODO min)

---


## Additional Resources

If you are interested in more resources, check out the following:
- In Pandas' `datetime` library, [search for more information on `.dt` here](http://pandas.pydata.org/pandas-docs/stable/api.html).
- For additional review of these concepts, see [some inspiration from the Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/03.11-working-with-time-series.html).
- There are lots of additional tutorials on ARIMA models out there; [here is a good one](http://www.statsref.com/HTML/index.html?arima.html).
