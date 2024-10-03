# End-to-End Data Project

## Project Overview:
This project showcases my end-to-end data analysis and visualization skills. Using Python, I scraped, cleaned, and processed stock market data from Yahoo Finance, then visualized the insights using Tableau. The dashboard lets users interactively explore the top 25 most active stocks based on market activity, providing insights into stock performance, market capitalization, and sector analysis.

Data Scraping & Processing: Python(Beautiful Soup, Pandas)  
Data Visualization & Interactive Dashboard: Tableau

# How to Use:
Click on the link below to explore the dashboard(Suggest to view it with FullScreen for full functionality):
https://public.tableau.com/views/End-to-EndStockDataAnalysisDashboard/Dashboard1?:language=zh-TW&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
<img width="1394" alt="螢幕截圖 2024-09-30 下午8 27 16" src="https://github.com/user-attachments/assets/9df286ad-6ba0-4d77-980d-030ec3f6161b">

# Data Processing
#### Scraping Data from the website:
<img width="687" alt="ScrapeDataSS" src="https://github.com/user-attachments/assets/9bf53a19-81e2-49fd-9f94-84e56fad33a7">

#### Cleansing the data before analysis:
<img width="689" alt="CleanDataSS" src="https://github.com/user-attachments/assets/77653e40-6f64-4ae9-a20c-6249e9082ad3">

#### Cleansing Deatails Example:  
Price: Extracting the numeric value from a string that include currency symbols.  
Change and Change %: Converting string representations of numerical values to floats, removing percentage symbols.  
Volume and Average Volume: Converting values expressed as millions to full numerical representation.  
Market Cap: Converting values expressed as billions or trillions to their full numerical value.

# Dashboard
#### The filters on the Stock Market Dashboard provide dynamic control over the dataset, allowing users to tailor their analysis to specific interests. Key features include:

Sector Filter: Narrow down stock performance to a particular industry sector, such as Technology, Healthcare, or Finance.  
<img width="254" alt="螢幕截圖 2024-09-30 下午8 33 11" src="https://github.com/user-attachments/assets/8e2d4b03-1306-489c-9114-713fc202b502">  

Market Cap Size Filter: Explore stocks by their market capitalization size, from large-cap to small-cap companies.  
<img width="205" alt="螢幕截圖 2024-09-30 下午8 33 01" src="https://github.com/user-attachments/assets/e0c4dddd-4fe1-4cc1-a1e3-cadd640284c9">  

Top N Filter: Adjust the view to focus on the top N stocks based on market capitalization or daily performance, allowing users to see the most relevant stocks at a glance.<img width="1392" alt="螢幕截圖 2024-09-30 下午8 33 21" src="https://github.com/user-attachments/assets/6990f2c9-c0ad-473d-826b-94bf401d13b7">


Gainers & Losers Toggle: Quickly identify the top-performing (gainers) or worst-performing (losers) stocks, filtering all visuals to show only relevant data.<img width="1379" alt="螢幕截圖 2024-09-30 下午8 34 02" src="https://github.com/user-attachments/assets/080b51e1-3ae3-4ee9-b2ef-d5a66c900294">
<img width="1382" alt="螢幕截圖 2024-09-30 下午8 33 49" src="https://github.com/user-attachments/assets/59b954ca-67a4-4719-a5eb-1457bfa79cb1">











