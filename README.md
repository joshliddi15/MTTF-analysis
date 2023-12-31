# MTTF-analysis Overview

This project was intended to explore the abilities of various python packages to analyze sales and return data to identify trends which may be indicative of problems in a manufacturing environment. This type of analysis generates useful and actionable data which can direct decision making. Data for the project is randomly generated by the program prior to analysis of the data. Sample size can be easily changed by adjusting the call to generate sales records.

[Software Demo Video](https://youtu.be/gTDiXkL_G5w)

# Data Analysis Results

With this analysis I wanted to determine whether a certain subset of returns within a population was different enough from the entire population to indicate statistical significance which would warrant investigation or correction to the manufacturing process. Aggregating the data by the date of manufacture provides a clear path of traceability back to the original manufacture date, so trends caused by process errors or defective components could be identified and addressed.

# Development Environment

* Pandas was used to hold the sales and returns data in a dataframe.
* MatPlotLib was used to generate the graphs which are displayed to the user.
* Scipy was used to perform the t-test which checks for significance between the highest return rate and the main population.

# Useful Websites

* [MatPlotLib](https://matplotlib.org/)
* [Pandas](https://pandas.pydata.org/docs/getting_started/index.html)

# Future Work

* Improve data generation
* Modify T-Test to aggregate data by month after the calculation rather than before.
* Add indexes to the returns and sales data, then connect sales to returns based on those indexes to simulate a more serialized type of product and a more traditional ERP or CRM system.
