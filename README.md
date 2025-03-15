# 📊 Plant Co. Sales Dashboard – Power BI  

## 🔹 Overview  
This project is a **dynamic Power BI sales dashboard** for **Plant Co.**, designed to analyze **Sales, Quantity, and Gross Profit** across different regions, products, and time periods. The dashboard includes **YTD vs. PYTD comparisons, account profitability segmentation, and interactive filters** to support **data-driven business decisions**.  

## 📂 Dataset – **Plant_DTS**  
The dataset, **Plant_DTS**, is an **Excel file** containing three key sheets:  

- **Product_Fact** – Contains sales transaction details, including revenue, quantity, cost, and gross profit.  
- **Account** – Stores customer account details, linking sales to specific customers.  
- **Plant_Hierarchy** – Defines the company’s location-based hierarchy for analysis.  

After loading the dataset into Power BI, the tables were **renamed for better readability**:  
- `Product_Fact` → **Fact_Sales**  
- `Account` → **Dim_Accounts**  
- `Plant_Hierarchy` → **Dim_Product**  
- A **Dim_Date** table was also created for time intelligence calculations.  

📥 [[Download the dataset here](https://github.com/razamuhamadrazi/Plant-Co.-Report---Power-BI/blob/main/Plant_DTS.xls)]

## 📊 Key Features  
✅ **Dynamic Metric Selection** – Switch between Sales, Quantity, and Gross Profit using a slicer.  
✅ **Time-Based Analysis** – Compare **YTD vs. PYTD** performance for deep insights.  
✅ **Profitability Segmentation** – Identify high- and low-performing accounts using a **scatter plot (GP% vs. sales metrics)**.  
✅ **Bottom 20 Countries Analysis** – Track underperforming countries using a **Treemap visualization**.  
✅ **Advanced DAX Calculations** – Includes custom measures for revenue, profitability, and time comparisons.  

## 📈 Visualizations  
This dashboard includes the following **interactive visuals**:  

1️⃣ **Cards** – Displays YTD, PYTD, GP%, and YTD vs. PYTD % change.  
2️⃣ **Treemap** – Shows the **bottom 20 countries** based on YTD vs. PYTD.  
3️⃣ **Bar Chart** – **Compare YTD & PYTD** for Sales, Quantity, and Gross Profit across **Months, Countries, and Products**.  
4️⃣ **Stacked Line-Column Chart** – Shows **monthly trends** of YTD & PYTD for Sales, Quantity, and Gross Profit.  
5️⃣ **Scatter Plot** – **Account Profitability Segmentation** (GP% vs. Sales, Quantity, or Gross Profit).  

## 🛠 Technical Details  
- **Data Cleaning & Transformation** – Done in **Power Query** to remove duplicates and structure data.  
- **Custom DAX Measures** – Includes calculations for Sales, COGS, Gross Profit, YTD/PYTD, and dynamic metric selection using `SWITCH()`.  
- **Interactivity** – Implemented using **slicers, dynamic measures, and cross-filtering**.  

## 🚀 How to Use  
1️⃣ Download the dataset and open the Plant Co. Performance Report report.  
2️⃣ Use the **metric selector** to switch between Sales, Quantity, and Gross Profit.  
3️⃣ Adjust the **year slicer** to compare different time periods.  
4️⃣ Hover over visuals for **detailed tooltips and insights**.  

## 📌 Future Enhancements  
🔹 **Forecasting** – Implement predictive models for sales trends.  
🔹 **Drill-through Analysis** – Add detailed breakdowns for specific products/accounts.  
🔹 **More KPI Metrics** – Include MoM and QoQ growth insights.  

---

🔥 **If you find this project useful, don’t forget to ⭐ the repository!**  

