# Amazon Product Rating Tracker

## 📌 Overview
This project is a **Python-based Amazon product monitoring tool** that automatically extracts a product's title, price, and customer ratings from Amazon using **BeautifulSoup** and **Requests**.  
It saves the data in a CSV file daily and sends an **email alert** when the product rating meets a predefined condition.

---

## 🚀 Features
- **Web Scraping:** Extract product details (Title, Price, Ratings) from Amazon.
- **Automated Data Logging:** Appends daily data into a CSV file for historical tracking.
- **Email Notifications:** Sends alerts when ratings reach a specific threshold.
- **Scheduled Execution:** Runs automatically at set intervals using `time.sleep()`.

---

## 🛠️ Tech Stack
- **Language:** Python 3
- **Libraries:**
  - `BeautifulSoup4` – HTML parsing
  - `Requests` – Web requests
  - `Pandas` – Data reading and processing
  - `smtplib` – Sending email notifications
  - `csv` – Data storage

