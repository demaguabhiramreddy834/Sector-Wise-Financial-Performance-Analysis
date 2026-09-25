# 📊 Stock Market Exploratory Data Analysis (EDA)
## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA) on Indian stock market data** collected from **Screener.in**. The project uses web scraping to collect company-wise financial information across different sectors and analyzes important financial metrics such as Market Capitalization, P/E Ratio, ROCE, Dividend Yield, Quarterly Sales Growth, and Quarterly Profit Growth.

The goal is to understand sector-wise and company-wise financial patterns through data cleaning, statistical analysis, and visualizations.

## 🎯 Objectives
* Scrape stock market data from Screener.in.
* Collect company financial information across multiple sectors.
* Clean and preprocess the collected dataset.
* Handle missing values using sector-wise median imputation.
* Perform descriptive statistical analysis.
* Perform inferential statistical analysis.
* Analyze relationships between financial variables.
* Identify companies and sectors with different financial characteristics.
* Create meaningful visualizations for business insights.

## 🛠️ Technologies & Libraries
* **Python**
* **Pandas**
* **NumPy**
* **Requests**
* **BeautifulSoup**
* **LXML**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook / Google Colab**

## 🌐 Data Collection
The project uses **web scraping** to collect financial data from:
**Screener.in – Market/Sector data**
The `Requests` library is used to send HTTP requests, while `BeautifulSoup` and `LXML` are used to extract structured information from the webpages.
The collected data includes:
* Company
* Sector
* P/E Ratio
* Market Capitalization
* Dividend Yield
* Quarterly Profit Variation
* Quarterly Sales Variation
* ROCE
The scraped dataset is saved as:
`Cleaned_Sector_Data.csv`

## 🧹 Data Cleaning
The dataset was examined for missing values and inconsistencies.
Missing values in important numerical columns were handled using **sector-wise median imputation**.
The following columns were processed:

* P/E
* Quarterly Profit Variation %
* Quarterly Sales
* Quarterly Sales Variation %
* ROCE %
Sector-wise median imputation was used so that missing values were replaced according to the financial characteristics of their respective sectors.

## 📈 Statistical Analysis
### Descriptive Statistics
Sector-wise statistics were calculated using:
* Mean
* Median
* Standard Deviation
The analysis was performed for important financial metrics such as:
* P/E
* Market Capitalization
* Dividend Yield
* Quarterly Profit Growth
* Quarterly Sales Growth
* ROCE

### Inferential Statistics
The project also includes inferential statistical analysis, including **Pearson correlation significance testing**, to examine relationships between financial variables.

## 📊 Exploratory Data Analysis
The project contains multiple visualizations, including:

### Company & Sector Analysis
* Top 20 sectors by number of companies
* Top 20 companies by market capitalization
* Top 20 companies by ROCE
* Top 20 companies by quarterly profit growth
* Top 20 companies by quarterly sales growth

### Sector Analysis
* Average ROCE by sector
* Average P/E by sector
* Average market capitalization by sector
* ROCE distribution across sectors

### Distribution Analysis
* Market capitalization distribution
* ROCE distribution
* Dividend yield distribution
* ROCE outlier detection using boxplots

### Relationship Analysis
* Market capitalization vs ROCE
* Quarterly sales growth vs quarterly profit growth
  
## 🔍 Key Analysis Questions
The project explores questions such as:

* Which sectors contain the highest number of companies?
* Which companies have the highest market capitalization?
* Which companies have higher ROCE?
* Which companies show higher quarterly profit growth?
* Which companies show higher quarterly sales growth?
* How does ROCE vary across sectors?
* How is market capitalization distributed?
* Are there outliers in ROCE?
* Is there a relationship between market capitalization and ROCE?
* Does quarterly sales growth relate to quarterly profit growth?

## 📁 Project Structure

Stock-Market-EDA/
│
├── EDAproject.ipynb
├── Cleaned_Sector_Data.csv
└── README.md

## ▶️ How to Run the Project
### 1. Clone the repository
git clone <your-github-repository-url>

### 2. Open the notebook
Open:
EDAproject.ipynb

using **Jupyter Notebook** or **Google Colab**.

### 3. Install required libraries
pip install requests beautifulsoup4 lxml pandas matplotlib seaborn

### 4. Run the notebook
Execute the notebook cells sequentially to:
1. Scrape the data
2. Create the dataset
3. Clean the data
4. Perform statistical analysis
5. Generate visualizations
6. Analyze relationships between financial variables

## 💡 Skills Demonstrated
* Web Scraping
* Data Collection
* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Missing Value Handling
* Data Visualization
* Python Programming
* Pandas
* Matplotlib
* Seaborn
* BeautifulSoup
* Business & Financial Data Analysis

## 👨‍💻 Project Type
**Exploratory Data Analysis | Web Scraping | Financial Data Analytics**

## 📌 Disclaimer
This project is created for educational and analytical purposes. The financial data is collected from a publicly accessible website and the analysis should not be considered financial or investment advice.

This project is created for **educational and analytical purposes**. The financial data is collected from a publicly accessible website and the analysis should not be considered financial or investment advice.
