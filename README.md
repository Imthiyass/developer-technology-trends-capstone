# Developer Technology Trends: IBM Data Analyst Capstone

**Author:** Mohamed Imthiyas

A data analysis project for the IBM Data Analyst Professional Certificate. It uses the Stack Overflow Developer Survey (65,437 respondents after removing duplicates) to show which technologies developers use today and want to use next.

## Key findings
- JavaScript (62.8%), HTML/CSS (53.3%), Python (51.4%) and SQL (51.4%) are the most used languages.
- Python is the language developers most want to use next (44.9%). Rust (30.9%) and Go (24.8%) enter the top 10.
- PostgreSQL leads databases now (50.8%) and next year (56.4%). MySQL falls from 42.0% to 28.8%.
- Median yearly pay is $65,000. Swift, Python and C++ have the highest average salaries.
- Hybrid (42.0%) and remote (38.0%) work are the most common.

## Dashboard (Google Looker Studio)
[Open the live dashboard](https://datastudio.google.com/reporting/20623146-91b3-40bb-9698-15e30db92d9f)

![Current technology usage](images/tab1.png)
![Future technology trends](images/tab2.png)
![Demographics](images/tab3.png)

## Report
[Data Analyst Capstone Project Report (PDF)](Data%20Analyst%20Capstone%20Project%20Report.pdf)

## Methods
1. Collected data with Python `requests` (job postings API) and `BeautifulSoup` (web scraping).
2. Cleaned the survey: removed duplicates, handled missing values, standardized labels, normalized pay.
3. Analyzed and charted results with pandas, matplotlib and seaborn.
4. Built a 3-tab dashboard in Looker Studio and a final PDF report.

## Tools
Python, pandas, NumPy, matplotlib, seaborn, BeautifulSoup, requests, openpyxl, Jupyter, Google Looker Studio, PowerPoint.
