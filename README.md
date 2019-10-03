# Eploratory_Data_Analysis

Before we build our machine learning models on a dataset, we need to be familiar with our data. We need to have an intuition on how to interpret the results of the models. Exploratory data analysis, or EDA, is a crucial part of Data Science process. 

Some of the most important/interesting business insights come not from machine learning models, but from exploring the distribution of our data. We can utilize descriptive analytics to gain valuable company insight--think about questions like "who is my most profitable customer segment?" or "is there a seasonality to our customer churn rate?". The ability to ask good questions and basic visualizations, sometimes will get the job done vs. using machine learning models. 

Understanding your data distribution can be done in a few different ways. Generally, we'll use high-level descriptive statistics, followed by visualizations. It's common to find interesting things in the data that leads to further questions for investigation. 

Using pandas `.describe()` method, you'll be able to easily extract the count, mean, median, min, max, and quartile values for every column in the DataFrame. It's useful for answering questions like "how much variance can I expect in column x?" (i.e. how far is column x from the dataset mean?) 

## Visualizing Distributions - Histograms 
The simplest way to understand the distribution of a dataset is to visualize it. Pandas has an built-in `.hist()` method. 

## Visualizing Distributions - Kernel Density Estimation (KDE) plots
KDE plot is a non-parametric way of estimating the probability density function (PDF) of a random variable. It's normally overlaid with a histogram to create a line that visualizes the probability mass for each value in the histogram.

## Joint Plots
The joint plot allows us to visualize a scatter plot of two different columns, a KDE plot, and a simple linear regression line. We can use the seaborn library to create them. `sns.jointplot()`

## Interpreting Our EDA
The goal of EDA is not pretty visualizations, but insight to our data! Use visualization as a tool, not a goal. The goal is to ask good questions and see if you can answer it by exploring the dataset. 
