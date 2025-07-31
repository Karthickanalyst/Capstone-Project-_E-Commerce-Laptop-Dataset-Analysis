# Laptop E-Commerce Analysis

A complete end-to-end data analytics project using Python, MySQL, and Power BI to analyze laptop listings from Amazon. This project explores laptop pricing, specifications, and customer ratings using web scraping, data cleaning, statistical methods, and interactive dashboarding.

---

## 📌 Project Overview
This project focuses on extracting product data from Amazon (via SerpAPI), performing exploratory and statistical analysis, and visualizing trends and patterns using Power BI. It helps identify brand trends, price ranges, popular specs, and market segmentation.

**Tools & Technologies:**
- Python (Pandas, Seaborn, Matplotlib, NumPy)
- Web Scraping (SerpAPI)
- MySQL (mysql-connector-python)
- Power BI

---

## 🔍 Features
- ✅ Scrapes product data (Price, Brand, Rating, Processor, RAM, etc.)
- ✅ Handles cleaning: missing values, invalid brands, RAM/Processor normalization
- ✅ Performs Exploratory Data Analysis (EDA) with visual insights
- ✅ Conducts correlation analysis and hypothesis testing
- ✅ Stores cleaned data into a structured MySQL database
- ✅ Builds an interactive Power BI dashboard with filters, slicers & KPIs

---

## 📁 Project Structure
```
├── notebooks/
│   └── laptop_data_analysis.ipynb     # Jupyter Notebook with full workflow
├── sql_scripts/
│   └── create_laptop_table.sql        # SQL table schema
│   └── import_data_script.sql         # Data import example
├── powerbi_dashboard/
│   └── Laptop_ECommerce_Dashboard.pbix
│   └── screenshots/
│       └── dashboard_view_1.png
│       └── dashboard_view_2.png
├── assets/
│   └── amazon_notebook_data_pages1to10.csv
│   └── visuals/
│       └── price_distribution.png
│       └── rating_by_brand.png
```

---

## 📊 Key Insights
- **RAM vs Price:** Higher RAM → Higher price trend
- **Brand Popularity:** HP, Lenovo, Dell dominate product listings and reviews
- **Processor Type:** Intel i5/i7 and Ryzen 5 dominate; i9 and M2 priced higher
- **Rating Trends:** High-rated laptops aren't always expensive
- **Unknown Data:** A large number of products had missing or ambiguous brand/processor details

---

## 🧪 Statistical & EDA Highlights
- Price distributions and outliers visualized with boxplots
- Correlation matrix for price, rating, reviews
- Hypothesis testing between RAM and Price
- Brand-wise pricing, rating, and popularity analysis

---

## 🗃️ Database Integration
- Cleaned data inserted into a MySQL table
- Table schema supports normalization for brand, specs, and identifiers
- Enables further queries and BI tool connectivity

---

## 📈 Power BI Dashboard
- KPIs: Avg Price, Avg Rating, Product Count
- Visuals: Bar, Donut, Line, and Scatter Plots
- Filters: Brand, Price Range, Ratings, Processor
- Bookmarks and buttons used to switch between views

---

## 🚀 Future Enhancements
- Add customer sentiment analysis using review text
- Forecast top-performing specs using machine learning
- Automate daily data update pipeline

---

## 📄 License
MIT License. For educational and non-commercial use only.

---

## 👤 Author
**Karthick**  
Data Analyst | Chemist  
[GitHub](https://github.com/Karthickanalyst)

---

