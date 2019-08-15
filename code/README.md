# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

## Problem Statement

The new format for the SAT was released in March 2016. New SAT <br>
a. combines the reading and writing sections and made up half total score (before was 2/3 of total score), <br>
b. no penalty for incorrect answer <br>
c. students are more well-informed about the different parts to be tested in the exam <br>

Despite the change, the participation rate of SAT is lower compared ACT. We would like to find out :<br>
a. the possible impact due to the change of SAT format<br>
b. what could College Board do to get the most utility out of finite resources

## Executive Summary

We are experiencing a considerable low participation rate for SAT in Kansas state. We will analyse the data collected for SAT and ACT for year 2017 and 2018 and find out possible solution to increase the SAT participation rate.

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

### Data dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|object|ACT & SAT|The name of state in United States|
|**act2017_participation(%)**|integer|ACT|Percentage of high school students taking ACT|
|**act2017_english**|float|ACT|The score for English section in ACT|
|**act2017_math**|float|ACT|The score for Mathematics section in ACT|
|**act2017_reading**|float|ACT|The score for Reading section in ACT|
|**act2017_science**|float|ACT|The score for Science section in ACT|
|**act2017_composite**|float|ACT|The average of English, Math, Reading and Science section scores|
|**sat2017_participation(%)**|integer|SAT|Percentage of high school students taking SAT|
|**sat2017_erw**|integer|SAT|Total score for Essay, Reading and Writing(ERW) section in SAT|
|**sat2017_math**|integer|SAT|The score for Mathematics section in SAT|
|**sat2017_total**|integer|SAT|The summation of score for Mathematic and ERW section in SAT|

## Conclusions
1. SAT participation rate is affected by ACT participation rate. <br>
2. College board need to convince the students that those do well in ACT could do the same in SAT. <br>
3. More data is needed to evaluate the impact of new SAT format. In future, if College board can show that the number of states score higher than the national average in SAT has improved, this could be an attraction point.<br>

## Recommendations
1. Since the new format was launched recently, there will not be enough past year paper for reference. College board can provide more sample test for students increase their confidence level in taking SAT. Then, College Board can conduct some seminars and let the teachers be informed about their focus in the new SAT.

2. The participation rate is strongly affected by individual state decision. College Board can work together with states by giving free test for students from family with lower income.
3. Number of participants and geographical data could help in the investigations, so it would be better to include the data in the future research.
