 Supermarket Analytics & Customer Segmentation (Data Science Project)
📌 Project Overview
This project performs an end-to-end analytics and data science study on supermarket transaction data to derive business insights, customer behavior patterns, and strategic recommendations.
The analysis progresses from exploratory data analysis (EDA) to advanced customer segmentation using unsupervised learning, with a strong emphasis on business interpretability and decision-making, not just model output.
🎯 Business Objectives
Understand revenue drivers across cities, categories, and customer types
Identify high-value vs price-sensitive customers
Evaluate the impact of discounts on basket value
Assess whether category-level differentiation is required
Segment customers to support targeted promotions and loyalty strategies
🧩 Dataset Description
The dataset contains invoice-level supermarket transactions, including:
Invoice ID
Date & Time
City & Branch
Product Category
Unit Price & Quantity
Discount Percentage
Customer Type (Member / Normal)
Payment Method
Net Sales & Gross Sales
Customer Rating
Each row represents a single product purchase within an invoice.
📊 Analysis Workflow
1️⃣ Data Cleaning & Feature Engineering
Date/time parsing
Creation of derived metrics:
net_sales
has_discount
basket-level aggregations
Validation of missing values and data consistency
2️⃣ Exploratory Data Analysis (EDA)
Revenue analysis by:
City
Category
Customer type
Basket size and transaction value analysis
City-wise and category-wise performance comparison
Identification of white space and concentration risk
3️⃣ Discount Impact Analysis
Comparison of discounted vs non-discounted transactions
Category-wise and city-wise discount effectiveness
Insight:
Discounts were found to be margin-dilutive rather than basket-accretive
Discounted and non-discounted items often belonged to different categories, making direct comparison misleading
4️⃣ Customer Segmentation (Core Data Science Component)
Unit of analysis: Invoice level
Features used:
Total spend per invoice
Average spend
Basket size (item count)
Discount dependency
Techniques:
Feature scaling using StandardScaler
K-Means clustering
Elbow method for optimal cluster selection
PCA for visualization
Cluster profiling and business interpretation
Key Customer Segments Identified:
High-value customers (large baskets, low discount dependency)
Mid-value customers (moderate spend, responsive to promotions)
Promotion-driven customers (price-sensitive, smaller baskets)
5️⃣ Category Segmentation (Strategic Validation)
Attempted clustering at category level using revenue, basket, and discount behavior
Result:
Categories showed homogeneous behavior
No meaningful natural clusters formed
Interpretation:
Category-level differentiation does not provide incremental value
Strategy should focus on customer behavior and city-level demand
🧠 Key Business Insights
Revenue variation is driven more by customer behavior than by product categories
High-value customers contribute disproportionately and should be protected from excessive discounting
Uniform discount strategies are inefficient
Simplified category management combined with customer-led targeting is more effective
City-specific demand patterns are more actionable than category-specific strategies
🛠️ Tools & Technologies
Python
pandas, numpy
matplotlib
scikit-learn (KMeans, PCA, scaling)
Google Colab
📈 Skills Demonstrated
Exploratory Data Analysis (EDA)
Feature engineering
Unsupervised learning (K-Means)
Model validation (Elbow method, silhouette reasoning)
Business storytelling with data
Translating analytics into managerial recommendations
🧾 Final Takeaway
“This project demonstrates that effective retail analytics requires applying complexity where customer behavior varies and maintaining simplicity where product behavior is homogeneous.”
👤 About Me
I am a former software engineer (C programming background) transitioning into data science, with a strong focus on:
logical reasoning
debugging and validation
business-aligned analytics
I believe tools can generate code, but experience is required to judge correctness and insight quality.

