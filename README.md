Supermarket Sales Analysis (Python)
📌 Project Overview
This project analyzes supermarket transaction data to understand revenue distribution, customer behavior, category performance, and discount effectiveness across multiple cities. The objective is to identify growth opportunities, revenue risks, and inefficiencies in discounting strategy using data-driven insights.
The analysis is performed entirely in Python (Pandas, Matplotlib) and is structured to mirror how a real-world business or retail analytics team would approach decision-making.
🎯 Business Objectives
Identify top-performing cities and categories
Detect revenue concentration risk
Uncover white-space (untapped category) opportunities
Evaluate whether discounts increase basket value
Compare member vs normal customer behavior
Provide actionable insights for store-level strategy
🧩 Dataset Description
The dataset represents supermarket transactions and includes:
Invoice ID, Date, Time
City, Branch
Category, Product
Unit Price, Quantity
Discount Percentage
Customer Type (Member / Normal)
Payment Method
Net Sales, Gross Sales
Customer Rating
Note: This is a simulated dataset designed to resemble real supermarket transaction data.
🛠️ Tools & Technologies
Python
Pandas
Matplotlib
Google Colab
📊 Analysis Structure
Step 1–3: Data Understanding & Cleaning
Data inspection (head, info, isnull)
Feature engineering (dates, flags like has_discount)
Validation of sales metrics
Step 4–6: Core Performance Metrics
Total sales and average transaction value
City-wise and category-wise revenue
Customer type analysis (Member vs Normal)
Step 7: Basket Size & Transaction Behavior
Average transaction value by city
Member vs Normal spending patterns
Identification of cities with higher footfall but lower basket value
Step 8: Revenue Concentration & White Space
City × Category revenue contribution
Detection of category dependency risk
Identification of white-space categories (zero or near-zero contribution)
Key Insight:
Growth opportunities exist more in category expansion and visibility than in pushing existing high-performing categories.
Step 9: Discount Effectiveness Analysis
Comparison of discounted vs non-discounted transactions
Discount impact by:
Overall performance
City
Category
City × Category
Identification of margin-dilutive discounting
Key Insight:
Discounts currently:
Do not increase average basket value
Are applied inconsistently across cities and categories
Cannot be evaluated conclusively due to lack of standardization
🔍 Key Insights Summary
Bangalore and Mumbai show high revenue concentration in single categories.
Delhi has a more diversified category mix, reducing risk.
Multiple white-space categories exist across cities.
Discounting is not basket-accretive and appears margin-dilutive.
Membership programs are underutilized and do not currently drive higher spend.
📈 Business Recommendations (Based on Analysis)
Focus on category expansion and assortment visibility instead of aggressive discounting.
Standardize discount experiments across cities and categories.
Use discounts selectively for testing, not blanket application.
Strengthen membership programs to improve engagement and basket size.
⚠️ Scope & Limitations
Margin data not available (analysis based on net sales only)
Discounts not applied uniformly across categories
Customer-level lifetime value not analyzed
These limitations are acknowledged and reflect real-world data constraints.
🚀 Future Enhancements
Margin and profitability analysis
Time-based trends (weekday vs weekend)
Customer segmentation and cohort analysis
Dashboarding using Power BI / Tableau
👤 Author
Reshma
Aspiring Data Analyst
Focused on business-oriented analytics and decision-making
