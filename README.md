Here’s your README rewritten with a more lively, GitHub-friendly style using **emojis** and clearer formatting:

---

# 📊 **DSA-2040 Practical Exam – Cynthia Gathogo (745)**

## 🗂 **Section 1: Data Warehousing**

### ⭐ **Task 1: Star Schema Design**

**🗄 Fact Table:** `fact_sales`

* 📏 **Measures:** `sales_amount`, `quantity`
* 🔗 **Foreign Keys:** `customer_id`, `product_id`, `time_id`

**📊 Dimension Tables:**

* 👤 `dim_customer(customer_id, name, gender, age, location)`
* 📦 `dim_product(product_id, product_name, category, price)`
* ⏳ `dim_time(time_id, date, quarter, year)`

**💡 Why Star Schema over Snowflake:**
⭐ Star schema keeps dimensions **denormalized** → faster queries, easier joins, great for BI dashboards.
❄ Snowflake uses more joins → slightly less space, but slower queries.

---

### 📈 **Task 3: OLAP Queries – Insights**

* 🔼 **Roll-up:** Highest sales in 🇰🇪 Kenya & 🇺🇸 USA, especially in Q2 & Q3 (seasonal promos 🌸🎄).
* 🔍 **Drill-down:** Kenya peaks in festive months → good for 🎯 targeted marketing & 📦 stock planning.
* 🎯 **Slice:** Electronics dominate 📱💻 → suggests expansion potential.

> 📝 *Synthetic dataset shows trends but doesn’t exactly match real-world markets.*

---

## 🤖 **Section 2: Data Mining**

### 🔍 **Task 2: Clustering (K-Means)**

* 📌 **k=3** → ARI ≈ **0.73** ✅ strong alignment with true classes.
* 🌸 *Setosa* & *Virginica* clearly separated; *Versicolor* overlaps.
* 📉 **Elbow Method:** Optimal k = **3**.
* 🛒 **Real-world use:** Customer segmentation, sales trend grouping, classification without labels.

---

### 🧠 **Task 3: Classification & Association Rules**

**🪵 Decision Tree Classifier**

* 🎯 Accuracy: **\~100%** → perfect split for Iris dataset.

**📍 KNN (k=5)**

* 🎯 Accuracy: **96–98%** → strong but slightly less effective here.

**🔗 Example Association Rule:**

* `{bread} → {butter}` 🥖🧈 *(lift > 2)* → perfect for cross-selling & bundle discounts.

---

💬 **Final Note:**
This project blends **ETL pipelines**, **OLAP analysis**, **ML models**, and **market basket analysis** — the complete 🔄 data workflow from raw data to actionable insights 📊.


