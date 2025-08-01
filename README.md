# Data-Analyst-2
This repository contains the following projects:

1. "project8.ipynb"

2. "project9.ipynb"

3. "project10.ipynb"

🛠️**Libraries used**: Pandas, NumPy, Matplotlib, SciPy, Seaborn.

## 1. "Project 8"
This project analyzes the information of trips (trips amount,company name, date of starting and ending trips) performed by a taxi service. The information is in 3 different datasets. Visualizations and hypotheses tests are performed.

**Objective:** To clean data and create data (from the cleaned one) to perform hypotheses tests (**Levene** and **T tests**) to make decisive decisions.

### Steps
First, the exploratory data analysis (EDA) is performed to show the data in the non-cleaned datasets. Second, the data preprocessing is made, which consist of filling null values, dropping duplicates, verifying if data format is correct and processing the outliers. Third, to create data from the previously cleaned one. Fourth, the formal Levene and T tests are performed to determine if the following hypothesis is true:

• Average trip duration in raining saturdays != Average trip duration in non-raining saturdays.

Finally, some decisive conclusions are given.

## 2. "Project 9"
This project analyzes the information of 360000 clients about their visits and buys in a web site.

**Objective:** To make the Return On Marketing Investment (**ROMI**) analysis to determine how much revenue a marketing campaign is generating compared to the cost of running that campaign.

### Steps
First, the exploratory data analysis (EDA) is performed to show the data in the non-cleaned datasets. Second, the data preprocessing is made, which consist of filling null values, dropping duplicates, verifying if data format is correct and processing the outliers. Third, to create data from the previously cleaned one. Fourth, the Lifetime Value (**LTV**), the Client Acquisition Cost (**CAC**) and the **ROMI** analysis are made.

The Lifetime Value to Cost of Acquisition (LTV/CAC) Ratio tells if the theoretical lifetime revenue you get from a customer is higher or lower than the sales and marketing costs needed to acquire that customer.

Finally, some conclusions are given.

## 3. "Project 10"
This project analyzes the results of a previously conducted **A/B test**. Visualizations, hypotheses tests and two profit analysis are performed by taking into account and without outliers in purchases.

**Objective:** To determine if there is a significant difference in the sample proportions to make decisive decisions by using the **Wilcoxon-Mann-Whitney test**.

### Steps
First, the data will be analyzed taking outliers into account, then without them to determine whether these outliers distorted the A/B test. The **Shapiro-Wilk test** is applied to determine whether the data are normally distributed, and the Wilcoxon-Mann-Whitney U test is also applied to determine whether there are significant differences between groups considering the outliers. The Wilcoxon-Mann-Whitney test is used to validate proportions in independent samples without a normal distribution. In order to avoid the "seeking-problem," the cumulative sum of profits throughout the analysis is used.

Finally, some decisive conclusions are given.
