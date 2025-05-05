# **Ecommerce Sales Analysis**

### **Data Model** 
![](https://github.com/worksakshi/Ecommerce-Sales-Analysis-PowerBI-Dashboard/blob/main/Data%20Model%20View.PNG)

---

## **Objective**  
Designed an interactive and scalable dashboard to track and analyze sales performance, product-level trends, and retailer contributions across regions and years for Pepsi’s U.S. operations. The dashboard supports data-driven decision-making by offering insights into revenue growth, brand-wise sales variance, and quarterly profit margins.

---

## **Action**  

### **Key Features**   
- **Interactive Filters**: Used Excel slicers for Region and Year to allow users to explore KPIs dynamically.
- **Variance Analysis**: Highlighted YoY growth with calculated variances for both brands and retailers, using conditional formatting for quick visual cues.
- **Dynamic KPI Cards**: Displayed Total Sales, Units Sold, Average Price, and Total Operating Profit with real-time updates based on selected filters.
- **Quarterly Trend Visualization**: Created a combo chart to show quarterly sales trends alongside operating profit margin percentages.

### **Technology Stack**  
- **Tools Used**: Microsoft Excel, Pivot Tables, Pivot Charts, Slicers, Conditional Formatting, Named Ranges
- **Data Sourc**: Excel Sheets.  

### **Execution Steps**  

1. **Data Modeling**: Built a star schema with factEcommerce as the central table, ensuring referential integrity through one-to-many relationships.
2. **Data Cleaning & Transformation**: Cleaned data using Power Query, standardized naming, and ensured data types and keys were consistent.
3. **Visualization**: Developed multi-page reports with performance metrics, including maps for regional analysis and charts for payment trends.
4. **Image Mapping**: Merged product and country flag images using Product ID and Country as keys, allowing for enriched visuals.
5. **Time Intelligence**: Used the Calendar table to support YoY and MoM growth analysis.
6. **User Experience Design**: Included bookmarks for better usability.
