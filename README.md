# Power BI Sales Dashboard — Step-by-Step Tutorial

This repository contains the dataset and Power BI file used in the walkthrough video where we build a dynamic, interactive sales dashboard from scratch using Power BI. The tutorial is designed for beginners and managers who want quick insights into regions, product categories, and monthly trends.

---

## YouTube Tutorial
Watch the full video here:  
https://www.youtube.com/watch?v=xXYnuW_xWsg

---

## Tutorial Overview (Based on Transcript)

### Intro 
Imagine you're a regional manager who needs to quickly understand which product categories and regions are performing best.  
In this tutorial, we take raw Excel data and turn it into an interactive Power BI dashboard to help make informed decisions quickly.

---

## Step-by-Step Instructions

### Step 1 — Import Excel Dataset
Go to Home → Get Data → Excel  
Select the file `Sales_Demo_Dataset.xlsx` and check the `SalesData` table.  
Load the data. It includes Region, Product Category, Sales, and Month.
Once loaded, the dataset is ready for visualization.

---

### Step 2 — Total Sales (Card)
Add a Card visual to show total sales.  
Drag Sales into the card.  
Rename the title to "Total Sales" for clarity.

---

### Step 3 — Sales by Region (Bar Chart)
Add a clustered column chart to compare performance across regions.  
Drag Region to the X-axis and Sales to the Y-axis.

Example insight: East leads, while West requires more attention.

---

### Step 4 — Monthly Sales Trend (Line Chart)
Add a line chart to track monthly trends.  
Drag Month to the X-axis and Sales to the Y-axis.

Observation: Sales are declining, which may require actions like boosting marketing or adjusting pricing.

---

### Step 5 — Product Category Slicer
Add a slicer for Product Category.  
Selecting a category updates all visuals automatically.  
Hold CTRL to choose multiple categories at once.

---

### Step 6 — Closing / Summary
In a few minutes, we turned raw Excel data into an interactive Power BI dashboard.

Final question from the tutorial:  
How can you check total sales or regional sales for a specific month?  
- Use the Month field in the line chart, or  
- Add a Month slicer to filter the entire dashboard.


---

## How to Use This Repository

1. Download or clone the repository.  
2. Open the Excel file to explore the dataset.  
3. Open the PBIX file in Power BI Desktop.  
4. Explore or modify the dashboard as needed.

---

## Additional Notes
Feel free to use this repository for learning, teaching, or practice.

If the tutorial helps you, consider subscribing to the YouTube channel for more Power BI content.
