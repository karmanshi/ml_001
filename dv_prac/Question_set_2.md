# Tableau Data Visualization Lab Test (Practice – 2)

## Problem Statement

**XYZ Hospital Management Pvt. Ltd.** wants to analyze patient billing and treatment data using Tableau. You have been provided with the following dataset.

Create the required visualizations and dashboard in Tableau.

---

## Dataset (Save as `Hospital_Data.csv`)

| Patient ID | Visit Date  | Department  | Doctor    | Treatment     | Patients | Billing Amount | Discount |
| ---------- | ----------- | ----------- | --------- | ------------- | -------- | -------------- | -------- |
| P1001      | 01-Feb-2026 | Cardiology  | Dr. Mehta | ECG           | 5        | 25000          | 2000     |
| P1002      | 02-Feb-2026 | Orthopedics | Dr. Rao   | X-Ray         | 8        | 16000          | 1200     |
| P1003      | 03-Feb-2026 | Neurology   | Dr. Shah  | MRI Scan      | 3        | 45000          | 5000     |
| P1004      | 04-Feb-2026 | Pediatrics  | Dr. Patel | Vaccination   | 12       | 18000          | 1500     |
| P1005      | 05-Feb-2026 | Cardiology  | Dr. Mehta | Consultation  | 10       | 20000          | 1000     |
| P1006      | 06-Feb-2026 | Orthopedics | Dr. Rao   | Surgery       | 2        | 80000          | 7000     |
| P1007      | 07-Feb-2026 | Neurology   | Dr. Shah  | CT Scan       | 4        | 36000          | 3000     |
| P1008      | 08-Feb-2026 | Pediatrics  | Dr. Patel | Consultation  | 15       | 22500          | 1800     |
| P1009      | 09-Feb-2026 | Cardiology  | Dr. Mehta | Angiography   | 2        | 90000          | 8000     |
| P1010      | 10-Feb-2026 | Orthopedics | Dr. Rao   | Physiotherapy | 9        | 27000          | 2500     |

---

# Tasks

## Question 1

### Import the dataset into Tableau.

### Requirements

* Load the CSV file.
* Verify that all columns are recognized with appropriate data types.
* Ensure **Visit Date** is recognized as a Date field.

---

## Question 2

### Create a Horizontal Bar Chart showing Billing Amount by Department.

### Requirements

* Place **Department** on Rows.
* Place **Billing Amount** on Columns.
* Sort in descending order.
* Display data labels.
* Apply an attractive color palette.

---

## Question 3

### Create a Pie Chart showing Billing Contribution by Treatment.

### Requirements

* Use **Treatment** as the category.
* Use **Billing Amount** as the measure.
* Display percentage labels.
* Show Treatment names.

---

## Question 4

### Create a Line Chart showing Daily Billing Trend.

### Requirements

* Place **Visit Date** on Columns.
* Place **Billing Amount** on Rows.
* Display markers.
* Format the date axis properly.

---

## Question 5

### Create a Department Filter.

### Requirements

* Add **Department** as a filter.
* Display the filter.
* Allow users to select only one department at a time.
* Verify that all charts update accordingly.

---

## Question 6

### Create a Dashboard.

### Requirements

Include the following worksheets:

* Billing by Department
* Treatment Contribution Pie Chart
* Daily Billing Trend

Also:

* Add the Department Filter.
* Arrange the charts neatly.
* Add a dashboard title:

> **Hospital Billing Analysis Dashboard**

---

## Question 7

### Create a Calculated Field named **Net Revenue**.

### Formula

```
Net Revenue = Billing Amount - Discount
```

### Requirements

* Create the calculated field.
* Display Net Revenue by Department.
* Format the values as currency with zero decimal places.

---

## Question 8

### Create a Vertical Bar Chart showing Total Discount by Doctor.

### Requirements

* Display Doctor and Discount.
* Sort in descending order.
* Show data labels.
* Use different colors for each doctor.

---

## Question 9

### Highlight the Top 3 Treatments based on Billing Amount.

### Requirements

* Display the Top 3 treatments.
* Sort by Billing Amount in descending order.
* Show Billing Amount values.
* Highlight the top treatment using a different color.

---

## Question 10

### Create a Text Table (Crosstab) showing the hospital billing summary.

### Requirements

Display:

* Department
* Doctor

Measures:

* Sum of Billing Amount
* Sum of Discount
* Sum of Net Revenue

Format the table with:

* Appropriate headings
* Currency formatting
* Grid lines

---

# Bonus Question (Optional)

Create a calculated field named **Average Billing per Patient**.

### Formula

```
Average Billing per Patient = Billing Amount / Patients
```

Create a bar chart showing **Average Billing per Patient by Department**, display data labels, and sort the chart in descending order.
