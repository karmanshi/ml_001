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
    - Fill the form with following values:
    ![alt text](image.png)
    - Click OK, now you will see the parameter with name Top Cities in the left pane, like:
    ![alt text](image-1.png)
2. Create a filter
    - Drag **City Name** from tables\
    ![alt text](image-2.png)\
    to Filters tab\
    ![alt text](image-3.png)\
    - it will open a new pop up, go to **Top** tab in it:
    and fill it like following:
    ![alt text](image-4.png)
    - Click **Apply** and **OK**
3. Creating Graph:
    - Move field **Population** to Columns
    - Move field **City Name** to Rows 
4. Showing Parameter
    - Now Right click on Parameter **Top Cities** and click **Show Parameter**, it will add a Top Cities input in the right pane like below\
    ![alt text](image-5.png)
    - Updating the number in the input will update the graph according to the value input
5. Your top n cities is created.