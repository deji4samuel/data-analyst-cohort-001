# Week 5

[← Back to journal index](index.md)

## Lessons — 0/1 complete

| Lesson | Status | Tasks done | Updated |
| --- | --- | --- | --- |
| Learn: Mean, median, mode, standard deviation, correlation, outliers, and sampling bias in plain English | In progress | 10 | 04 Aug 2026, 23:33 |

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

**To explore further**

- [x] Read about MEDIAN() Function
- [x] Read about STDEV() function
- [x] Read about QUARTILE() function
- [ ] Read about MODE.SNGL() function
- [x] Read about CORREL() function
