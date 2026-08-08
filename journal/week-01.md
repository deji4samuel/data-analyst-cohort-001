# Week 1

[← Back to journal index](index.md)

## Lessons — 14/14 complete

| Lesson | Status | Tasks done | Updated |
| --- | --- | --- | --- |
| Set up your data analyst portfolio | Complete | 10 | 25 Jun 2026, 21:16 |
| Learn: Workbook setup, tables, sorting, filtering, and named ranges | Complete | 9 | 25 Jun 2026, 21:34 |
| Practice: Workbook setup, tables, sorting, filtering, and named ranges | Complete | 4 | 26 Jun 2026, 23:38 |
| Clean and validate: Workbook setup, tables, sorting, filtering, and named ranges | Complete | 4 | 27 Jun 2026, 21:18 |
| Analyze: Workbook setup, tables, sorting, filtering, and named ranges | Complete | 4 | 27 Jun 2026, 22:20 |
| Visualize: Workbook setup, tables, sorting, filtering, and named ranges | Complete | 4 | 02 Jul 2026, 15:22 |
| Portfolio proof: Workbook setup, tables, sorting, filtering, and named ranges | Complete | 4 | 04 Jul 2026, 00:16 |
| Review: Workbook setup, tables, sorting, filtering, and named ranges | Complete | 4 | 04 Jul 2026, 00:47 |
| Practice: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP | Complete | 5 | 11 Jul 2026, 16:24 |
| Clean and validate: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP | Complete | 5 | 13 Jul 2026, 14:40 |
| Analyze: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP | Complete | 5 | 13 Jul 2026, 20:55 |
| Visualize: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP | Complete | 5 | 16 Jul 2026, 06:43 |
| Portfolio proof: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP | Complete | 5 | 22 Jul 2026, 15:09 |
| Review: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP | Complete | 5 | 17 Jul 2026, 01:41 |

### Set up your data analyst portfolio

**What I did**

- **Explained:** I have learned how to create a repo on GitHub and invite collaborators.
- **Note:** I installed VS Code on my local laptop
- **Note:** I cloned the GitHub repo with my local workspace via VS code
- **Note:** I was able to create a local settings file named ".env.development."
- **Built:** I created required folders in the application base folder on my laptop
- **Built:** Added .gitignore into the development environment
- **Note:** I downloaded Python and intall it in the development environment
- **Note:** I downloaded other required libraries like pandas, numpy and matplotlib

**To explore further**

- [x] VS Code installation
- [x] Creating local environment development setting file
- [x] Cloning GitHub repo with VS Code
- [x] Install Python
- [ ] Install Jupyter notebook
- [ ] Install SQL

### Learn: Workbook setup, tables, sorting, filtering, and named ranges

**What I did**

- **Note:** I understand that raw data has to be kept intact and not edited. In other words, duplicate the raw data and work with the copied version
- **Built:** I created an extra sheet so as to be documenting the insights I got I was filtering and sorting the data

### Practice: Workbook setup, tables, sorting, filtering, and named ranges

**What I did**

- **Note:** I set up Excel Workbook
- **Note:** I converted Excel Spreadsheet into a Table and make it a named Table
- **Note:** I sort the data in the Table
- **Note:** I filter the data as required
- **Note:** I make use of a named range on a column and calculated its total sum
- **Note:** I save the file with the required insight for further action
- **Note:** I make use of some excel formula such as SUM to complete the task

**To explore further**

- [x] Filter in Exce Table
- [x] Sort in Excel Table
- [x] Create a named range on columns
- [x] Summarising the findings

**Practice work**

---
<!-- framework:solve -->

### Clean and validate: Workbook setup, tables, sorting, filtering, and named ranges

**What I did**

- **Note:** I inspect the data and remove the duplicates
- **Applied:** I used =PROPER(text) to capitalise all the the first letters of the names
- **Note:** I standardise Date column with format on MS excel
- **Note:** I cleaned the leading and trailing spaces with the use of =TRIM(text) function in MS Excel
- **Note:** I flagged the mandatory value that was missing to the HR unit
- **Note:** I flagged the impossible values (negative salary) to the HR

**To explore further**

- [x] Standardize Date Column
- [x] Cleaning of leading and trailing spaces
- [x] Discovering the impossible values

### Analyze: Workbook setup, tables, sorting, filtering, and named ranges

**What I did**

- **Note:** I converted Excel Spreadsheet into a Table and make it a named Table
- **Note:** I sort the data in the Table with Value column to determine the Hub that has highest order value
- **Note:** I then filter the Table with the insight I got from earlier sort operation to get all the  transaction that happened in each hub
- **Note:** I make use of =SUMIF() function to calculate the total order value in the hub so as to discover the hub that generated the highest order value.
- **Applied:** I make use of =COUNTIF() to find the number of the orders which has "Delivered" as their Status, I also used COUNTA() to get the total number of Status and then divide then output of COUNTIF() by the output of COUNTA() so as to calculate the percentage of deliveries that were on time.
- **Note:** I make use of =AVERAGEIF() function to find the average of the order value if the customer type is B2B or B2C
- **Applied:** Making note of every change applied to a workbook is very important as it will help in case there would be need to trace back

**To explore further**

- [x] Excel Formulas
- [x] Excel Functions - SUMIF()
- [x] Excel Functions - COUNT(), COUNTA(), and COUNTIF()
- [x] Excel Functions - AVERAGEIF()

### Visualize: Workbook setup, tables, sorting, filtering, and named ranges

**What I did**

- **Built:** I created a line chart using the data supplied with one of the variables (A&E) to reflect the trend of customers waiting times over the period of six (6) months, by highlighting the months row and A&E rows and select INSERT from the menu bar and then select line chart from the charts options
- **Built:** I added additional line by RIGHT clicking on the chart and Select Data Source and then click. '+' sign under Legend entries (series) to add additional line. I also selected the series I wanted to add by writing the formula =Hosp!$B$5:$G$5 into the Y values
- **Note:** To change the chart title, I double clicked on the Title of the chart so as to edit it.
- **Note:** I formatted the chart legend by RIGHT clicking on the chart and Select Data Source and then edit the chart legend under Legend entries (series).
- **Note:** I explore other chart by right clicking the chart and selected change chart type, and I selected Colums from the options
- **Built:** I created a named range for all the rows involved and used them in the Line Chart by RIGHT clicking on the chart and Select Data Source and then click. '+' sign under Legend entries (series) to add additional line.I then added new line using named range by writing the formula =Hosp!AandE (note that AandE is a named range) into the Y values
- **Built:** I wrote the summary of the chart showing that the A&E has the highest waiting time by this has been declining over the monthfor the the period of month being examined.

**To explore further**

- [x] Adding additional line to the same chart
- [x] Changing the chart title
- [x] Formatting the chart legend
- [x] Making use of the named range in the chart

**Practice work**

---
<!-- framework:solve -->

### Portfolio proof: Workbook setup, tables, sorting, filtering, and named ranges

**What I did**

- **Explained:** I have learned how to create a repo on GitHub and invite collaborators.
- **Explained:** I have learned how to clone a repo with VS Code using git clone command
- **Note:** I converted Excel Spreadsheet into a Table and make it a named Table
- **Note:** I sort the data in the Table
- **Note:** I filter the data as required
- **Note:** I make use of a named range on a column and calculated its total sum
- **Note:** I inspect the data and remove the duplicates
- **Applied:** I used `=PROPER(text)` to capitalise all the the first letters of the names
- **Note:** I standardise Date column with format on MS excel
- **Note:** I cleaned the leading and trailing spaces with the application of `=TRIM(text)` function in MS Excel
- **Applied:** I used `=SUMIF()` function to calculate the total order value in the hub so as to discover the hub that generated the highest order value.
- **Applied:** I make use of `=COUNTIF()` to find the number of the orders which has "Delivered" as their Status, I also used COUNTA() to get the total number of Status and then divide then output of `COUNTIF()` by the output of `COUNTA()` so as to calculate the percentage of deliveries that were on time.

**Practice work**

---
<!-- framework:solve -->

### Review: Workbook setup, tables, sorting, filtering, and named ranges

**What I did**

- **Note:** I was able to understand that setting up and excel workbook is the basis of analysing data with Excel.
- **Note:** I learnt that making use of different sheet for Raw Data support traceability and protect the original data
- **Note:** I learnt that making use of named Table make referencing easier and both sorting and filter are straight forward
- **Applied:** I learnt that making use of named range make referencing easier as excel formula and functions can be applied directly on the named range.

**To explore further**

- [ ] Mastering documentation

### Practice: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

**What I did**

- **Note:** I setup a workbook for the project
- **Built:** I created GradeData and StudentContacts sheet as instructed
- **Note:** I converted Excel Spreadsheet into a Table and make it a named Table in a separate sheet so as to work on the data accordingly
- **Note:** I make use of AVERAGE() function to calculate the average score of each students in the table
- **Note:** I make use of IFS() function instead of nested IF() to assign grade letters to the each student
- **Applied:** I used COUNTIFS() function to count the number of students that score more than overall average in all 3 courses
- **Applied:** I used XLOOKUP() function to add the email of the students from another table in another sheet.

**To explore further**

- [x] Apply AVERAGE Function
- [x] Apply IFS function
- [x] Apply COUNTIFS function
- [x] Apply XLOOKUP function

### Clean and validate: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

**What I did**

- **Built:** I set up the work book and created sheets for Raw Data, Price Tracking and Notes
- **Note:** I inspect the data to check for the duplicates and missing values
- **Note:** The price for item PC002 was changed to 0 instead fo FREE, being a promotional item
- **Note:** I repalce the emopty price column with 0 and flag it to the sales team so they can review it.
- **Applied:** I used IFERROR function to trap all any attempt to divide by zeroo in the in the revenue formula column
- **Note:** I repalce the NONE value in the dicount column with zero, being that there is no discount on that item
- **Built:** I created the FinalPrice formula with IFERROR() function
- **Note:** I add the QualityFlag Column to track the comleteness of the data quaulity check where I make use of IF OR statement so as to pass all the condition that should be fulfilled.

**To explore further**

- [x] IF Function
- [x] IF OR function
- [x] IFERROR Function

### Analyze: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

**What I did**

- **Built:** I setup a workbook for this exercise and created different sheet for RawData, PropertyData and Notes
- **Note:** I Converted the dataset into an excel table for easy manipulation
- **Note:** I sort the table to determine the table to determine the properties overasking prices
- **Note:** I make use of AVERAGEIFS() to calculate the averages of based on multiple condition
- **Applied:** I used SUMIFS() to calculate the total sum based on some conditions
- **Note:** I make use of COUNTIFS to count the number of values based on some conditions
- **Note:** I make us of IFERROR to trap the violation of mathematical and arithimetic operations
- **Note:** I make use of XLOOKUP to search for a value in an array and return required values

**To explore further**

- [x] Use AVERAGEIFS
- [x] Use XLOOKUP
- [x] Use COUNTIFS
- [x] Use SUMIFS
- [x] Use IFERROR
- [x] Use Sort on the table

### Visualize: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

**What I did**

- **Note:** I set up a workbook with different sheets including Rawdata, Tracking and notes.
- **Explained:** I crated a visualization by highlighting the cells and inserting a clustered bar chart to compare the two variables in question.
- **Built:** I added the chart title to give my audience an expectation of what to see
- **Note:** I learnt the use of RAG in designing a dashboard

**To explore further**

- [ ] Formatting Data point
- [ ] Signling out a bar for attention

### Portfolio proof: Formulas: SUM, AVERAGE, COUNTIFS, nested IF, VLOOKUP, and XLOOKUP

**What I did**

- **Note:** I practiced the use of Nested IF on tables to gain more understanding
- **Built:** I created a dashboard that compare the actual and target sales of different Line products using the MS Excel bar chart across the 5 different products.
- **Note:** I make use of helper column to calculate teporary vaues required to update my table and charts.
- **Applied:** I used COUNTIF function to find the number of properties that were solde above the list price
- **Applied:** I used XLOOKUP to assign agent email to each agent name
- **Applied:** I used AVERAGEIFS to calculate the property of type 'Fllat' and of type 'House' seperately
- **Note:** I make use of the combination of IFERROR and COUNTIFS to calculate the AgentSalesRatio for each agent.

**To explore further**

- [x] Study about AVERAGEIFS

**Practice work**

---
<!-- framework:solve -->
