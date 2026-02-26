# Flower-Aura-Web-Scrapping-and-Sentiment-Analysis
🌸 FlowerAura Customer Sentiment Analysis Project 🌷 Scraped 500+ reviews using BeautifulSoup &amp; Selenium, performed data cleaning with Pandas, and applied NLP-based sentiment analysis using TextBlob. 📊 Identified 425 positive reviews, key strengths, weaknesses, and business insights to improve delivery, quality, and customer satisfaction. 🌹✨

🌸 FlowerAura Customer Sentiment Analysis Project 🌷
📌 Project Overview

This project focuses on Customer Sentiment Analysis of FlowerAura product reviews.
The objective is to understand customer opinions about flower delivery and gifting services using Web Scraping, Data Cleaning, NLP, and Data Visualization.

By analyzing real customer feedback, this project extracts meaningful business insights to improve customer satisfaction and service quality. 🌹

🚀 Project Workflow
1️⃣ Data Collection (Web Scraping)

Scraped 500+ product reviews

Extracted:

Username

City

Occasion

Posted Date

Rating (1–5 stars)

Review Text

Handled pagination (50 pages)

Tools Used:

BeautifulSoup

Requests

Pandas

2️⃣ Data Cleaning & Preprocessing 🧹

Removed duplicates (0 duplicates found)

Handled missing values (Occasion → filled with "Unknown")

Converted text to lowercase

Removed punctuation & special characters

Tokenization

Lemmatization (WordNetLemmatizer)

Tools:

Pandas

NLTK

3️⃣ Sentiment Analysis 🤖

Used TextBlob for:

Polarity (-1 to +1)

Subjectivity

Classification Rule:

Positive → Polarity ≥ 0.1

Negative → Polarity < 0.1

📊 Results:

✅ Positive Reviews: 425

❌ Negative Reviews: 75

4️⃣ Data Analysis & Visualization 📈

Performed:

Sentiment Distribution Analysis

Rating vs Polarity Correlation

Word Cloud for Positive Reviews

Review Length vs Sentiment Analysis

Correlation between Review Length & Sentiment Strength

📉 Correlation (Rating vs Polarity): -0.018
(Weak relationship)

Tools Used:

Matplotlib

Seaborn

WordCloud

📊 Key Insights 🌼

🌟 Majority of customers had positive experiences.
🚚 Delivery speed received strong appreciation.
📦 Some complaints related to:

Late deliveries

Quality mismatch

Customer support delays

📈 Opportunities:

Improve logistics & real-time tracking

Leverage positive delivery feedback in marketing

Enhance loyalty programs

🛠️ Tech Stack

Python

BeautifulSoup

Requests

Pandas

NumPy

NLTK

TextBlob

Matplotlib

Seaborn

WordCloud

📁 Dataset Information

Total Reviews: 500

Columns:

Names

Cities

Posted_On

Occasion

Ratings

Reviews

Lemmatized_Reviews

Polarity

Subjectivity

Sentiment

💡 Business Impact 🌹

This project demonstrates how raw customer reviews can be transformed into:

Actionable Business Insights

Customer Experience Improvements

Marketing Strategy Enhancements

Data-Driven Decision Making

📬 Contact

Shiva Kashyap
📧 shivakashyap1999@gmail.com
