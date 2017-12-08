# GENDER INCOME GAPS IN THE UNITED STATES

## SEMESTER AND CLASS TITLE

Fall 2017, DATA 550 Data Visualization - Dr. Bora Pajo

## DESCRIPTION AND CONTEXT

The gender pay gap in the United States is the ratio of female-to-male median yearly earnings among full-time, year-round workers. While many believe that the gender gap is overstated in the United States. This analysis attempts to show if the gender gap does exist accross various industries. The extent to which discrimination plays a role in explaining gender wage disparities is somewhat difficult to quantify, due to a number of potentially confounding variables. 

A 2010 research review by the majority staff of the United States Congress Joint Economic Committee reported that studies have consistently found unexplained pay differences even after controlling for measurable factors that are assumed to influence earnings – suggestive of unknown/unmeasurable contributing factors of which gender discrimination may be one.[7] Other studies have found direct evidence of discrimination – for example, more jobs went to women when the applicant's sex was unknown during the hiring process.

Analysis thus far has found that there is indeed a sizable gender gap between male and female incomes.

![GitHub Logo](US_Gender_pay_gap_by_state.png)

Figure: Women's earnings as a percentage of men's earnings, by state and Puerto Rico, 2007. Data from the Income, Earnings, and Poverty Data From the 2007 American Community Survey.

Source: US Census Bureau

## ABOUT THE DATA

This dataset, retrieved from the Bureau of Labor Statistics, shows the median weekly incomes for 535 different occupations. The data encompasses information for all working American citizens as of January 2015. The incomes are broken into male and female statistics, preceded by the total median income when including both genders. The data has been re-formatted from the original PDF-friendly arrangement to make it easier to clean and analyze.


Using pandas, numpy, seaborn, and matplotlib 
Created bar chart, pie chart, boxplot, strip plot, violin plot, and kdeplot 

## DATA SOURCE 

Bureau of Labor Statistics - https://www.bls.gov/

The Bureau of Labor Statistics (BLS) is a Federal government agency and everything published, both in hard copy and electronically, is in the public domain, except for previously copyrighted photographs and illustrations. 

This dataset has been converted to CSV

## AUTHOR'S NAME AND CONTACT

Oddinigwe Onyemenem - oddinigwe@gmail.com




## CONTENT

### Fields in the dataset:

Median weekly earnings of full-time wage and salary workers by detailed occupation and sex.

Occupation: Job title as given from BLS. Industry summaries are given in ALL CAPS.

All_workers: Number of workers male and female, in thousands.

All_weekly: Median weekly income including male and female workers, in USD.

M_workers: Number of male workers, in thousands.

M_weekly: Median weekly income for male workers, in USD.

F_workers: Number of female workers, in thousands.

F_weekly: Median weekly income for female workers, in USD.

## INPUTS AND OUTPUTS

```
#to enable visualizations 
%matplotlib inline

# First, import pandas, a useful data analysis tool especially when working with labeled data
import pandas as pd

# import seaborn, visualization library in python 
import warnings # current version of seaborn generates a bunch of warnings that we'll ignore
warnings.filterwarnings("ignore")
import seaborn as sns
import matplotlib.pyplot as plt
sns.set(style="white", color_codes=True)

# Next, we'll load the cereal dataset, which is in the specified directory below
cereal = pd.read_csv("C:\\Users\\oddin\\Documents\\projects\\project2\\cereal.csv")


```

