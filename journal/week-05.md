# Week 5

[← Back to journal index](index.md)

## Lessons — 4/5 complete

| Lesson | Status | Tasks done | Updated |
| --- | --- | --- | --- |
| Learn: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | Complete | 12 | 04 Aug 2026, 23:35 |
| Practice: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | Complete | 5 | 16 Aug 2026, 00:37 |
| Clean and validate: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | Complete | 5 | 27 Aug 2026, 14:58 |
| Analyze: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | Complete | 5 | 27 Aug 2026, 15:55 |
| Visualize: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | In progress | 3 | 31 Aug 2026, 00:19 |

### Learn: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English

**What I did**

- **Built:** I setup a workbook for the project and created RawData Sheet, Working Sheet and Notes Sheet
- **Note:** The data from raw data sheet was copied into working sheet and converted to a named Table
- **Applied:** AVERAGE() function was used to calculate the mean of Patient waiting time
- **Applied:** MEDIAN() function was used to calculate the median of Patient waiting time
- **Applied:** STDEV() function was used to calculate the standard deviation of Patient waiting time
- **Applied:** QUARTILE() function was used to calculate both first quartile (Q1) and third quartile (Q3) of the data set
- **Note:** The IQR was generate by deducting Q1 from Q3
- **Note:** Lower fence was calculated with the formula Q1 - (1.5 * IQR)
- **Note:** Upper fence = Q3 + (1.5 * IQR)
- **Applied:** IFS() function was used on waiting time to flag the Outlier
- **Applied:** CORREL() function was used to calculate correlation between Staffing and patient waiting time
- **Applied:** MODE.SNGL() function was used to calculate most frequent value of acuity.
- **Note:** The distribution of the waiting time was plotted with histogram using the chart
- **Note:** The relationship between Staffing and waiting time was plotted with scatter plot in excel chart

**To explore further**

- [x] Read about MEDIAN() Function
- [x] Read about STDEV() function
- [x] Read about QUARTILE() function
- [x] Read about MODE.SNGL() function
- [x] Read about CORREL() function

### Practice: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English

**What I did**

- **Built:** I setup a workbook for the project and created RawData Sheet, Working Sheet and Notes Sheet
- **Note:** The data from raw data sheet was copied into working sheet and converted to a named Table
- **Applied:** AVERAGE() function was used to calculate the mean of Monthly Return percentage of Assets
- **Applied:** MEDIAN() function was used to calculate the median of Monthly Return percentage of Assets
- **Applied:** I used MiN() and MAX() functions to find the minimum and maximum percentage of the Monthly Return respectively.
- **Applied:** CORREL() function was used to calculate correlation between MonthlyReturn percentages and Standard Deviation percentages

### Clean and validate: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English

**What I did**

- **Built:** I setup a workbook for the project and created RawData Sheet, Working Sheet and Notes Sheet
- **Note:** The data from raw data sheet was copied into working sheet and converted to a named Table
- **Applied:** I used QUARTILE() function to calculate the Q1, Q2 and Q2 of YieldPerHa field
- **Applied:** I documented the clean records and logged the changes that was applied in the Notes Sheet of the workbook

### Analyze: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English

**What I did**

- **Built:** I setup a workbook for the project and created RawData Sheet, Working Sheet and Notes Sheet
- **Note:** The data from raw data sheet was copied into working sheet and converted to a named Table
- **Applied:** AVERAGE() function was used to calculate the mean of Maths, English and Science subjects
- **Applied:** MEDIAN() function was used to calculate the median of Maths, English and Science subjects
- **Applied:** STDEV() function was used to calculate the standard deviation of Maths, English and Science subjects
- **Applied:** CORREL() function was used to calculate correlation between Maths and Science

### Visualize: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English

**What I did**

- **Built:** I setup a workbook for the project and created RawData Sheet, Working Sheet and Notes Sheet
- **Note:** The data from raw data sheet was copied into working sheet and converted to a named Table
- **Applied:** AVERAGE() function was used to calculate the mean of Patient waiting time
- **Applied:** MEDIAN() function was used to calculate the median of TempAnomaly_C
- **Applied:** STDEV() function was used to calculate the standard deviation of TempAnomaly_C
- **Applied:** CORREL() function was used to calculate correlation between Year and TempAnomaly_C
- **Applied:** CORREL() function was used to calculate correlation between Year and CO2
- **Applied:** CORREL() function was used to calculate correlation between TempAnomaly_C and CO2
- **Applied:** I used line chart to plot the temperature rend over the years.
- **Verified:** I was able to able to add a trend line to the line chart by right-clicking the data series, selected the "Add Trendline" and I checked "Display Equation on chart" and "Display R-squared value on chart"
- **Applied:** I used scatter port to plot the temperature against the CO2
- **Built:** I added a trend line to the scatter plot by right-clicking the data series, selected the "Add Trendline".

## Daily Concept Clinic

### Statistics 2: Relationship - scatter plot and correlation

_2026-08-07 · logged 2026-08-08 23:02 UTC_

- **Clinic topic:** Statistics 2: Relationship - scatter plot and correlation
- **What was taught:** Introduction to scatter plot and correlation. There would be a possible driver that would influence the related outcome. For instance, an increase in tree age could be the driver of the increase in the size of the tree trunk. Each row of the dataset would denote one point.
Furthermore, correlation is being interpreted using two words, which are direction and strength.
- **What you now understand:** The possible driver is represented on X-axis while the outcome is represented on Y-axis. Also, I now understand the distinct difference between scatter plot and a correlation, which is that correlation coulld only be represented in the form of ranges between -1, 0 and 1. While the negative/positive represents the direction, the closeness of the the correlation outcome to 1 determines how strong the data are correlated
