# Data-Analysis-and-Web-Scraping-with-Python

## 📄 Overview
This project demonstrates two key data science skills:
1. **Web Scraping** – Extracting tabular data from a live Wikipedia page.
2. **Data Analysis** – Cleaning, exploring, and visualizing corporate revenue data using pandas, Matplotlib, and Seaborn.

## 📁 Files Included

| File Name                   | Description |
|----------------------------|-------------|
| `web_scraping.ipynb`       | Scrapes data from [Wikipedia: Largest Companies in India](https://en.wikipedia.org/wiki/List_of_largest_companies_in_India) using `requests` and `BeautifulSoup`, and extracts the target HTML table. |
| `Analysis_using_Pandas.ipynb` | Loads and analyzes the dataset (CSV) of companies by revenue. Includes exploratory data analysis (EDA), summary statistics, and visualizations. |
| `companies_by_revenue.csv` | (Expected external file) CSV file containing revenue data, possibly used in the analysis notebook. |

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- requests
- BeautifulSoup

## 🚀 How to Run

1. Clone the repository or download the files.
2. Ensure all required Python packages are installed:
   ```bash
   pip install pandas matplotlib seaborn requests beautifulsoup4
   ```
3. Run `web_scraping.ipynb` to scrape the latest data (if required).
4. Run `Analysis_using_Pandas.ipynb` to perform data analysis.

## 📊 Analysis Highlights

- Summary statistics of top companies
- Revenue distribution
- Clean and structured data visualization


