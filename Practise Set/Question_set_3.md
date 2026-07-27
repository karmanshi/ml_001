# Tableau Data Visualization Lab Test (Practice – 3)

## Problem Statement

**Sunrise Supermarket Pvt. Ltd.** wants to analyze its grocery sales data using Tableau. You have been provided with the following dataset.

Create the required visualizations and dashboard in Tableau.

---

# Dataset (Save as `Supermarket_Data.csv`)

| Bill ID | Bill Date   | City      | Category  | Product  | Quantity | Sales | Cost |
| ------- | ----------- | --------- | --------- | -------- | -------: | ----: | ---: |
| B1001   | 01-Mar-2026 | Mumbai    | Beverages | Tea      |       20 |  6000 | 4200 |
| B1002   | 01-Mar-2026 | Delhi     | Snacks    | Chips    |       35 |  3500 | 2200 |
| B1003   | 02-Mar-2026 | Bengaluru | Dairy     | Milk     |       50 |  4000 | 3000 |
| B1004   | 03-Mar-2026 | Chennai   | Fruits    | Apple    |       30 |  4500 | 3200 |
| B1005   | 04-Mar-2026 | Mumbai    | Bakery    | Bread    |       40 |  3200 | 2000 |
| B1006   | 05-Mar-2026 | Delhi     | Beverages | Coffee   |       18 |  7200 | 4800 |
| B1007   | 06-Mar-2026 | Bengaluru | Snacks    | Biscuits |       28 |  2800 | 1800 |
| B1008   | 07-Mar-2026 | Chennai   | Dairy     | Cheese   |       15 |  5250 | 3600 |
| B1009   | 08-Mar-2026 | Mumbai    | Fruits    | Banana   |       45 |  2700 | 1800 |
| B1010   | 09-Mar-2026 | Delhi     | Bakery    | Cake     |       12 |  6000 | 4100 |

---

# Tasks

## Question 1

### Import the dataset into Tableau.

### Requirements

* Load the CSV file.
* Verify that all fields have appropriate data types.
* Ensure **Bill Date** is recognized as a Date field.

---

## Question 2

### Create a Bar Chart showing Sales by City.

### Requirements

* Place **City** on Rows.
* Place **Sales** on Columns.
* Sort in descending order.
* Display data labels.

---

## Question 3

### Create a Donut Chart showing Sales Contribution by Category.

### Requirements

* Use **Category** as the dimension.
* Use **Sales** as the measure.
* Display percentage labels.
* Show category names.

---

## Question 4

### Create a Line Chart showing Daily Sales Trend.

### Requirements

* Place **Bill Date** on Columns.
* Place **Sales** on Rows.
* Show markers.
* Format the chart with an appropriate title.

---

## Question 5

### Create a City Filter.

### Requirements

* Add **City** as a filter.
* Display the filter on the worksheet.
* Allow users to select a single city.
* Verify that all related charts update.

---

## Question 6

### Create a Dashboard.

### Requirements

Include the following worksheets:

* Sales by City
* Category Sales Donut Chart
* Daily Sales Trend

Also:

* Add the City Filter.
* Arrange all worksheets neatly.
* Provide the dashboard title:

**Supermarket Sales Dashboard**

---

## Question 7

### Create a Calculated Field named **Profit**.

**Formula**

```
Profit = Sales - Cost
```

### Requirements

* Create the calculated field.
* Display Profit for each Product.
* Format values as currency with two decimal places.

---

## Question 8

### Create a Horizontal Bar Chart showing Profit by Product.

### Requirements

* Display Product and Profit.
* Sort by Profit in descending order.
* Show data labels.

---

## Question 9

### Display the Top 5 Products based on Sales.

### Requirements

* Create a visualization showing the Top 5 products.
* Sort in descending order of Sales.
* Display Sales values.
* Highlight the highest-selling product using a different color.

---

## Question 10

### Create a Text Table (Crosstab) showing the sales summary.

### Requirements

Display:

* City
* Category

Measures:

* Sum of Sales
* Sum of Cost
* Sum of Profit

Format the table with appropriate headings and currency formatting.

---

# Bonus Question (Optional)

Create a calculated field named **Average Selling Price**.

**Formula**

```
Average Selling Price = Sales / Quantity
```

Create a bar chart showing **Average Selling Price by Product**, sort it in descending order, and display data labels.

---

## Skills Covered

* Importing CSV data
* Data type verification
* Bar charts
* Donut chart creation
* Line charts
* Filters
* Dashboard creation
* Calculated fields
* Sorting
* Top N analysis
* Crosstab (Text Table)
* Data formatting
* Dashboard layout and interactivity
