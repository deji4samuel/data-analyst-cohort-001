# Week 6

[← Back to journal index](index.md)

## Lessons — 3/4 complete

| Lesson | Status | Tasks done | Updated |
| --- | --- | --- | --- |
| Learn: Normal distribution, z-scores, probability, and the 68-95-99.7 rule | Complete | 7 | 08 Sept 2026, 09:49 |
| Practice: Normal distribution, z-scores, probability, and the 68-95-99.7 rule | Complete | 5 | 11 Sept 2026, 10:21 |
| Clean and validate: Normal distribution, z-scores, probability, and the 68-95-99.7 rule | Complete | 5 | 11 Sept 2026, 11:52 |
| Analyze: Normal distribution, z-scores, probability, and the 68-95-99.7 rule | In progress | 5 | 11 Sept 2026, 12:54 |

### Learn: Normal distribution, z-scores, probability, and the 68-95-99.7 rule

**What I did**

- **Built:** I setup a workbook for the project and created RawData Sheet, Working Sheet and Notes Sheet
- **Note:** The data from raw data sheet was copied into working sheet and converted to a named Table
- **Built:** I created a named cell for the vaues of Mean, Standard Deviation and the Threshold.
- **Applied:** NORM.DIST() method was used to find the probability that package will fail
- **Applied:** I used formula (value - mean)/SD for callculate the Z-Score
- **Built:** I added Quaity Control column so as to flag the batches that woudl be rejected
- **Applied:** NORM.INV() method was used to find the value give the probabiity that package woud fail
- **Applied:** I used histogram chart to plot the weigth distribution so as to visualise the curve and observe the spread

**To explore further**

- [x] Read about NORM.DIST() method
- [x] Read about NORM.INV() method

### Practice: Normal distribution, z-scores, probability, and the 68-95-99.7 rule

**What I did**

- **Applied:** Given the value of mean and SD, I used NORM.DIST() method to caculate and discovered that 4% of the loan applicants would be automatically declined
- **Applied:** I used the Z-score formula to compare diferent data point so as to know how far they are from center

### Clean and validate: Normal distribution, z-scores, probability, and the 68-95-99.7 rule

**What I did**

- **Applied:** Z score formula was used to calculate and discover if the given values are within the expected value

### Analyze: Normal distribution, z-scores, probability, and the 68-95-99.7 rule

**What I did**

- **Applied:** Z scoore formula `(value - mean)/SD` was used to discover how far is the average sales order of the flash day sales from normal day
- **Applied:** `=1 - NORM.DIST(68, 47, 12, TRUE)` was used to discovered that only 4% of normal day average order value could achieve such order value
- **Applied:** `NORM.INV(x%, 47, 12)` was used to define the average sales order expected from different percentile.
