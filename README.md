# E-Commerce_sales_data_analysis
<b>Author= Pawan kumar</b>

This project performs Exploratory Data Analysis (EDA) on e-commerce sales dataset to uncover insights regarding sales revenue, product demand, and regional payment preferences.

---

## Project Overview
The goal of this project is to analyze transactional e-commerce data to understand key business metrics such as revenue per category, product sales volume, and customer payment behaviors across different global regions.

---

## Dataset Overview
The dataset (`ecommerce_sales_data.csv`) contains **220 order records** with the following features:

- `OrderID`: Unique order identifier
- `Date`: Transaction date
- `Category`: Product category (Electronics, Home & Kitchen, Clothing, Books, etc.)
- `Product`: Item purchased
- `UnitPrice`: Price per unit
- `Quantity`: Number of units purchased
- `TotalAmount`: Total order value (`UnitPrice` × `Quantity`)
- `PaymentMethod`: Payment type (Credit Card, PayPal, UPI, Debit Card)
- `Region`: Customer location (North America, Europe, Asia-Pacific, Latin America)
- `CustomerRating`: Feedback rating (1 to 5)

---

##  Tools & Libraries Used
- **Python** 
- **Pandas**: Data manipulation and aggregation
- **Matplotlib**: Basic charts and plotting
- **Seaborn**: Advanced statistical data visualisations

---

##  Key Findings & Insights
1. **Revenue & Volume Analysis**: Sales and quantities were aggregated by product categories to identify top-performing categories.
2. **Regional Payment Preference**:
   - Analyzed payment method preferences across **North America**, **Europe**, **Asia-Pacific**, and **Latin America**.
   - **Credit Card** is the most preferred payment method across almost all geographic regions.

---

##  How to Run
1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
