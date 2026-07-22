# Indian-E-Commerce-Power-BI-Dashboards

A collection of **4 interactive Power BI dashboards** built on real Indian e-commerce and quick-commerce datasets — **Flipkart**, **Myntra**, **Zepto**, and **Blinkit** — covering sales analysis, product performance, customer trends, outlet insights, and regional breakdowns.

---

## 📸 Dashboard Previews

###  Flipkart Sales Dashboard
<img width="1210" height="683" alt="Dashboard screenshot" src="https://github.com/user-attachments/assets/bc0880b9-0acf-4a4f-ac36-499966d741a6" />


###  Myntra Sales Analysis Dashboard
<img width="1187" height="671" alt="Dashboard screenshot" src="https://github.com/user-attachments/assets/fa0dbb2a-2149-4426-9ad6-ea0c3b80b8e8" />


###  Zepto Grocery Dashboard
<img width="1197" height="674" alt="Dashboard screenshot" src="https://github.com/user-attachments/assets/709d5873-8558-44bf-a37a-852330b498bb" />


###  Blinkit Grocery Dashboard
<img width="1179" height="658" alt="Dashboard Screenshot" src="https://github.com/user-attachments/assets/c8dbcd94-beef-4ba4-b0ee-9d5f79399354" />


---

## 📁 Repository Structure

```
ecommerce-powerbi-dashboards/
│
├── 📊 Flipkart/
│   ├── Flipkart_Sales_Dashboard.pbix
│   ├── flipkart_com-ecommerce_sample.csv
│   └── flipkart_com-ecommerce_sample.zip
│
├── 📊 Myntra/
│   ├── Myntra_Sales_Analysis_Dashboard.pbix
│   └── Myntra_dataset.xlsx
│
├── 📊 Zepto/
│   ├── Zepto_Dashboard.pbix
│   ├── Zepto_Grocery_Data.xlsx
│   └── Zepto_Grocery_Data.csv
│
├── 📊 Blinkit/
│   ├── Blinkit_Dashboard.pbix
│   └── BlinkIT_Grocery_Data.xlsx
│
└── README.md
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard design & publishing |
| **DAX** | Measures — Total Sales, Avg Sales, Profit, Ratings |
| **Power Query (M)** | Data cleaning & transformation |
| **Excel / CSV** | Raw data sources |

---
---

## 🟡 1. Flipkart Sales Dashboard

### 📸 Overview
An e-commerce sales analysis dashboard for Flipkart covering product categories, payment methods, regional sales distribution, and customer ratings.

### 📋 Dataset

| Property | Details |
|---|---|
| **File** | `flipkart_com-ecommerce_sample.csv` |
| **Total Records** | 20,000 products |
| **Total Columns** | 15 |

#### Columns

| Column | Description |
|---|---|
| `uniq_id` | Unique product ID |
| `product_name` | Name of the product |
| `product_category_tree` | Full category hierarchy |
| `retail_price` | Original price |
| `discounted_price` | Discounted selling price |
| `product_rating` | Individual product rating |
| `overall_rating` | Overall rating |
| `brand` | Product brand |
| `is_FK_Advantage_product` | Flipkart Advantage flag |
| `product_specifications` | Technical specs |

### 📊 KPI Cards

| Metric | Value |
|---|---|
| 💰 Total Sales | 10M |
| 📦 Avg Sales | 10.1K |
| ⭐ Avg Rating | 3.02 |
| 🛒 Quantity Sold | 5K |

### 📈 Visuals

| Visual | Description |
|---|---|
| 🗺️ Sales by Region Map | Geographic sales distribution across India |
| 📊 Top Product Categories | Grocery, Electronics, Home Décor, Fashion, Beauty, Books, Toys & Baby |
| 📉 Sales Trend Over Time | Jan 2023 – Jan 2024 monthly trend (peak: 0.68M) |
| 🍩 Payment Method Analysis | COD 21.81% · Debit Card 22.59% · UPI 19.15% · Credit Card 19.12% · Net Banking 17.33% |
| 📊 Qty Sold by Category | Grocery (819) · Electronics (725) · Fashion (716) |
| 📊 Sales by Rating | Performance distribution across 1–5 star ratings |
| 📊 Region × Payment Breakdown | South / North / Central / East vs all payment modes |

### 🔽 Slicers
- **Payment Method:** COD · Credit Card · Debit Card · Net Banking · UPI

---
---

## 🟠 2. Myntra Sales Analysis Dashboard

### 📋 Dataset

| Property | Details |
|---|---|
| **File** | `Myntra_dataset.xlsx` |
| **Total Records** | 3,071 products |
| **Total Columns** | 8 |

#### Columns

| Column | Description |
|---|---|
| `Product ID` | Unique product ID |
| `Category` | Women / Men / Beauty / Kids |
| `Sub-category` | Footwear, Topwear, Bottomwear, etc. |
| `Product Name` | Product title |
| `Brand Name` | Brand (H&M, Puma, Roadster, etc.) |
| `Size` | Product size |
| `Color` | Product color |
| `Ratings` | Customer rating |

### 📊 KPI Cards

| Metric | Value |
|---|---|
| 📦 Total Orders | 4K |
| 💰 Total Sales | 1.88M |
| 📦 Avg Sales | 536.88 |
| 💵 Total Revenue | 3M |
| 🏷️ Avg Discount | 35.51% |
| 🗂️ Total Products | 40 |

### 📈 Visuals

| Visual | Description |
|---|---|
| 📊 Total Sales by Discount | Monthly combo — bar (sales) + line (discount %) |
| 📊 Total Revenue by Brand | Puma · H&M · Roadster · Here&Now · Adidas |
| 📊 Brand Distribution | Count of products per brand |
| 📉 Sales by Days | Weekly trend across Beauty / Kids / Men / Women |
| 📊 Sales by Category (Year) | 2021–2023 stacked area — category-wise trend |
| 📊 Sales Revenue by State | State-wise revenue breakdown |
| 🍩 Product by Category | Women 32.33% · Men 32.2% · Beauty 20.19% · Kids 15.27% |
| 📊 Product Distribution by Sales | Jeans (310) · Shorts (260) · Shirts (147) · T-Shirts (142) |
| 📋 Brand Summary Table | Avg Discount · Avg Sales · Total Orders · Total Sales per brand |

### 🔽 Slicers
- **Year:** 2021 · 2022 · 2023
- **Category:** Beauty · Kids · Men · Women
- **Brand Name** dropdown
- **Sub-category** dropdown

### 🏆 Top Brands by Revenue
Puma · H&M · Roadster · Here&Now · Adidas · Allen Solly · Bata · Biba · Biotique

---
---

## 🟣 3. Zepto Grocery Dashboard

### 📋 Dataset

| Property | Details |
|---|---|
| **File** | `Zepto_Grocery_Data.csv` / `.xlsx` |
| **Total Records** | 8,523 items |
| **Total Columns** | 12 |

#### Columns

| Column | Description |
|---|---|
| `Item Identifier` | Unique item code |
| `Item Type` | Category (Fruits, Snacks, Dairy, etc.) |
| `Item Fat Content` | Low Fat / Regular |
| `Item Weight` | Weight of item |
| `Item Visibility` | Shelf visibility score |
| `Outlet Identifier` | Unique outlet code |
| `Outlet Establishment Year` | Year outlet was established (2012–2022) |
| `Outlet Size` | Small / Medium / High |
| `Outlet Location Type` | Tier 1 / Tier 2 / Tier 3 |
| `Outlet Type` | Grocery Store / Supermarket Type 1/2/3 |
| `Sales` | Item sales amount |
| `Rating` | Customer rating |

### 📊 KPI Cards

| Metric | Value |
|---|---|
| 💰 Total Sales | 1.20M |
| 📦 Avg Sales | 140.99 |
| ⭐ Avg Rating | 3.92 |
| 🗂️ No of Items | 9K |

### 📈 Visuals

| Visual | Description |
|---|---|
| 📉 Outlet Establishment Timeline | Sales trend 2012–2022 (peak: 205K in 2018) |
| 📊 Outlet Location (Treemap) | Tier 3: 0.47M · Tier 2: 0.39M · Tier 1: 0.34M |
| 📊 Total Sales by Item Type | Fruits & Veg (0.18M) · Snacks (0.18M) · Household (0.14M) |
| 🍩 Sales by Outlet Size | Medium 42.27% · Small 37.01% · High 20.72% |
| 📊 Outlet Location Type (Bar) | Tier 3: 472K · Tier 2: 393K · Tier 1: 336K |
| 📋 Outlet Type Summary Table | Total Sales · No of Items · Avg Sales · Avg Rating · Item Visibility |

### 🏪 Outlet Type Performance

| Outlet Type | Total Sales | No of Items | Avg Sales | Avg Rating |
|---|---|---|---|---|
| Supermarket Type1 | 787,549 | 5,577 | 141.21 | 3.92 |
| Grocery Store | 151,939 | 1,083 | 140.29 | 3.93 |
| Supermarket Type2 | 131,477 | 928 | 141.68 | 3.93 |
| Supermarket Type3 | 130,714 | 935 | 139.80 | 3.91 |

### 🔽 Filter Panel
- **Outlet Size** · **Outlet Location Type** · **Item Type**

---
---

## 🟡 4. Blinkit Grocery Dashboard

### 📋 Dataset

| Property | Details |
|---|---|
| **File** | `BlinkIT_Grocery_Data.xlsx` |
| **Total Records** | 8,523 items |
| **Total Columns** | 12 |

> Same schema as Zepto dataset — `Item Fat Content`, `Item Type`, `Outlet Establishment Year`, `Outlet Size`, `Outlet Location Type`, `Outlet Type`, `Sales`, `Rating`, etc.

### 📊 KPI Cards

| Metric | Value |
|---|---|
| 💰 Total Sales | ₹1.2M |
| 📦 Avg Sales | ₹140.99 |
| 🗂️ No of Items | 8.523K |
| ⭐ Avg Rating | 3.92 |

### 📈 Visuals

| Visual | Description |
|---|---|
| 🍩 Fat Content | Low Fat 64.13% · Regular 35.14% |
| 📊 Item Type Sales | Fruits & Veg ₹178.1K · Snacks ₹175.4K · Household ₹136K |
| 📊 Rating by Outlet Location | Low Fat vs Regular split across Tier 1/2/3 |
| 📉 Sales by Establishment Year | 2010–2022 trend (peak: ₹0.20M in 2018) |
| 🍩 Outlet Size | Medium ₹507.9K · Small ₹444.8K · High ₹249K |
| 📊 Outlet Location Type | Tier 3 ₹472.1K · Tier 2 ₹393.2K · Tier 1 ₹336.4K |
| 📋 Outlet Type Summary | Total Sales · Avg Sales · No of Items · Avg Rating · Item Visibility |

### 🏪 Outlet Type Performance

| Outlet Type | Total Sales | Avg Sales | No. of Items | Avg Rating |
|---|---|---|---|---|
| Supermarket Type1 | ₹787,549 | ₹141.21 | 5,577 | 3.92 |
| Grocery Store | ₹151,939 | ₹140.29 | 1,083 | 3.93 |
| Supermarket Type2 | ₹131,477 | ₹141.68 | 928 | 3.93 |
| Supermarket Type3 | ₹130,714 | ₹139.80 | 935 | 3.91 |

### 🔽 Filter Panel
- **Outlet Location Type** · **Outlet Size** · **Item Type**

---

## 🚀 How to Run

### Step 1 — Clone the Repository
```bash
git clone https://github.com/your-username/ecommerce-powerbi-dashboards.git
cd ecommerce-powerbi-dashboards
```

### Step 2 — Open Any Dashboard
- Open the `.pbix` file in **Power BI Desktop** (free from Microsoft)
- All visuals, slicers, and DAX measures load automatically

### Step 3 — Refresh Data (if needed)
- Go to **Home → Transform Data → Data Source Settings**
- Update the file path to your local copy of the CSV/Excel file

### Step 4 — Explore & Filter
- Use slicers (Year, Category, Payment Method, Outlet Type, etc.)
- Click on any chart element to cross-filter the entire dashboard

---

## 🔍 Key Insights

### 🟡 Flipkart
- **Grocery** is the top-selling category, closely followed by Electronics
- **Debit Card** is the most preferred payment method (22.59%)
- Sales peaked in **Jan 2024** at 0.68M and dropped sharply after

### 🟠 Myntra
- **Puma** leads in total revenue among all brands
- **Jeans** is the highest-selling sub-category (310 units)
- Sales peaked in **2021** and declined by 2023 — reflecting post-COVID trend
- **Average discount of 35.51%** is consistent across brands

### 🟣 Zepto
- **Tier 3 cities** contribute the most sales (₹472K) — growth market potential
- **Fruits & Vegetables** and **Snack Foods** are the top item types
- **Supermarket Type1** dominates with 5,577 items and ₹787K in sales
- Outlet establishment peaked in **2018** with ₹205K in sales

### 🟡 Blinkit
- **64.13%** of items are Low Fat — health-conscious product mix
- **₹1.2M** total sales with consistent ₹140.99 average per item
- **Tier 3** cities lead with ₹472.1K, same as Zepto — indicating underserved markets
- Sales trend mirrors Zepto — peak in 2018, stable post-2020
