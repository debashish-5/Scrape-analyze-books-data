# 📚 Book Store Data Scraping and Analysis (Python Project)

This project showcases a complete data pipeline using Python — from **web scraping** to **data cleaning** and **data visualization** — using book information from the open practice website [Books to Scrape](https://books.toscrape.com).

---

## 📌 Project Overview

🔍 **Goal:**  
To collect data about books (title, price, rating) from multiple pages, clean the data using `pandas`, and generate insights using `matplotlib` and `seaborn`.

🎯 **Steps Covered:**
- Scrape HTML data from all 50 pages
- Extract structured data from each page
- Convert and clean messy values (like star ratings)
- Categorize prices into `Low`, `Medium`, `High`
- Visualize data trends and relationships

---

## 🗂️ Repository Structure

| File | Purpose |
|------|---------|
| `01_Requests.ipynb` | Scrapes and stores HTML pages from the website |
| `02_Beautifulsoup.ipynb` | Parses and processes book data, cleans it, and visualizes it |
| `Page1.csv` | Sample data for testing scraping logic on a single page |
| `Allpage.csv` | Final cleaned dataset of all 1000 books scraped |

> 🛑 **Note:** The raw HTML files are stored locally but **not uploaded** to GitHub to keep the repo safe and clean.

---

## 📊 Data Visualizations

Visualizations generated using `matplotlib` and `seaborn`:
- 📈 Bar charts (price vs rating, rating vs category)
- 🟪 Stack plots (price with rank)
- 🌟 Scatter plots (price vs rating with rating as star)
- 🧩 Subplots (e.g., price vs rating, price vs rank)
- 📊 Hue-based category comparisons with seaborn

---

## ⚠️ Ethical Use & Safety

> ✅ **This project is for learning and academic purposes only.**  
> Data is scraped from `https://books.toscrape.com`, a public sandbox website built specifically for scraping practice.  
> ❌ No copyrighted, private, or sensitive data is collected.  
> 📁 The HTML folder is kept private and not shared on GitHub to avoid confusion or misuse.

---

## 🧠 Skills Demonstrated

- Python scripting and automation
- Web scraping using `requests` and `BeautifulSoup`
- Data processing and cleaning using `pandas`
- Data visualization using `matplotlib` and `seaborn`
- File and CSV handling
- GitHub version control and documentation

---

## 👨‍💻 Author

**Debashish Parida**  
B.Tech CSE | Python and Data Science Enthusiast  
📫 Connect on [LinkedIn](https://www.linkedin.com/in/debashish-parida-a260b1355)

---

## 📝 License

This project is open-source and free to use for learning and educational purposes.
