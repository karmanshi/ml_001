Question 2

### Create a Horizontal Bar Chart showing Billing Amount by Department.
### Requirements
* Place **Department** on Rows.
* Place **Billing Amount** on Columns.
* Sort in descending order.
* Display data labels.
* Apply an attractive color palette.

# Step 2: Locate the Required Fields In the Data pane (left side), find: 
1. Department (Dimension) 
2. Billing Amount (Measure)
# Step 3: Place Department on Rows
1. Click and hold Department. Drag it to the Rows shelf.
2. Drag Billing Amount to the Columns shelf, Tableau automatically creates a Horizontal BarChart.
# Step 4: Verify the Marks Type
On the Marks card (left side), Tableau usually selects Automatic.If it is not a bar chart:
Click the drop-down on the Marks card. Select (Bar)
# Step 6: Sort in Descending Order
# Step 7: Display Data Labels
On the Marks card, click 1. Label
2. Check the box Show Mark Labels
# Step 8: Apply an Attractive Color Palette
Different Colors for Each Department (Recommended)
Drag Department from the Data pane to Color on the Marks card.
Tableau assigns a different color to each department.
Change the Color Palette
Click Color.
Click Edit Colors...
Select a palette such as:
Tableau 10
Tableau 20
Color Blind
Blue-Green
Click Assign Palette (if available).
Click OK.
# Step 9: Format the Billing Amount (Optional)
Right-click the Billing Amount axis.
Select Format.
Under Numbers, choose:
Number (Standard), or
Currency (if your data is monetary).
# Step 10: Add a Chart Title
Edit the Existing Title (Most Common)
Step 1
After creating your line chart, look at the top of the worksheet.
You'll usually see a title like:
Sheet 1 or SUM(Billing Amount) by Visit Date

## Question 3 ### Create a Pie Chart showing Billing Contribution by Treatment. ### Requirements
* Use **Treatment** as the category. * Use **Billing Amount** as the measure. * Display percentage labels.* Show Treatment names.
# Step 2: Locate the Required Fields
In the Data pane (left side), locate: 1. Treatment (Dimension)  2. Billing Amount (Measure)
# Step 3: Change the Marks Type to Pie
 On the Marks card: Click the drop-down that says Automatic.1 Select Pie
The Marks card will now display options for a pie chart
# Step 4: Add Treatment as the Category
1. Drag Treatment from the Data pane.
2. Drop it onto Color on the Marks card.
Each treatment now has a different colored slice.
# Step 5: Add Billing Amount as the Measure
1. Drag Billing Amount. 2. Drop it onto Angle on the Marks card.
The size of each pie slice is now based on the billing amount.
# Step 6: Show Treatment Names
1. Drag Treatment again from the Data pane. 2. Drop it onto Label on the Marks card.
Now each slice displays its treatment name.
# Step 7: Display Billing Amount (Optional) If you also want to display the billing amount:
1. Drag Billing Amount to Label on the Marks card.
Now the labels show percentages instead of the actual billing amounts.
# Step 8: Display Percentage Labels
Step 8.1
On the Marks card: 1. Click Label.
Step 8.2 On the Label shelf, click the small ▼ beside SUM(Billing Amount).
Choose :- Quick Table Calculation -> select (Percent of Total) 
# Step 9: Format Percentage 1. Right-click SUM(Billing Amount) on the Label shelf.
2. Select :- Format
3. Under Numbers, choose :- Percentage :- Set the decimal places (for example, 1 or 2).
# Step 10: Increase Pie Size
# Step 11: Apply an Attractive Color Palette
1. Click :- Color
2. Click :- Edit Colors...
3. Choose a palette such as:
    Tableau 10
    Tableau 20
    Color Blind
    Blue-Green
4. Click :-Assign Palette 5.Click OK.
# Step 12: Show Label if Hidden
# Step 13: Add a Chart Title

## Question 4
### Create a Line Chart showing Daily Billing Trend.
### Requirements
* Place **Visit Date** on Columns.
* Place **Billing Amount** on Rows.
* Display markers.
* Format the date axis properly.
Step 3: Drag Visit Date to Columns
1. Click and hold Visit Date.
2. Drag it to the Columns shelf.
Sometimes Tableau automatically displays YEAR(Visit Date). Since the question requires a daily trend, you'll need to change it.
# Step 4: Change Visit Date to Day
1. Click the ▼ (drop-down arrow) on the Visit Date pill in the Columns shelf.
2. Under the Date section, choose: Day or Exact Date
3. If Exact Date is selected, click the ▼ again and choose: Continuous
The pill should now appear as a green pill, for example:
DAY(Visit Date) or Exact Date (This displays one point for each date.)
# Step 5: Drag Billing Amount to Rows
1. Drag Billing Amount to the Rows shelf.
# Step 6: Ensure the Chart Type is Line
If Tableau does not create a line chart:
1. On the Marks card, click the drop-down that says Automatic.
2. Select -> Line
# Step 7: Display Markers (Dots on the Line)
1. On the Marks card, click :- Color
2. Check :- Show Markers
If you do not see Show Markers, try this:
    Click the Marks drop-down.
    Ensure Line is selected.
    Then click Color again.
# Step 8: Format the Date Axis
To make the dates easy to read:
1. Right-click the Visit Date axis (the dates on the X-axis). 2.Click :- Format
3. On the left Format pane, under Dates, choose a format such as: dd-MMM-yyyy
# Step 9: Format the Billing Amount
1. Right-click the Billing Amount axis.
2. Select :- Format
3. Under Numbers, choose: * Number (Standard), or * Currency (if billing amounts represent money).
# Step 10: Add a Chart Title

## Question 5 ### Create a Department Filter.
### Requirements
* Add **Department** as a filter.
* Display the filter.
* Allow users to select only one department at a time.
* Verify that all charts update accordingly.
# Step 2: Add Department to the Filters Shelf
1. In the Data pane (left side), locate Department.
2. Drag Department to the Filters shelf.
# Step 3: Select All Departments
A Filter dialog box appears.
1. Select All (or leave all departments checked). 2. Click OK. Now the filter is applied to the worksheet.
# Step 4: Display the Filter on the Screen
To make the filter visible:
1. On the Filters shelf, click the ▼ next to Department. 2. Click :- Show Filter (A filter card appears on the right side of the worksheet or dashboard.)
# Step 5: Allow Only One Department Selection :- On the filter card (right side):
1. Click the ▼ in the upper-right corner of the filter.
2. Choose one of these options: Single Value (List) or Single Value (Dropdown) (Recommended: Single Value (Dropdown))
# Step 6: Apply the Filter to All Charts :- If you're working with multiple worksheets in a dashboard, do this:
1. Click the ▼ on the Department filter card.
2. Select :- Apply to Worksheets
3. Click Selected Worksheets... or All Using This Data Source (Recommended: All Using This Data Source)
# Step 7: Verify That the Filter Works :- Test the filter.
1. Click the drop-down arrow on the Department filter.
2. Select Cardiology.
Only Cardiology data should appear in:
✅ Horizontal Bar Chart
✅ Pie Chart
✅ Line Chart
Next, select Neurology.(All charts should immediately update to show only Neurology data.)
# Step 8: Save Your Workbook

# Create a Dashboard.(2 point yaad rakhna filter poore dashboard pr apply kese krna h:- )
Apply the Filter to All Worksheets :- On the Department filter card (not the worksheet):
1. Click the ▼ (drop-down arrow) in the upper-right corner of the filter.
2. Click: :- Apply to Worksheets
You will see options like:
• All Using This Data Source
• Selected Worksheets...
Choose: All Using This Data Source


## Question 7 ### Create a Calculated Field named **Net Revenue**.
### Formula Net Revenue = Billing Amount - Discount
### Requirements
* Create the calculated field.
* Display Net Revenue by Department.
* Format the values as currency with zero decimal places.

# Step 2: Create the Calculated Field
In the Data pane (left side), right-click anywhere in the blank area.
Click  Create -> Click Calculated Field...
# Step 3: Name the Calculated Field :- A dialog box opens. In the Name box, type: Net Revenue
# Step 4: Enter the Formula :- In the formula area, type:
[Billing Amount] - [Discount]
It should look like:
Name: Net Revenue
Formula: [Billing Amount] - [Discount]
# Step 5: Validate the Formula :- Look at the bottom of the dialog.
If everything is correct, Tableau displays: The calculation is valid.
If there is an error:
    Check the field names.
    Make sure they exactly match the names in your dataset.
# Step 6: Click OK
# Step 7: Display Net Revenue by Department
Drag Department to Rows
Find Department.
Drag it to the Rows shelf.
Drag Net Revenue to Columns
Find Net Revenue.
Drag it to the Columns shelf.(Tableau automatically creates a horizontal bar chart.)
# Step 8: Ensure the Marks Type is Bar :- If Tableau doesn't display bars:
1. On the Marks card, click Automatic.
2. Choose :- Bar
# Step 9: Format Net Revenue as Currency
1. Right-click SUM(Net Revenue) on the Columns shelf.
2. Click -> Format -> Number Format...
# Step 10: Choose Currency Format :- In the Number Format dialog:
Choose -> Currency (Custom)
# Step 11: Set Decimal Places
Set -> Decimal Places = 0
# Step 12: Add Data Labels (Show Mark Labels)
# Step 13: Sort Departments (Sort Descending)
# Step 14: Add a Chart Title

## Question 8 ### Create a Vertical Bar Chart showing Total Discount by Doctor.
### Requirements
* Display Doctor and Discount.
* Sort in descending order.
* Show data labels.
* Use different colors for each doctor.
# Step 2: Locate the Required Fields :- In the Data pane (left side), find:
    Doctor (Dimension)
    Discount (Measure)
# Step 3: Drag Doctor to Columns
1. Click and hold Doctor.
2. Drag it to the Columns shelf.
# Step 4: Drag Discount to Rows
Drag Discount to the Rows shelf.
# Step 5: Verify the Chart Type :- If Tableau does not create bars:
1. On the Marks card, click Automatic.
2. Select: -> Bar  (Now the chart is a Vertical Bar Chart.)
# Step 6: Sort Doctors in Descending Order
    Click anywhere on the chart.
    Click the Sort Descending icon (bars with a downward arrow) on the toolbar.
# Step 7: Show Data Labels (Show Mark Labels)
# Step 8: Use Different Colors for Each Doctor
1. Drag Doctor from the Data pane.
2. Drop it onto Color on the Marks card.
# Step 9: Change the Color Palette
# Step 10: Format the Discount Values (Optional)
1. Right-click the Discount axis.
2. Click: Format
3. Under Numbers, choose:
    Currency (if Discount is monetary), or
    Number (Standard)
# Step 11: Adjust the Bar Size


## Question 9 ### Highlight the Top 3 Treatments based on Billing Amount.
* Display the Top 3 treatments.
* Sort by Billing Amount in descending order.
* Show Billing Amount values on the chart
* Highlight the top treatment using a different color.
# Step 2: Locate the Required Fields  In the Data pane, locate:
    Treatment (Dimension)
    Billing Amount (Measure)
# Step 3,4 : Drag Treatment to Rows and Drag Billing Amount to Columns
    Drag Treatment to the Rows shelf. Drag Billing Amount to the Columns shelf.
# Step 5: Keep Only the Top 3 Treatments :- 1. Drag Treatment again from the Data pane to the Filters shelf.
A Filter dialog box appears.
2. Click the Top tab.
3. Select: -> By FielS
4. Set:
    Top: 3
    Field: Billing Amount
    Aggregation: Sum
# Step 6: Sort in Descending Order
# Step 7: Show Billing Amount on the Bars(Show Mark Labels)
# Step 8: Highlight the Top Treatment with a Different Color
If your instructor expects dynamic highlighting:
1. Drag Treatment to Color.
2. Click Color → Edit Colors.
3. Assign a distinct color to the first-ranked treatment after applying the Top 3 filter.
# Step 9: Increase Bar Size 


## Question 10 ### Create a Text Table (Crosstab) showing the hospital billing summary.
Display: * Department * Doctor
Measures: * Sum of Billing Amount * Sum of Discount * Sum of Net Revenue
Format the table with: * Appropriate headings * Currency formatting * Grid lines

# Step 2: Locate the Required Fields
In the Data pane, find:
Dimensions * Department *Doctor
Measures * Billing Amount * Discount * Net Revenue (Calculated Field)
# Step 3 : Drag Department to Rows 
1. Drag Department to the Rows shelf.
# Step 4: Drag Doctor Below Department
1. Drag Doctor to the Rows shelf.
2. Drop it after Department.
# Step 5: Create a Text Table
Click Show Me (top-right corner).
Choose the first icon: :- Text Table
# Step 6: Add Billing Amount
1. Drag Billing Amount.
2. Drop it onto -> Text
on the Marks card.
# Step 7: Add Discount
1. Drag Discount.
2. Drop it onto :- Text
# Step 8: Add Net Revenue
Drag Net Revenue.
Drop it onto
Text
Your Marks card should look similar to:
Marks
Text
SUM(Billing Amount)
SUM(Discount)
SUM(Net Revenue)
 # Step 9: Display Each Measure as a Separate Column
Instead of all three values appearing in one cell:
Drag
Measure Names
to the Columns shelf.

Drag
Measure Values
to the Text mark.

#Step 10: Keep Only Required Measures

Tableau may display every measure.

To show only the required ones:

In the Measure Values card,
remove all unwanted measures.

Keep only:

SUM(Billing Amount)
SUM(Discount)
SUM(Net Revenue)

Now your table contains exactly three measure columns.

# Step 12: Format Billing Amount as Currency
1 Right-click
    SUM(Billing Amount)
2 Select
    Format
3 Under Numbers
Choose
Currency (Custom)
4 Decimal Places
0
Click OK.

# Step 13: Format Discount

Repeat the same steps.

Choose

Currency (Custom)

Decimal Places

0



























