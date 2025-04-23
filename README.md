# Sales_Customer_Insights_Report
A Power BI project analyzing customer behavior, purchase patterns, and retention strategy effectiveness using a synthetic sales dataset. Includes insights on customer lifetime value (LTV), churn probability, and seasonal trends to support data-driven sales and marketing decisions.  

**Key objectives:**  
-Identify high-value customer segments based on Lifetime Value (LTV)

-Evaluate the impact of retention strategies on churn probability

-Analyze purchasing behavior across time, regions, and product categories

-Recommend data-driven actions to improve retention and campaign performance  

---

##  Data Sources  

| Field | Description |
|-------|-------------|
| `Customer_ID` | Unique customer identifier |
| `Product_ID` | Unique product identifier |
| `Transaction_ID` | Unique transaction identifier |
| `Purchase_Frequency` | Total number of purchases by the customer |
| `Average_Order_Value` | Average transaction value per customer |
| `Most_Frequent_Category` | Product category purchased most often |
| `Time_Between_Purchases` | Days between purchases |
| `Region` | Customer region |
| `Churn_Probability` | Probability of the customer churning |
| `Lifetime_Value` | Predicted customer revenue over their lifetime |
| `Launch_Date` | Product release date |
| `Peak_Sales_Date` | Date when product sales peaked |
| `Season` | Season associated with peak sales |
| `Preferred_Purchase_Times` | Time of day the customer prefers to buy |
| `Retention_Strategy` | Strategy used to retain the customer |

### Data-Cleaning Steps  
- Removed missing or duplicate rows  
- Standardized column types (dates, numbers, text)  
- Created new calculated columns in Excel (e.g., Estimated CLV, Retention Effectiveness Indicator)  
- Normalized purchase frequency for comparison  
- Transformed and visualized using Power BI  

📂 Dataset Source: [Kaggle - Sales and Customer Insights Dataset](https://www.kaggle.com/datasets/imranalishahh/sales-and-customer-insights/data)

---

##  Results and Visuals

### 🔹 Key Insights
- **Europe and Electronics** contributed the most to overall customer value.
- **Customers with high frequency and high AOV** have the highest LTV.
- **Churn probability increases sharply after 36 days** without purchase.
- **Email Campaigns drive high LTV but also the highest churn** — suggesting the need for improved targeting.
- **Seasonal trends reveal October and Summer as peak sales periods**, especially in the **Evening**.
- Retention strategy performance is mostly classified as **Needs Improvement** or **At Risk**.

###  Sample Visuals

#### Overview Dashboard  
![Screenshot (34)](https://github.com/user-attachments/assets/212aa003-eeb8-4ce7-90be-6ea5e9399bf0)


#### Churn vs Time Between Purchases  
![Screenshot (36)](https://github.com/user-attachments/assets/55d67108-3676-4528-b091-3a534615683f)


#### Retention Strategy Effectiveness  
![Screenshot (37)](https://github.com/user-attachments/assets/716eec22-5276-47c5-9e4b-51a2deef202d)


#### Seasonal Purchase Behavior  
![Screenshot (38)](https://github.com/user-attachments/assets/be2be20c-e2ff-4757-a791-f72f812f4001)


---

##  Acknowledgments  

Special thanks to:  
- **Imran Ali Shah** for publishing the dataset on Kaggle  
- **Power BI** for providing the analytics tools  
- **ChatGPT** (OpenAI) for guidance on structuring the analysis and summary  

---

## 📁 Files Included  
- `Sales&CustomerInsights.pbix` – Power BI Report  
- `Sales&CustomerInsights.pdf` – Report Visuals  
- `Executive Summary.pdf` – Key Business Insights
- `SALES AND CUSTOMER INSIGHTS REPORT.ppt`-Presentation Report
- `README.md` – This documentation file  
