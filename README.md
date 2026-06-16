# 📈 Extracting and Visualizing Stock Data

## Overview

This project demonstrates how to extract, clean, analyze, and visualize stock market data using Python. The analysis focuses on two popular companies:

- Tesla (TSLA)
- GameStop (GME)

The project utilizes **Yahoo Finance API**, **web scraping**, **Pandas**, and **Plotly** to collect, process, and visualize financial data.

This assignment was completed as part of the **IBM Data Science Professional Certificate**.

---

## 🎯 Objectives

- Extract historical stock data using `yfinance`
- Scrape company revenue data from web pages
- Clean and preprocess financial datasets
- Visualize stock prices and revenue trends
- Analyze the relationship between revenue growth and stock performance

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Analysis & Manipulation |
| yfinance | Stock Market Data Extraction |
| Requests | Downloading Web Content |
| BeautifulSoup4 | Web Scraping |
| Plotly | Interactive Data Visualization |
| Jupyter Notebook | Development Environment |

---

## 📂 Project Structure

```text
├── Final Assignment3.ipynb
└── README.md
```

---

## 📊 Data Sources

### Stock Price Data
Historical stock data is retrieved using the Yahoo Finance API through the `yfinance` package.

Companies analyzed:
- Tesla (TSLA)
- GameStop (GME)

### Revenue Data
Revenue information is extracted from publicly available financial web pages using web scraping techniques.

---

## 🔄 Project Workflow

### 1. Extract Tesla Stock Data
- Create a Tesla ticker object using `yfinance`
- Retrieve historical stock price data
- Store data in a Pandas DataFrame

### 2. Extract Tesla Revenue Data
- Download webpage content
- Parse HTML using BeautifulSoup
- Extract revenue tables
- Clean revenue values

### 3. Extract GameStop Stock Data
- Create a GameStop ticker object
- Retrieve stock history
- Convert data into a DataFrame

### 4. Extract GameStop Revenue Data
- Scrape quarterly revenue information
- Clean and organize the extracted data

### 5. Visualize Tesla Data
Generate interactive charts showing:
- Historical stock prices
- Revenue trends

### 6. Visualize GameStop Data
Generate interactive charts showing:
- Historical stock prices
- Revenue trends

---

## ✨ Features

- Historical stock data extraction
- Revenue data web scraping
- Data cleaning and preprocessing
- Interactive Plotly visualizations
- Financial trend analysis
- Reusable graph generation functions

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/stock-data-analysis.git
cd stock-data-analysis
```

Install dependencies:

```bash
pip install yfinance==0.1.67
pip install pandas
pip install requests
pip install beautifulsoup4
pip install plotly==5.3.1
```

Or install all dependencies at once:

```bash
pip install pandas yfinance requests beautifulsoup4 plotly
```

---

## ▶️ Usage

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Final Assignment3.ipynb
```

Run all notebook cells sequentially to:

1. Extract stock data
2. Scrape revenue data
3. Clean datasets
4. Generate visualizations

---

## 📈 Sample Analysis

The notebook creates interactive visualizations that compare:

### Tesla
- Stock price history
- Quarterly revenue growth

### GameStop
- Stock price history
- Quarterly revenue trends

These charts help identify potential relationships between company performance and stock market behavior.

---

## 🎓 Learning Outcomes

By completing this project, you will gain experience with:

- Financial data extraction
- API integration in Python
- Web scraping with BeautifulSoup
- Data cleaning using Pandas
- Interactive visualization with Plotly
- Exploratory financial data analysis

---

## 👨‍💻 Author

**Prabhat Pandey**

Electronics and Communication Engineering Student

---

## 🙏 Acknowledgments

- IBM Data Science Professional Certificate
- Cognitive Class
- Yahoo Finance
- Plotly
- Pandas Community

---

## 📜 License

This project is for educational purposes only.

Original assignment content © IBM Corporation.
