## 📘 Project Description: Book Price & Rating Analysis using Web Scraping<br>

This project demonstrates a complete data workflow using web scraping on an eCommerce-like site.<br>
We used [BooksToScrape.com](http://books.toscrape.com) to collect, clean, analyze, and visualize product data.<br>
It showcases a real-world scenario involving HTML scraping, data transformation, and exploratory insights.<br>

---

## 🧭 Step-by-Step Workflow<br>

### ✅ Step 1: Web Scraping<br>
- Scraped 50 pages of book listings (~1,000 books total)<br>
- Collected: title, price, rating, and availability<br>
- Used `requests` and `BeautifulSoup` to parse structured HTML content<br>

### ✅ Step 2: Data Cleaning<br>
- Converted price from string (e.g., `£53.74`) to numeric float<br>
- Mapped rating text (e.g., `"Three"`) to integers (1–5)<br>
- Transformed availability into a boolean field (in stock = True)<br>
- Checked for and confirmed absence of missing values<br>

### ✅ Step 3: Analysis<br>
- **Average Price of Books:** £35.07<br>
- **Most Frequent Ratings:** 3 and 4 stars<br>
- All books were in stock — limited inventory analysis<br>

### ✅ Step 4: Visualization<br>
- 📊 Rating count plot<br>
- 💰 Price distribution histogram<br>
- 📈 Boxplot of price by rating<br>
- Created using `matplotlib` and `seaborn`<br>

### ✅ Step 5: Final Reflection<br>
The project was an excellent exercise in real-world data handling.<br>
Web scraping was straightforward thanks to a clean HTML layout.<br>
I learned to clean structured product data and extract patterns.<br>
In future iterations, I would include categories or build an interactive dashboard.<br>

