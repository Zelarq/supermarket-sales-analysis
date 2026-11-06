# 🛒 Supermarket Sales & Retail Performance Analysis

An Exploratory Data Analysis project investigating supermarket sales transactions, branch performance, customer demographics, and product profitability across retail store locations.

---

## 📌 Project Overview

Retail optimization requires a granular understanding of customer purchasing patterns, peak shopping periods, product line margins, and regional branch performance. This project analyzes historical transaction logs from a supermarket chain with branches in multiple cities to assess sales trends, membership spending habits, and payment preferences.

---

## 📊 Dataset Overview

The dataset (`supermarket.csv`) includes transaction-level attributes:

* **Invoice Details:** `Invoice ID`, `Date`, `Time`, `Payment` method (Cash, Credit card, Ewallet).
* **Branch & Location:** `Branch` (A, B, C), `City` (Yangon, Naypyitaw, Mandalay).
* **Customer Demographics:** `Customer type` (Member vs. Normal), `Gender`.
* **Merchandise & Economics:** `Product line` (Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel), `Unit price`, `Quantity`, `Tax 5%`, `Total`, `cogs` (Cost of Goods Sold), `gross margin percentage`, `gross income`.
* **Experience:** `Rating` (1 to 10 customer satisfaction score).

---

## 🔍 Key Findings & Retail Insights

1. **Branch Revenue Parity:**
   * All three supermarket branches (A, B, C) demonstrate consistent aggregate revenue generation, with minor variances attributable to regional product category preferences.

2. **Customer Membership Impact:**
   * Loyalty program Members generate higher repeat transaction frequency and exhibit slightly higher basket sizes compared to non-member shoppers.

3. **Payment Preferences:**
   * Payment transactions are evenly distributed across E-wallets, Cash, and Credit Cards, demonstrating that digital payment integration is equally adopted alongside cash transactions.

4. **Temporal Patterns & Peak Hours:**
   * Analysis of transaction timestamps identifies consistent sales velocity peaks during afternoon and early evening hours, providing actionable guidance for staffing and checkout lane optimization.

5. **Customer Rating Distribution:**
   * Customer ratings display a uniform distribution between 4.0 and 10.0, indicating overall stable customer satisfaction without major negative service clustering.

---

## 📈 Visualizations in the Notebook

* **Basket Value Distribution:** Boxplot analyzing transaction totals and upper spending thresholds.
* **Rating Frequencies:** Histograms tracking customer rating score distributions.
* **Payment Method Distribution:** Pie charts illustrating customer payment mode preferences.
* **Demographic Spending Breakdown:** Comparative bar plots of spending across customer types and genders.
* **Branch Comparison:** Aggregate revenue comparisons across retail branches.
* **Time-Series Sales Trajectory:** Visualizations of sales volume variations over time.
* **Correlation Heatmap:** Multi-variable correlation evaluating margins, costs, and transaction sizes.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`
* **Dataset:** `supermarket.csv`

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Zelarq/supermarket-sales-analysis.git
cd supermarket-sales-analysis
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook project3_supermarket.ipynb
```

---

## 👤 Author

* **Sayanth N K**
* GitHub: [@Zelarq](https://github.com/Zelarq)
* Email: [sayanthnk32@gmail.com](mailto:sayanthnk32@gmail.com)

