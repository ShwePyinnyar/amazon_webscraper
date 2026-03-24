# 🛒 Amazon Price Tracker (Web Scraping Project)

## 📌 Project Overview
This project tracks the price of a product on Amazon over time. It scrapes the product title and price, stores the data in a CSV file, and updates it daily to monitor price changes.

---

## 🛠️ Tools & Libraries Used
- BeautifulSoup (bs4) → HTML parsing  
- requests → Sending HTTP requests  
- pandas → Data handling and analysis  
- time → Scheduling repeated execution  
- datetime → Recording dates  
- csv → Writing data to CSV files  

---

## 🌐 Data Source
Amazon product page (Samsung Galaxy Tab)

---

## 📈 Key Features
- Extracts product title and price from Amazon  
- Cleans and formats scraped data  
- Stores data in CSV format  
- Appends new data daily  
- Tracks historical price changes over time  

---

## 🔁 Automation
- Uses an infinite loop (`while True`)  
- Runs the scraper every 24 hours (`86400 seconds`)  

---

## ⚠️ Challenges & Notes
- Amazon may block requests (anti-bot protection)  
- Requires proper headers to mimic a browser  
- HTML structure may change over time  
- Price class names may vary  

---

## ✅ Conclusion
This project demonstrates a real-world use case of web scraping by tracking product prices over time. It combines data extraction, storage, and automation, forming a strong foundation for building more advanced data pipelines and monitoring systems.
