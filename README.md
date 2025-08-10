# FUTURE_DS_01
# FUTURE_DS_01 — Business Sales Dashboard

## 📌 Objective
Create an interactive Power BI dashboard to analyze e-commerce sales performance, identify top-selling products, seasonal sales patterns, and revenue by category/region.

## 📂 Files in this Repository
- **data/sales_clean.csv** → Cleaned sales dataset
- **powerbi/FUTURE_DS_01.pbix** → Power BI dashboard file
- **presentation/report_slides.pdf** → Slides with visuals & insights
- **images/** → Screenshots of the dashboard

## 🛠️ Tools & Technologies
- Power BI Desktop (Data modeling, DAX, visualization)
- Excel / Power Query (Data cleaning & transformation)
- GitHub (Version control & sharing)

## 🔄 Steps to Reproduce
1. Clone/download this repository.
2. Open `powerbi/FUTURE_DS_01.pbix` in Power BI Desktop.
3. Update the dataset source to point to `data/sales_clean.csv`.
4. Click **Refresh** to load the visuals.

## 📊 Data Preparation
- Removed duplicates & null values
- Standardized product/category names
- Extracted Year, Month, Month-Year from Order Date
- Created calculated columns for Revenue & Profit

## 📈 Key DAX Measures
- `Total Sales`
- `Total Units`
- `Total Orders`
- `Avg Order Value`
- `YoY Growth %`
- `Product Rank`
- `Sales % of Total`

## 💡 Key Insights
1. **Top 3 products** contributed ~40% of total revenue.
2. **Sales peak in November–December** (holiday season effect).
3. **Category X** drives high revenue but low margin → Pricing strategy review recommended.

## ✍️ Author
**Harshita Saini** — Future Interns, Data Science & Analytics Internship
