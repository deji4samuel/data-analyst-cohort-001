# Week 3

[← Back to journal index](index.md)

## Lessons — 7/7 complete

| Lesson | Status | Tasks done | Updated |
| --- | --- | --- | --- |
| Learn: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 12 | 22 Jul 2026, 16:34 |
| Practice: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 5 | 22 Jul 2026, 18:55 |
| Clean and validate: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 5 | 24 Jul 2026, 13:18 |
| Analyze: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 5 | 24 Jul 2026, 15:32 |
| Visualize: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 5 | 24 Jul 2026, 17:53 |
| Portfolio proof: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 5 | 27 Jul 2026, 00:37 |
| Review: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules | Complete | 5 | 27 Jul 2026, 00:39 |

### Learn: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

**What I did**

- **Note:** I setup a workbook for the project
- **Built:** I created RawData sheet sheet as instructed
- **Built:** I created CleanedCustomer sheet where I apply all the formula references
- **Built:** I created Notes sheet where I log all the changes and record the flag row/column
- **Applied:** I used TRIM and PROPER function to clean the text off leading and trailing spaces, and then standardised the texts
- **Note:** I corrected all the uneven date formatting and make all dates to be in short date format

**To explore further**

- [x] Read about TRIM Function
- [x] Apply PROPER Function

### Practice: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

**What I did**

- **Note:** I setup a workbook for the project
- **Built:** I created RawData sheet sheet
- **Built:** I created CleanDonoorsheet sheet where I apply all the formula references
- **Built:** I created Notes sheet where I log all the changes and record the flag row/column
- **Applied:** I used TRIM and PROPER function to clean the name column off leading and trailing spaces, and then standardised the texts
- **Applied:** I used TRIM and LOWER function to clean the email address column off leading and trailing spaces, and then standardised the texts
- **Note:** I corrected all the uneven date formatting and make all dates to be in short date format
- **Applied:** I used SUBSTITUTE in conjunction with VALUE function to remove the currency sign in from the Amount value for ease of calculation.
- **Applied:** I used COUNTIF to flag the records with duplicate Donor ID

**To explore further**

- [x] Explore LIMIT function
- [x] Further make use of TRIM and PROPER function
- [x] Study SUBSTITUTE Function
- [x] Study VALUE Function

### Clean and validate: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

**What I did**

- **Note:** I setup a workbook for the project
- **Built:** I created RawData sheet and Tracker sheet to carry out the calculations
- **Applied:** I used IF() function to identify the PolicyIDs that are not well formatted
- **Applied:** I used IF() function to confirm the logical posibbilities of claim date greater than settlement date
- **Applied:** I used IF() function to identify the missing value under ClaimAmount
- **Applied:** I used IF() function to note the invalid dates in the ClaimDate

### Analyze: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

**What I did**

- **Note:** I setup a workbook for the project
- **Built:** I created RawData sheet sheet
- **Applied:** I used of SUM() function to find the total billed amount
- **Applied:** I used of SUM() function to find the total collected amount
- **Built:** I created an helper column to calculate the collection rate in percentage
- **Applied:** I used the INDEX() Function to with both MATCH() and MIN() functions to find theh area that needs the recovery plan

**To explore further**

- [x] Study the usage INDEX() Function

### Visualize: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

**What I did**

- **Note:** I setup a workbook for the project
- **Built:** I created RawData sheet and Tracker sheet for calculation and Notes sheet for taking notes.
- **Applied:** I used IFS() function to apply multiple condition in other to know if a route exceeded the target, met target, near target or absolutely below the target
- **Built:** I created a clustered bar chart to rvisualize the data and understand what is there at one glance
- **Built:** I added a an horizontal reference line to the chart so as to display the target expectation

### Portfolio proof: Cleaning data: duplicates, TRIM/PROPER, text-to-columns, date formats, and validation rules

**What I did**

- **Applied:** This week, I used COUNTIF() function to discover the duplicates in the Donor dataset
- **Applied:** I used IF() function to discover the invalid data in insurance policy dataset
- **Applied:** I used ISNUMBER() to vallidate the value of date column in the insurance policy dataset
- **Applied:** I used PROPER() with TRIM() Function to standardise the names in the cutomer dataset
- **Applied:** I used PROPER() with LOWER() function to cleanup the customer email in the customer dataset
- **Note:** I plotted a Line chart displaying Target vs. Actual for each route in a transport operating company
