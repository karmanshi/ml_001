## Question 1. Create an Animated Scatter Chart for Ship Date using the Superstore Dataset.

1. Drag Sales to **Columns**
2. Drag Profit to **Rows**
3. Drag Category to **Marks/Color**
4. Drag Order Id to **Detail**
5. Change **Automatic** to **Circle** in Marks pane
6. Drag **Ship Date** to **Pages**, You can change it to either Year/Month/Day by clicking on the down arrow (🔻) in the Pages Page > Ship Date
7. Now your graph is created, now in the right side of the screen in the visualization pane you will see the **Ship Date** it will have play(▶)and pause (⏹) to run the animation

---

## Question 2. Create table and matrix for amount, name and region using customer dataset.

#### To Create table:
**Dataset:** Sample Superstore dataset

1. Drag **Customer Name** and **Country/Region** To rows, If any pop up opens select **Add all**. Alternatively, Instead of Country/Region, you can drag City, or Postal Code to the rows

2. Drag **Sales** to **Text** Pane inside **Marks**


#### To Create Matrix:
**Dataset:** Sample Superstore dataset

1. Drag **Customer Name** to Columns and **Country/Region** To rows, If any pop up opens select **Add all**. Alternatively, Instead of Country/Region, you can drag City, or Postal Code to the rows

2. Drag **Sales** to **Text** Pane inside **Marks**
---

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