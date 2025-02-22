# Flipkart TV Reviews and Ratings Analysis using Web Scraping

## Project Overview
This project analyzes Flipkart TV Reviews and Ratings using Exploratory Data Analysis (EDA). The dataset was collected through web scraping and includes attributes such as brand, screen size, OS, launch year, warranty, price, ratings, and customer reviews. The goal is to identify key factors influencing customer satisfaction and uncover trends in TV sales and ratings.

## Project Objectives
- Extract and analyze customer ratings and reviews to understand user satisfaction.
- Identify how pricing, brand, and screen size affect ratings.
- Explore trends in TV purchases based on features like OS, warranty, and launch year.
- Determine the relationship between discounts and customer ratings.
- Provide data-driven insights to help buyers make informed decisions.
- 
## Web Scraping Technology
To collect TV listings from Flipkart, I used:

**Python Libraries:**
**BeautifulSoup** – Extracted structured HTML content from Flipkart product pages.
**Selenium** – Automated page navigation and data extraction for dynamic content.
**Requests** – Retrieved HTML content efficiently.
  
## Data Storage:
Extracted data was stored in CSV format for further processing.
**Dataset Description**
The dataset consists of TV listings from Flipkart, with the following attributes:

Brand : The brand name of the TV.
Inches : Screen size of the TV in inches.
Scores : Average score rating given by customers.
Reviews : Total number of customer reviews for the TV.
Ratings : Total number of customer ratings for the TV.
OS : Operating system of the TV.
Launch Year : Year the TV model was released.
Warranty : Warranty period (in years) offered with the TV.
Selling Price : Current selling price of the TV.
Original Price: Original listed price of the TV before discounts.

## Process & Methodology
- Data Collection – Scraped Flipkart TV data using BeautifulSoup and Selenium.
- Data Cleaning – Removed duplicates, handled missing values, and formatted text.
- Exploratory Data Analysis (EDA) – Used Pandas, Matplotlib, and Seaborn to analyze patterns in ratings, reviews, pricing, and discounts.
- Insights Extraction – Identified top-rated brands, best-selling screen sizes, and the impact of price and discounts on reviews.

## 📈 Key Insights & Findings
- Higher-priced TVs do not always have the best ratings; mid-range TVs (₹20,000 - ₹40,000) receive higher customer satisfaction.
- Screen size matters – TVs between 43-55 inches have the most positive reviews.
- Discounts influence sales but not necessarily ratings – Customers may give lower ratings despite higher discounts due to expectations.
- Android TVs dominate – Smart TVs with Android OS have higher purchase rates and positive reviews.
- Warranty period impacts purchasing decisions – TVs with longer warranties tend to have better ratings and reviews.

## 🔚 Final Conclusion
This analysis helps identify the best-performing TV models based on real customer feedback. It provides insights into pricing strategies, discount effectiveness, and feature preferences. These findings can benefit TV manufacturers, retailers, and buyers in making informed decisions.

## 🚀 Technologies Used
- ***Web Scraping:*** BeautifulSoup, Selenium, Requests
- ***Data Processing:*** Pandas, NumPy
- ***Data Visualization:*** Matplotlib, Seaborn
- ***Jupyter Notebook:*** Analysis and visualization
- ***Excel/CSV:*** Data storage and processing
## 🏆 Future Improvements
- Perform Sentiment Analysis on customer reviews for deeper insights.
- Expand the dataset to include more TV brands and platforms.
- Use Machine Learning models to predict customer ratings based on TV features.
