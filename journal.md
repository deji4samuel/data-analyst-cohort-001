# Data Analyst Job-Ready Learning Journal

> Last updated: 2 July 2026

---

## Day 1 — Visualize: Workbook setup, tables, sorting, filtering, and named ranges

**Phase:** Excel

### What I Did

- **Built:** I created a line chart using the data supplied with one of the variables (A&E) to reflect the trend of customers waiting times over the period of six (6) months, by highlighting the months row and A&E rows and select INSERT from the menu bar and then select line chart from the charts options
- **Built:** I added additional line by RIGHT clicking on the chart and Select Data Source and then click. '+' sign under Legend entries (series) to add additional line. I also selected the series I wanted to add by writing the formula =Hosp!$B$5:$G$5 into the Y values
- **Explained:** To change the chart title, I double clicked on the Title of the chart so as to edit it.
- **Verified:** I formatted the chart legend by RIGHT clicking on the chart and Select Data Source and then edit the chart legend under Legend entries (series).
- **Reflected:** I explore other chart by right clicking the chart and selected change chart type, and I selected Colums from the options
- **Built:** I created a named range for all the rows involved and used them in the Line Chart by RIGHT clicking on the chart and Select Data Source and then click. '+' sign under Legend entries (series) to add additional line.I then added new line using named range by writing the formula =Hosp!AandE (note that AandE is a named range) into the Y values

### To Explore Further

- [x] Adding additional line to the same chart
- [x] Changing the chart title
- [x] Formatting the chart legend
- [x] Making use of the named range in the chart

### My Practice Work

---
<!-- framework:solve -->

## Visualize: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-07-02 | **Method:** SOLVE

> **Scenario:** Sector: Healthcare
> 
> Scenario: A hospital operations manager needs to present A&E waiting-time performance to the board. The board has 90 seconds per slide. Your chart must communicate the trend immediately — no table, no explanation needed, just the visual.

### S — Split the problem
- A&E waiting-time performance.
Line chart showing the trend.
Clear legend and labelling to communicate vital information

- The chart must communicate the trend immediately

- Other sheets such as 'Raw Data,' 'Tracking,' and 'Charts' were created for clear distinction and traceability.

### O — Observe the data
- Rows and columns

- Line chart

- Unreadable labels, unclear chart title

### V — Verify your logic
- A line chart was used to show the trend over a period of 6 months

- Using of Line with makers made it possible to confirm the data at each point

- Wrong chart type and unclear title, label or legend.

### E — Evolve the solution
- Label and colour

- Clear labelling and title

- Final output of the chart


---
<!-- framework:five-how -->

## Visualize: Workbook setup, tables, sorting, filtering, and named ranges
**Completed:** 2026-07-02 | **Method:** 5-HOW

> **Scenario:** Sector: Healthcare
> 
> Scenario: A hospital operations manager needs to present A&E waiting-time performance to the board. The board has 90 seconds per slide. Your chart must communicate the trend immediately — no table, no explanation needed, just the visual.

### Write it — code the solution
- I created a new workbook with 3 empty sheets named 'Raw Data,' 'Tracker,' and 'Charts.'
I copied the raw data from source into the Raw Data Sheet and then duplicated it into the Tracker sheet
I made the data in the tracker sheet a named table call HosTable
I highlighted the column/range I wanted to add to the line chart and I clicked insert menu and then picked line chart 
While the chart was active, I clicked on the Chart Design menu and also clicked the dropdown on 'Add Chart Element,' where I changed the chart title and added the label 'Minutes' to the Y-axis as instructed in the exercise.

- No formula is required for this exercise

- A&E range, i.e., cell B2 to G2

### Explain it — pseudocode
1. Start with HospTable
2. Selected the A&E row and make it a named range called AandE
3. I also selected the Month row and make it a named range called Months
4. I selected the line chart to make a line chart
5. I selected the Cardiology row and make it a named range called CardList
6. I added the line chart for cardiology by right-clicking on the chart and select 'Select Data,' where I added the CardList into the series
7. I then clicked Ok and the extra line chart was added

### Use it — job story
**My role:** Junior Data Analyst

**The problem:** Create a chart that shows the trend and can be understood in 10 seconds.

I make use of the named range created to populate the chart. I ensured the chart has a clear title, and also both axes and the series were well labeled. I ensure the colour of each line is distinct from each other.

### See it — expected output
- The sperad sheet consist of 4 rows and 6 colums. The columns represent each month under observation while each row is the record of waiting-time for each department in the hospital.  There are no missing data and no duplicates.

- The result shows the waiting time along each month in the form of a trend.

### Try it — Scenario 1
> Finance has an Orders spreadsheet and wants to know: "What's the total sales value for the Electronics category only?"
> 
> Write a SUMIF formula that sums `order_value` where `product_category` equals "Electronics".

- I created a line chart using the data supplied with one of the variables (A&E) to reflect the trend of customers waiting times over the period of six (6) months, by highlighting the months row and A&E rows and select INSERT from the menu bar and then select line chart from the charts options
I added additional line by RIGHT clicking on the chart and Select Data Source and then click. '+' sign under Legend entries (series) to add additional line. I also selected the series I wanted to add by writing the formula =Hosp!$B$5:$G$5 into the Y values
To change the chart title, I double clicked on the Title of the chart so as to edit it.
I formatted the chart legend by RIGHT clicking on the chart and Select Data Source and then edit the chart legend under Legend entries (series).

- No formula was involved

---
