#  Product Recommendation & Return Prediction System using Online Retail Dataset

This project is built using the **Online Retail dataset (3600+ records)** to explore concepts in data mining and create a simple **product recommendation** and **return prediction system**.
---

##  Dataset Attributes
- `InvoiceNo`: Invoice number (unique ID)
- `InvoiceDate`: Date of invoice
- `Description`: Product description
- `StockCode`: Product code
- `Quantity`: Quantity purchased
- `UnitPrice`: Price per item
- `CustomerID`: Unique ID per customer
- `Country`: Country of transaction

---

## Techniques Used


- **Data Cleaning**: Handled missing values and duplicates
- **Data Transformation**: Added month field, normalized case
- **Visualization**:
  - Bar chart of top-selling products
  - Monthly sales trends
  - Product purchase patterns using histograms
- **Market Basket Analysis** using the **FP-Growth Algorithm** for efficient mining of frequent itemsets
- **Correlation Heatmap**: Visualized purchase patterns across top 20 products
- **Return Rate Prediction**: ML model classifies whether a product will be returned based on past sales behavior
- **User Input Functionality**: User can input a product `StockCode` or `Description` and get its real return rate based on historical dat
- Use KMeans to group similar customers based on purchase behavior
- Basic return prediction can help detect anomalies in purchasing behavior
- Example Use Cases:
  - Recommendation Systems
  - Financial Analytics for refund rate analysis
  - Inventory Planning

---

## 💻 Tech Stack
- **Python**
- **Pandas, NumPy** for preprocessing
- **Matplotlib, Seaborn** for visualization
- **Scikit-learn** for ML classification
- **mlxtend** for market basket analysis (FP-Growth)

---

