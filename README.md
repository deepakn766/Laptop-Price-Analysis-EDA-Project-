💻 Laptop Price Analysis — Exploratory Data Analysis (EDA) Project
📊 Objective

This project analyzes a dataset of laptops from various brands to understand how specifications like RAM, processor, generation, weight, and storage influence pricing and discounts in the e-commerce market.

🧠 Key Skills Demonstrated

Python (Pandas, NumPy, Matplotlib, Seaborn)
Data Cleaning and Preprocessing
Univariate, Bivariate, and Multivariate Analysis
Data Visualization and Insight Generation
Analytical storytelling for business understanding

<a href="">dataset


⚙️ Technologies Used
Tool / Library	Purpose
Python 3.x	Programming language
Pandas	Data cleaning & analysis
NumPy	Numerical operations
Matplotlib / Seaborn	Data visualization
Jupyter Notebook	Interactive environment
🧹 Data Cleaning & Preparation

Steps performed:
Loaded dataset using pandas.
Checked for nulls, duplicates, and inconsistent entries.
Standardized column names and formats.
Converted data types (numeric conversions for Price, Offer, etc.).
Created additional columns:
Price_In_Thousands
Price_Category
Processor_Brand
Processor_Types
Has_Offer

Removed outliers and missing data for clean visualizations.

🔍 Exploratory Data Analysis
1️⃣ Univariate Analysis

Most common laptop brands
Processor types and distributions
RAM & ROM frequency
Price and Offer distributions
Rating overview
(Visualized using countplots, histograms, boxplots)

2️⃣ Bivariate Analysis
RAM vs Price — Price increases with RAM size.
Processor Type vs Price — i7 / Ryzen 7 costlier than i3 / Ryzen 3.
Laptop Generation vs Offer — Older generations get more discounts.
ROM vs Price — Higher storage increases price.
Weight vs Price — Premium or gaming laptops weigh more.
Brand vs Offer — Lenovo and Acer provide higher discounts.

3️⃣ Multivariate Insights

Brand + Processor + RAM combinations influencing price.
Offers vs Value_for_Money vs Rating correlation.

📈 Key Insights

✅ HP, Dell, and Asus dominate mid-to-high price ranges.
✅ RAM and Processor Type are the strongest indicators of price.
✅ Offers are frequent for older models.
✅ 8GB RAM and 512GB SSD provide the best price-performance balance.
✅ AMD laptops generally have slightly higher discounts.
✅ Weight correlates with premium segment laptops.

💡 Final Conclusion

This analysis shows how laptop specifications and brand strategies shape pricing and offers in the market.

Businesses can use these insights to:
Identify best-selling configurations
Plan targeted promotions
Understand consumer preferences

For aspiring data analysts, this project strengthens:
Data cleaning & EDA
Visualization & storytelling
Business interpretation from raw data

