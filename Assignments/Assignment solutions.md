# Assignment 2025 Solutions

## Question 1. Create an Animated Scatter Chart for Ship Date using the Superstore Dataset.

1. Drag Sales to **Columns**
2. Drag Profit to **Rows**
3. Drag Category to **Marks/Color**
4. Drag Order Id to **Detail**
5. Change **Automatic** to **Circle** in Marks pane
6. Drag **Ship Date** to **Pages**, You can change it to either Year/Month/Day by clicking on the down arrow (🔻) in the Pages Page > Ship Date
7. Now your graph is created, now in the right side of the screen in the visualization pane you will see the **Ship Date** it will have play(▶)and pause (⏹) to run the animation

## Question 2. Create table and matrix for amount, name and region using customer dataset.
**Dataset:** Sample Superstore dataset
- To Create table:
    1. Drag **Customer Name** and **Country/Region** To rows, If any pop up opens select **Add all**. Alternatively, Instead of Country/Region, you can drag City, or Postal Code to the rows
    2. Drag **Sales** to **Text** Pane inside **Marks**

- To Create Matrix:
    1. Drag **Customer Name** to Columns and **Country/Region** To rows, If any pop up opens select **Add all**. Alternatively, Instead of Country/Region, you can drag City, or Postal Code to the rows
    2. Drag **Sales** to **Text** Pane inside **Marks**

## Question 3. Create a donut chart of job classification using customer dataset.

To create a **Donut Chart of Job Classification** in Tableau using the **Customer dataset**, follow these steps.

#### Steps to Create a Donut Chart

1. Open Tableau and connect to the **Customer** dataset.
2. Drag **Job Classification** to the **Color** shelf on the **Marks** card.
3. Drag **Number of Records** (or `COUNT(Customer ID)`) to **Angle**.
4. Change the **Marks** type to **Pie**.
5. Drag **Number of Records** again to **Label** to display the count for each job classification.

#### Create the Donut Effect

1. Drag **MIN(1)** to the **Columns** shelf twice.
2. Right-click the second **MIN(1)** and select **Dual Axis**.
3. On the second **Marks** card:

   * Change the mark type to **Pie**.
   * Remove **Job Classification** from **Color**.
   * Set the color to **White** (or match the dashboard background).
   * Reduce the **Size** to create the hole in the center.
4. Right-click the secondary axis and uncheck **Show Header**.
5. Adjust the pie sizes until the chart appears as a donut.

## Question 4. Create a hierarchy line chart for time series as “ship-date” using superstore dataset.

1. In columns Write **YEAR(Ship Date)** and press Enter
2. Drag Sales to Rows
3. From marks pane, select line
4. In columns Add **Quarter(Ship Date)** and press Enter

## Question 5. Create a slicer for order-date and bar chart of item description using purchase order dataset.

**Dataset: Purchase Order**\

1. Drag **Item Description** to Rows
2. Drag **Order No.** and **Cost per Order** to Columns
3. Drag **Order Date** to Filters and select **Range of Dates** then click **Next** then **Apply** and **OK**
4. Click 🔻 in Order Date of Filters and click **Show Filters**
5. Drag the range in the Order Date filter to Slice the data for a particular range


---

# Assignment 3 Solutions

## Question 1. Using the data in the Excel files Student Grades, construct a Scatter chart for midterm versus final exam and add a linear trend line. What is the regression model? if  a student scores 85 on the midterm, what would be  you predict her grade on the final exam to be?

## Question 2. Create a pie chart to show the breakup of 100% contributing component of categories using pricing data set.

## Question 3. Create a histogram to investigate the city-mpg distribution of cars using pricing dataset

## Question 4. Create a pareto analysis chart using bicycle inventory data
Pareto analysis chart requires to create following two charts on the same plane:
- Bar Graph
- Line Graph
Both the charts will use the same mesures to create the plane.

1. Move **Bicycle Model** to Columns
2. Move **Inventory** to Rows 
3. Move **Inventory** to Rows again
4. On the second Inventory down arrow click **Quick Table Calculation** > **Running Total**
5. On the second Inventory down arrow click **Edit Table Calculation** > **Add Secondary Calculation**, In Secondary Calculation Type select **Percent of Total** and set Compute Using **Table (Across)**
6. In the **Marks** tab, select the second Inventory and change **Automatic** to **Line**
7. Click Bicycle Model in the left pane and now Click on the red icon in the menu
8. Now click arrow on the second inventory in the rows and select dual axis

## Question 5. Create a line chart using the purchase order data set
In this we will select **Order date** and **sales** to create the chart because the nature of line chart is to show changes over time

1. Move **Order Date** in Column
2. Move **Sales** in Rows
3. Your Line Chart is created

## Question 6. Create a group and set using the purchase order dataset

## Question 7. Create a parameter to show the top 10 cities based on the population using cities data set.

1. Create a Parameter:
    - Right click in the empty area in left pane
    - Click Create Parameter
    - Fill the form with following values
    - Click OK, now you will see the parameter with name Top Cities in the left pane:
2. Create a filter
    - Drag **City Name** from tables to Filters tab
    - it will open a new pop up, go to **Top** tab in it and fill it accordingly
    - Click **Apply** and **OK**
3. Creating Graph:
    - Move field **Population** to Columns
    - Move field **City Name** to Rows 
4. Showing Parameter
    - Now Right click on Parameter **Top Cities** and click **Show Parameter**, it will add a Top Cities input in the right pane
    - Updating the number in the input will update the graph according to the value input
5. Your top n cities is created.