# 🛒 Supermarket Sales Analysis — Capstone Project
---

### 📘 Project Overview
This project analyzes supermarket sales data from three branches to uncover key business insights.  
Using **Python (Pandas, NumPy, Matplotlib, Seaborn)**, the dataset was cleaned, transformed, and visualized to explore:  
- Product line performance  
- Branch comparison  
- Payment method preferences  
- Customer satisfaction  
- Time-based sales trends  

📅 **Dataset Period:** January – March 2019  
📊 **Dataset Size:** 1,006 rows × 16 columns (cleaned to 1,001 × 22)

---

### 🎯 Objectives
- Clean and prepare raw sales data for analysis.  
- Explore trends across products, branches, and payment types.  
- Visualize customer behavior and peak shopping hours.  
- Generate actionable business insights and recommendations.

---

### 🧰 Tools & Libraries
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Google Colab** for notebook execution  
- **Excel / Power Query** for initial review  
- **PDF Reports** for business and technical documentation  

---

### ⚙️ Data Wrangling Summary
From the **Data Wrangling Report**:
- Trimmed and standardized column names.  
- Converted numeric and date columns properly.  
- Imputed missing `Tax`, `Total`, and `Hour` values.  
- Created `Total_Calc`, `Year`, `Month`, `Day`, and `Day_Period` columns.  
- Final dataset: **1,001 rows × 22 columns**, 0 missing values.  

---

### 📊 Key Insights (From Business Insights Report)
| Area | Key Findings |
|------|---------------|
| 🏷 **Product Lines** | *Food & Beverages* had the highest total sales (~53.7K). |
| 🏢 **Branches** | Branch **C** led sales (~106K), slightly ahead of A & B. |
| 💳 **Payments** | **E-Wallet** was the top payment method (~35% of transactions). |
| ⭐ **Customer Ratings** | Fairly consistent, with minor variations between branches. |
| ⏰ **Peak Hours** | Highest sales occur around **12 PM** and **6–7 PM**. |

---

### 💡 Business Recommendations
- **Stock Planning:** Focus on *Food & Beverages* and *Sports & Travel* categories.  
- **Branch Strategy:** Allocate slightly more inventory to Branch **C**.  
- **Promotions:** Schedule marketing during **4–7 PM**; offer **E-Wallet discounts**.  
- **Service Quality:** Review customer feedback in lower-performing branches.

---

### 📈 Visual Highlights
The notebook includes:
- Bar charts for product and branch analysis  
- Donut chart for payment distribution  
- Boxplot for customer ratings  
- Line charts for daily and hourly sales trends  

---

### 📂 Project Files
| File | Description |
|------|--------------|
| `Capstone Data - Supermarket Sales-Project(Mahmoud Abdellateif).ipynb` | Main Colab notebook (data cleaning + visualization). |
| `Data Wrangling Report.pdf` | Technical data preprocessing documentation. |
| `Business Insights Report.pdf` | Key findings and business recommendations. |

---

### 🚀 Future Work
- Automate report generation using Python scripts.  
- Build an interactive **Tableau / Power BI dashboard** for management review.  
- Integrate predictive models for sales forecasting.
