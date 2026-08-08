<img width="1111" height="632" alt="Screenshot 2026-08-08 224817" src="https://github.com/user-attachments/assets/846954b1-f8ba-4799-b5db-eb9384b6dc58" />

# 🛒 Blinkit E-Commerce Analysis

An end-to-end **E-Commerce Data Analytics and Business Intelligence project** focused on analyzing Blinkit's grocery sales data to uncover insights into **sales performance, product categories, outlet performance, customer preferences, and business growth opportunities**.

The project combines **Python/SQL-style data analysis, Power BI, data visualization, and business storytelling** to transform raw grocery sales data into actionable insights.

---

## 📌 Project Overview

Blinkit operates in the fast-growing quick-commerce industry where understanding **sales trends, product demand, outlet performance, customer preferences, and inventory distribution** is critical.

This project analyzes grocery sales data to answer important business questions such as:

* Which product categories generate the highest sales?
* Which outlets perform best?
* How does outlet size affect sales?
* Which location types contribute the most revenue?
* What is the relationship between product visibility and sales?
* How does customer rating vary across outlets?
* Which products contribute most to overall revenue?
* What factors influence outlet performance?

---

# 🎯 Business Objectives

The primary objectives of this project are:

1. Analyze overall sales performance.
2. Identify top-performing product categories.
3. Compare different outlet types and sizes.
4. Analyze sales across different locations.
5. Understand customer rating patterns.
6. Identify products contributing significantly to revenue.
7. Build an interactive business intelligence dashboard.
8. Generate actionable insights for business decision-making.

---

# 🛠️ Tools & Technologies

| Tool                    | Purpose                       |
| ----------------------- | ----------------------------- |
| 🐍 Python               | Data analysis & preprocessing |
| 🐼 Pandas               | Data manipulation             |
| 🔢 NumPy                | Numerical analysis            |
| 📊 Matplotlib           | Data visualization            |
| 🎨 Seaborn              | Statistical visualization     |
| 🗄️ SQL                 | Data querying & analysis      |
| 📈 Power BI             | Interactive dashboard         |
| 🧮 DAX                  | KPI calculations              |
| 🔄 Power Query          | Data transformation           |
| 📊 Microsoft PowerPoint | Data storytelling             |
| 📂 GitHub               | Project management            |

---

# 🔄 Project Workflow

```text
Raw Grocery Dataset
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Exploratory Data Analysis
        ↓
SQL / Query Analysis
        ↓
Power Query
        ↓
Data Modeling
        ↓
DAX Measures
        ↓
Power BI Dashboard
        ↓
Business Insights
        ↓
Presentation
```

---

# 🧹 Data Preparation

The raw Blinkit grocery dataset was prepared before performing analysis.

Major preprocessing steps included:

* Loading raw datasets
* Checking dataset dimensions
* Understanding data types
* Detecting missing values
* Checking duplicate records
* Handling inconsistent values
* Exploring categorical variables
* Analyzing numerical distributions
* Validating sales-related fields
* Preparing data for visualization

Typical analysis operations include:

```python
df.shape
df.info()
df.describe()
df.isnull().sum()
df.duplicated().sum()
df.nunique()
df.columns
```

---

# 🔎 Exploratory Data Analysis

The project explores multiple dimensions of Blinkit's business performance.

## 📦 Product Analysis

Analysis includes:

* Product categories
* Item visibility
* Item sales
* Product type performance
* High-performing products
* Low-performing products

---

## 🏪 Outlet Analysis

The analysis compares:

* Outlet type
* Outlet size
* Outlet location
* Outlet establishment year
* Outlet-level sales
* Average customer ratings

This helps identify which outlet characteristics are associated with stronger business performance.

---

## 💰 Sales Analysis

Key sales metrics include:

* Total sales
* Average sales
* Sales by product category
* Sales by outlet
* Sales by location
* Sales by outlet size
* Sales contribution by product type

---

## ⭐ Customer Rating Analysis

Customer satisfaction is analyzed using:

* Average rating
* Rating distribution
* Rating by outlet type
* Rating by location
* Rating vs sales performance

---

# 📊 Power BI Dashboard

The Power BI dashboard converts the raw dataset into an interactive business intelligence solution.

### Dashboard Features

* 📌 KPI cards
* 📈 Sales analysis
* 🏪 Outlet performance
* 📦 Product category analysis
* 📍 Location analysis
* ⭐ Customer rating analysis
* 📊 Interactive charts
* 🎛️ Dynamic filters
* 🔎 Slicers
* 📉 Comparative analysis

---

# 📌 Key KPIs

The dashboard focuses on important business metrics such as:

* **Total Sales**
* **Average Sales**
* **Number of Items**
* **Average Rating**
* **Sales by Outlet**
* **Sales by Category**
* **Sales by Location**
* **Sales by Outlet Size**

---

# 🧮 DAX & Power BI

DAX was used to create dynamic measures and business KPIs.

Example:

```DAX
Total Sales =
SUM('BlinkIT Grocery Data'[Sales])
```

Example:

```DAX
Average Sales =
AVERAGE('BlinkIT Grocery Data'[Sales])
```

Example:

```DAX
Average Rating =
AVERAGE('BlinkIT Grocery Data'[Rating])
```

These measures allow the dashboard to dynamically update based on selected filters and slicers.

---

# 💡 Business Insights

The analysis helps identify:

### 🏪 Outlet Performance

Different outlet types and sizes show different sales performance, allowing businesses to identify stronger outlet formats.

### 📦 Product Performance

Certain product categories contribute significantly more to total revenue and can therefore receive greater attention in inventory and promotional planning.

### 📍 Location Analysis

Outlet location plays an important role in sales performance and can help guide future expansion strategies.

### ⭐ Customer Satisfaction

Customer ratings provide an additional perspective for evaluating outlet and product performance.

### 📈 Sales Optimization

Combining product, outlet, location, and customer metrics provides a broader view of the factors influencing business performance.

---

# 📁 Repository Structure

```text
Blinkit-Ecommerce-Analysis/
│
├── 📊 BlinkIT Grocery Data.csv
│
├── 📈 Blinkit_Ecommerce_Analysis_Dashboard.pbix
│
├── 📑 Blinkit Analysis.pptx
│
├── 📄 Query Doc (1).docx
│
├── 📊 data.csv
│
├── 🔧 blinkit.json
│
├── 🖼️ background kpi (1).png
│
├── 📁 Images/
│
├── 📦 Images-20260802T203640Z-1-001.zip
│
└── 📄 README.md
```

The repository currently contains these project assets, including the Power BI dashboard, grocery dataset, presentation, query document, and visualization resources.

---

# ▶️ How to Use

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Rohit3435/Blinkit-Ecommerce-Analysis.git
```

## 2️⃣ Explore the Dataset

Open:

```text
BlinkIT Grocery Data.csv
```

or:

```text
data.csv
```

---

## 3️⃣ Open the Power BI Dashboard

Open:

```text
Blinkit_Ecommerce_Analysis_Dashboard.pbix
```

using **Microsoft Power BI Desktop**.

---

## 4️⃣ Explore the Analysis

The repository also contains:

```text
Blinkit Analysis.pptx
```

which presents the major findings and business insights.

---

# 📚 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* SQL Analysis
* Data Visualization
* Power BI
* Power Query
* DAX
* Data Modeling
* KPI Development
* Business Intelligence
* Business Analysis
* Data Storytelling
* Dashboard Development
* Git & GitHub

---

# 🚀 Future Improvements

Potential improvements include:

* Customer segmentation
* Sales forecasting
* Product demand prediction
* Outlet performance prediction
* Customer churn analysis
* Inventory optimization
* Machine Learning-based sales prediction
* Automated dashboard refresh
* SQL database integration
* Advanced Power BI analytics

---

# 👨‍💻 Author

**Rohit Verma**

🎓 Electronics & Communication Engineering
🏫 Netaji Subhas University of Technology (NSUT)

### Areas of Interest

**Data Analytics | SQL | Python | Power BI | Business Intelligence**

---

# ⭐ Support

If you found this project useful, consider giving the repository a ⭐.

**Thanks for visiting! 🚀**
