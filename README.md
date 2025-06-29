# 📚 SAL_BW_Project - Book Data Analysis

## 📝 Overview
SAL_BW_Project is a comprehensive data analysis project focused on web scraping book data, storing it in a structured format, and performing exploratory data analysis (EDA). The project integrates web scraping, SQL querying, and data visualization techniques to derive meaningful insights from the dataset.

## 📂 Project Structure
```
SAL_BW_Project/
│── 📄 README.md               # Project documentation
│── 📂 data/                   # Contains raw and processed datasets
│   │── 📄 Books_Details.csv    # Scraped book data
│── 📂 notebooks/              # Jupyter notebooks for analysis
│   │── 📄 web_scraping.ipynb   # Web scraping script using BeautifulSoup
│   │── 📄 EDA.ipynb            # Exploratory Data Analysis notebook
│   │── 📄 sql_queries.ipynb    # SQL queries for extracting insights
```

## 🌐 Web Scraping
The project involves scraping book data from [Books to Scrape](http://books.toscrape.com/) using **BeautifulSoup**. The script extracts relevant details such as:
- **Title** 📖
- **Price** 💲
- **Availability** ✅
- **Rating** ⭐

Scraped data is stored in a CSV file for further processing and analysis.

## 🗄️ Data Storage & Processing
The raw book data is cleaned and structured for analysis. The **Books_Details.csv** file is generated after handling missing values, correcting formats, and removing inconsistencies.

## 🛠️ SQL Queries
The project utilizes MySQL to query and analyze book data. Some key SQL operations include:
- Fetching the most expensive books.
- Identifying the highest-rated books.
- Analyzing price distributions based on ratings.

## 📊 Exploratory Data Analysis (EDA)
Using **Pandas, Matplotlib, and Seaborn**, the project performs in-depth analysis, including:
- Price distribution visualization.
- Rating trends.
- Stock availability insights.

## 📌 Key Features
✔️ Automated book data scraping
✔️ Structured data storage and SQL querying
✔️ Data visualization for better insights
✔️ Clean and maintainable code structure

## 🔧 Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Anas-Zaki/SAL_BW_Project.git
   cd SAL_BW_Project
   ```
2. **Perform EDA and Visualization in Jupyter Notebook**

## 🚀 Future Improvements
- Extend analysis with machine learning predictions.
- Enhance the web app with interactive visualizations.
- Implement real-time book price tracking.

## 📜 License
This project is open-source and available for modification and distribution.

---

📩 **Contributions & Feedback**
Feel free to fork the repository, submit issues, or suggest improvements!

Happy Coding! 🚀
