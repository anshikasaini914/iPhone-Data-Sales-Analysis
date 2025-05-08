# iPhone-Data-Sales-Analysis
Flipkart iPhone Price Analysis - README 📌 Project Overview This project analyzes iPhone pricing data scraped from Flipkart, comparing the most and least expensive models to understand pricing trends, discounts, and customer preferences.

📊 Key Findings

Price Comparison Metric Most Expensive (iPhone 12 Pro) Least Expensive (iPhone SE) Sale Price ₹140,900 ₹29,999 MRP ₹149,900 ₹39,900 Discount % 6% 24% Price Difference ₹110,901 (4.7x cheaper)
Popularity & Reviews Metric iPhone 12 Pro iPhone SE Ratings 542 95,807 Reviews 42 8,154 Star Rating ⭐⭐⭐⭐✨ (4.5) ⭐⭐⭐⭐✨ (4.5)
Specifications Feature iPhone 12 Pro iPhone SE Storage 512 GB 64 GB RAM 4 GB 2 GB Color Silver White 🔍 Insights Discount Strategy:
The budget-friendly iPhone SE has a 24% discount, while the premium iPhone 12 Pro has only 6% off.

Flipkart likely uses higher discounts on older/entry models to boost sales.

Demand Difference:

The iPhone SE has 95K+ ratings vs. just 542 for the 12 Pro, suggesting higher demand for affordable models.

Price-Performance:

The 12 Pro costs 4.7x more but offers 8x storage (512GB vs 64GB) and 2x RAM (4GB vs 2GB).

📈 Business Implications For Consumers:

Best value: iPhone SE (24% discount, high ratings).

Best specs: iPhone 12 Pro (premium storage/RAM).

For Sellers:

Promote discounts on older models to clear inventory.

Highlight storage/RAM for premium models to justify pricing.

🛠️ How to Reproduce Data Source:

Scraped from Flipkart iPhone listings.

Tools Used:

Python (pandas, BeautifulSoup), Jupyter Notebook.

Code:

python import pandas as pd df = pd.read_csv("flipkart_iphones.csv") print(df[df['Sale Price'] == df['Sale Price'].max()]) # Most expensive print(df[df['Sale Price'] == df['Sale Price'].min()]) # Least expensive 📂 Files flipkart_iphones.csv: Raw dataset.

iphone_price_analysis.ipynb: Jupyter Notebook with full analysis.
