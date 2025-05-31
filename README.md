

## 🛍️ Shopify E-Commerce Power BI Dashboard – Description

This **interactive Power BI dashboard** provides a overview of Shopify-based e-commerce performance, enabling data-driven decision-making for marketing, operations, and sales strategies.

### 🎯 Key Objectives:

* Monitor total sales, profit, and order quantities.
* Analyze customer behavior, top-selling products, and payment preferences.
* Visualize performance trends over time and across different regions.

---

### 📌 Dashboard Components:

#### 🔢 **Top-Level KPIs:**

* **Amount (438K):** Total revenue generated from all transactions.
* **Quantity (5615):** Total number of units sold.
* **Profit (37K):** Net earnings after subtracting costs.
* **Average (121K):** Average revenue per order, calculated using:

  ```DAX
  Average Sales = AVERAGE(Orders[Amount])
  ```

#### 📅 **Quarter Selection Filter:**

* Allows users to filter the entire report by Q1, Q2, Q3, or Q4.
* Dynamically updates all visualizations based on the selected time period.

---

### 📊 Visual Analysis Sections:

#### 🧍‍♂️ **Top 5 Customer Names:**

* Highlights high-value customers by purchase volume.
* Helps identify loyal and high-spending clients (e.g., Jayant leads the chart).

#### 🛒 **Sum of Quantity by Category:**

* Pie chart showing category-wise product quantity distribution.
* Clothing leads with **62.62%**, followed by Electronics and Furniture.

#### 📈 **Profit or Loss by Month:**

* Bar chart showing monthly profit and loss trends.
* Identifies peak months (e.g., January & December: 10K profit) and low-performance periods (e.g., July, September, December show losses).

#### 🌍 **Top 3 States by Amount:**

* Bar chart showing the top-performing states by revenue.
* **Maharashtra** is the top contributor, followed by **Madhya Pradesh** and **Uttar Pradesh**.

#### 💳 **Payment Mode Percentage:**

* Pie chart visualizing customer payment preferences:

  * **COD** dominates at **43.74%**
  * **UPI** and **Debit/Credit Cards** follow
  * Insights useful for optimizing checkout options

#### 🧾 **Top 5 Products by Profit:**

* Bar chart ranking products by profit contribution.
* **Printers** lead the list, followed by **Bookcases**, **Sarees**, etc.

---

### 📁 Data Model (Fields Used):

* **Orders Table:**

  * `Order Date`, `CustomerName`, `Amount`, `Quantity`, `Profit`, `State`
* **Products Table:**

  * `Category`, `Sub-Category`, `PaymentMode`, `Order ID`

---

### 🛠️ Tools & Technologies:

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)** for calculated Average Value
* **Filters & Slicers** for interactivity
* **Dark UI Theme** for modern and readable visual presentation
