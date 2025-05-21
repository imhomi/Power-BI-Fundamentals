## Assignments Summary

### 1. 🧠 [Introduction to Power BI](https://github.com/imhomi/Power-BI-Fundamentals/blob/main/Introduction%20to%20PowerBI.zip)

### 2. 📥 [Data Extraction](https://github.com/imhomi/Power-BI-Fundamentals/blob/main/Data%20Extraction.pbix)

### 3. 🧩 [Shaping and Combining Data](https://github.com/imhomi/Power-BI-Fundamentals/blob/main/Shaping%20and%20Combining%20Data.zip)

### 4. 🔗 [Data Modeling](https://github.com/imhomi/Power-BI-Fundamentals/blob/main/Data%20Modeling.zip)

### 5. 📈 [Data Visualization](https://github.com/imhomi/Power-BI-Fundamentals/blob/main/Data%20Visualization.zip)

### 6. ☁️ [Power BI Service](https://github.com/imhomi/Power-BI-Fundamentals/blob/main/PowerBI%20Service.zip)

### 7. 🔌 [Power BI Solution & Direct Connectivity](https://github.com/imhomi/Power-BI-Fundamentals/blob/main/Power%20BI%20Solution%20&%20Direct%20Connectivity)

### 8. 🛠️ [Development with Power BI](https://github.com/imhomi/Power-BI-Fundamentals/blob/main/Development%20with%20PowerBI.zip)


## 🛠️ Tools & Technologies Used

* 💻 Power BI Desktop
* 🌐 Power BI Service
* 📊 DAX (Data Analysis Expressions)
* 🔍 Power Query Editor
* 📁 Excel, CSV, Web Sources
  
---
# Before starting with my repo ....you need to know what exactly is PowerBI!!
Data Analysis using Power BI
PowerBI is used to ***visualize*** the data, which indeed helps people understand it in a clearer and more accessible way.
Competitors who? : Tableau, Qliksense, SAS, Looker. ZOHO, SAP, Google Analytics

So, why choose Power BI when there are so many other tools available? - refer to Gartner's BI magic quadrant
![image](https://github.com/user-attachments/assets/e3f50dc0-8918-4b2e-a693-cad1e904b6ff)

Power BI has 2 main components:

1) Power BI Desktop:
* Power BI Desktop is a free Windows application used to create and develop reports.
* It is used for data modeling, visualization, report creation, and data transformation using Power Query.
* Primarily used by data analysts and report developers to design interactive and insightful reports.
* To run Power BI Desktop smoothly, a Windows laptop with at least 8 GB RAM is recommended.
* Think of it as the developer's console, where reports and dashboards are built before publishing.

2) Power BI Service:
* Power BI Service is the cloud-based platform where reports and dashboards created in Power BI Desktop are published and shared.
* It enables collaboration, real-time data updates, and interactive dashboards through the web.
* Allows users to schedule data refresh, manage data security, and share reports within the organization or with external stakeholders.
* Accessible from any device with internet access — no installation needed.
* Often used by business users, stakeholders, and decision-makers to view and interact with reports.
---
There are 3 Key Views in Power BI Desktop
1) Report View:
* This is the canvas area where you design your reports.
* Create visuals, build interactive dashboards, and craft compelling data stories.
* Drag and drop charts, slicers, KPIs, and more.
* Ideal for designing the user interface of your reports.

2) Data View (Table View):
* This view displays your raw data in a table format.
* Once data is imported, you can inspect rows and columns of each table.
* Useful for data validation, cleaning, and checking data types.
* Helps ensure data accuracy before modeling.

3) Model View
* This is where you define relationships between tables.
* Create one-to-many or many-to-many relationships.
* Set cardinality, cross-filter direction, and more.
* Essential for data modeling and enabling correct filtering across visuals.
---
Data Types in Power BI
Every column in Power BI has a specific data type that defines the kind of data it contains. Proper data typing is essential for accurate analysis and visualization.

**1) Whole Number**
- Contains only whole numbers (e.g., 1, 50, 999).
- Symbol: Σ (Summation)

**2) Decimal Number**
- Contains decimal (floating point) values (e.g., 3.14, 99.99).
- Symbol: Σ

**3) Fixed Decimal Number**
- Typically used for currency values (e.g., \$200.00, ₹1500.50).
- Symbol: Σ

**4) Date**
- Contains only date values (e.g., 02/02/2025).
- Symbol: Calendar

**5) Time**
- Contains only time values (e.g., 10:31 PM).
- Symbol: Clock

**6) Date/Time**
- Contains both date and time (e.g., February 2, 2025 — 10:31 PM).
- Symbol: Calender

**7) Text**
- Contains alphabetical or alphanumerical values (e.g., "India", "Customer123").
- Symbol: None

---
 ***Note:***
Changes made in Power BI (in **Power Query** or the **Power BI layer**) **do not affect the original source file**. All transformations are applied **only within Power BI**.

---

**Axes in Power BI Visualizations**

***X-Axis (Categorical Axis)***

Used for **categories or dimensions** such as:

* Date
* Product
* Segment
* Country
* Customer Name

***Y-Axis (Numerical Axis)***

Used for **numeric values** that are being measured or analyzed, such as:

* Sales
* Cost
* Profit
* Count

---

**What is a Tooltip?**

The **tooltip** is the small information box that appears when you hover over a data point in a visual. It displays additional details like values, categories, and comparisons to give more context to the data.

---
### Legend vs Small Multiples

 * **Legend**:
  When you place a field (e.g., *Segment*) in the **Legend**, the data is **color-coded within a single visual**, allowing **side-by-side comparison** across categories (e.g., Product Sales split by Segment).

* **Small Multiples**:
  When you place a field (e.g., *Segment*) in **Small Multiples**, it creates **separate charts** for each category (e.g., a different column chart per Segment).
---
### Column Chart: Compare Numerical Data

You can analyze **multiple numerical values together** in a Column Chart by placing them on the **Y-axis** (e.g., Sales vs. COGS by Product).

#### 3 Types of Column Charts:

1. **Clustered Column Chart**

   * Shows multiple categories **side by side**
   * Best for **comparing values** across multiple groups
   * *Example: Sales of products across different years*

2. **Stacked Column Chart**

   * Stacks different categories **within the same column**
   * Best for **part-to-whole comparison** while still seeing totals
   * *Example: Sales breakdown by country for each product*

3. **100% Stacked Column Chart**

   * Same as stacked chart but shows **percentage (%) contribution** instead of actual values
---
### Column vs Bar Chart

* **Column Chart**

  * Good for **categorical & periodical analysis**
  * Examples: *Sales by Product*, *Sales by Year*

* **Bar Chart**

  * Best for **categorical analysis** (especially when there are **many categories**)
  * Not ideal for **periodical data**
---
### Line Chart
* Used **only for periodical analysis** to track **trends over time**
* Not suitable for categorical analysis
---
###  Y-Axis vs. Secondary Y-Axis

* Use **Y-Axis** for numerical fields with **similar scales** (e.g., *Sales* and *COGS*)
* Use **Secondary Y-Axis** when comparing values with **different scales/magnitudes** (e.g., *Sales* and *Selling Price per Unit*)
---
### Area Chart

* Same as a Line Chart but with the **area below the line shaded**
---
### Card Visuals

* Used to display **high-level KPIs** like:

  * Total Sales
  * Total COGS
  * Profit
* Usually placed **at the top or side of reports**
---
### Slicers
* **Very important!**
  Slicers act as **filters** that allow users to "**slice and dice**" data dynamically
---
### Decomposition Tree

* Helps **break down a single metric** (e.g., *Sales*) by **multiple dimensions** (e.g., *Region*, *Category*, *Customer Type*)

---
### Custom Visuals from AppSource

* Power BI has **built-in visuals** in the **Visualizations pane**
* You can also download more visuals from **AppSource** (Power BI’s equivalent of the Play Store/App Store)
* Visuals may be:

  * Free or Paid
  * Microsoft-certified or not

⚠**Warning**:
Using **non-certified or unlicensed visuals** may impact **report performance**

---


