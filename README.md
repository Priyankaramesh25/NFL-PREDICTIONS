# NFL-PREDICTIONS

## Libraries

The libraries used include:
+ ggplot2
+ tidyverse
+ skimr
+ broom
+ Hmisc
+ readxl
+ readr
+ dplyr

## Introduction
In this project, we shall clean the 2020 nfl dataset and perform some simple Exploratory Data Analyis. At the end, we shall export the cleaned data to excel.

## Dataset
The dataset used in this analysis was the nfl 2020 dataset, containing two sheets in the workbook. 

## Data Preprocessing
In this step, we ensured that both sheets are in the right datatypes.After that, we combined the two sheets to form one dataset.
We then dealt with missing values and irrelevant columns. Columns such as date, season, neutral and playoff were irrelevant in our analysis and so, we dropped them off. Another step is that the playoff variable had too many nulls hence the reason for dropping it off.
The remaining numeric variables that had less nulls were dealt with by mean imputation.

Outliers were identified by use of boxplots, then dealt with my using IQR. 

## Data Exploration
We plotted the histogram of score2.


![image](https://github.com/Priyankaramesh25/NFL-PREDICTIONS/assets/166559405/1e3e4445-1563-417f-b92e-11eab4ad2312)


We also identified the density plots for score 1 and score 2 as follows:

![image](https://github.com/Priyankaramesh25/NFL-PREDICTIONS/assets/166559405/567b9ae7-9206-4532-8518-d3732d939285)



![image](https://github.com/Priyankaramesh25/NFL-PREDICTIONS/assets/166559405/ecd677a1-ea4f-41c9-a415-f6434dff0d47)


## Contribution
We welcome contributions from the community! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Open a Pull Request
