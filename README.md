# Aayan Angkit Kashyap - Portfolio
## About Me
👋 Hello there! I'm Aayan, currently pursuing my Master's in Earth Sciences at IISER Kolkata. As a data analyst, I'm passionate about exploring the intersection between data science and our planet's most critical systems. 

My focus includes exploring everything from the long-term trends in global warming to the computational analysis of seismic activity. This passion within me with a multidisciplinary mindset keeps me how data can be utilized for the ends of disaster risk and hazard management to assist with the realization of a more resilient and sustainable future. 🌿 

When I'm not delving into datasets, I channel my time and creativity through photography 📸 and music, playing both piano and drums. 🎵



This repository showcases my skills, shares projects, and tracks my progress in data analytics, especially related to earthquake hazard and climate change.

## Table of Contents
- [About Me](https://github.com/Pianomello/hoho/blob/main/README.md#About-Me)
- [Projects](https://github.com/Pianomello/hoho/blob/main/README.md#Projects)
  - Python
    - [Climate & Catastrophe: A Data-Driven Analysis of Rising Temperatures, Natural Disasters, and their Economic Toll](https://github.com/Pianomello/Climate_Impact)
      
    - [Comparative Analysis of Historical Temperature Trends in India, China, and the United States](https://github.com/Pianomello/Temp_Trend_Analysis)
      
    - [Automated Amazon Price Tracker & Alert System](https://github.com/Pianomello/Amazon_Web_Scraper)
        
 
  - Excel
    - [Excel Dashboard for Coffee Sales Analysis](https://github.com/Pianomello/Coffee_Sales_analysis)
      
    - [Interactive Excel Dashboard for Bike Purchase Trends Analysis](https://github.com/Pianomello/Bike_Sale_Analysis)
  
  

- [Education](https://github.com/Pianomello/hoho/blob/main/README.md#education)

  
- [Contact](https://github.com/Pianomello/hoho/blob/main/README.md#contacts)

  
## Projects
In this section, I will list my analysis projects, briefly describing the technology stack used to solve real-world cases.

### Climate & Catastrophe: A Data-Driven Analysis of Rising Temperatures, Natural Disasters, and their Economic Toll
**Repo:** [`Exploratory_data_analysis_of_temperature_and_natural_disasters`](https://github.com/Pianomello/Climate_Impact)

**Goal:** This project's main objective is to present compelling, fact-based proof of the connection between climate change—more especially, anomalies in global temperatures—and the rise in the frequency of natural disasters. It also seeks to examine the financial effects of these calamities while taking global economic expansion into consideration.

**Description:** The relationship between anomalies in global temperatures, the frequency of different natural disasters, and the resulting economic damages is examined in this exploratory data analysis (EDA). Three major datasets are used in the project: global temperatures, the number of natural disaster events, and the economic damage caused by natural disasters. Global GDP data is also used for normalization.

The analysis includes:

1. Data cleaning and preprocessing include reshaping dataframes for analysis, handling missing values, and converting data types.

2. Temperature Anomaly Calculation: To identify warming trends, temperature anomalies are calculated from a baseline (1951–1980 average).

3. Classifying and displaying the frequency of various natural disaster types over time is known as disaster occurrence analysis.

4. Evaluating the total and normalized (as a percentage of GDP) financial losses brought on by natural disasters is known as economic damage analysis.

5. Correlation Analysis: To measure the relationship between temperature anomalies, disaster events (both general and climate-related), and economic damages, Pearson and Spearman correlation coefficients are calculated.

6. Statistical Testing: Determining the statistical significance of observed correlations by utilizing the Shapiro-Wilk Normality Test and analyzing p-values.

7. Limitations Discussion: Taking into account elements such as reporting bias.

**Skills:** data cleaning, data analysis, hypothesis testing, correlation matrices, data visualization.

**Technology:** Python, Pandas, Numpy, Seaborn, Matplotlib, SciPy.

**Results:** In conclusion, the statistics overwhelmingly prove that a hotter world is experiencing more consistent pounding by nature disasters, which is having a consistent and measurable, even if complicated, impact upon the global economy.

### Comparative Analysis of Historical Temperature Trends in India, China, and the United States

**Repo:** [`Temperature_Trend_Analysis`](https://github.com/Pianomello/Temp_Trend_Analysis)

**Goal:** 

1. to compare the temporal trends and temperature distributions in China, India, and the US.

2. to evaluate temporal and spatial variation, especially at the city level, within the Indian nation.

3. to measure and illustrate trends in warming at the national level during the 20th and 21st centuries.

4. to establish an analytical framework for additional data-driven, climate-focused research.


**Description:** Using historical climate data, this project examines long-term temperature trends in three geographically and climatically different nations: the United States, China, and India. Histograms, KDE plots, scatterplots, and temporal line plots are among the visual exploratory techniques used in the analysis to compare the evolution of average surface temperatures across cities and countries and find patterns. The project intends to offer empirical insight into regional climate warming by utilizing data from the Global Historical Climatology Network and utilizing data visualization techniques based on Python.




**Skills:** data cleaning, exploratory data analysis, data visualization

**Technology:** Python, Pandas, Seaborn, Matplotlib

### Automated Amazon Price Tracker & Alert System
**Repo:** [`Amazon_Web_Scraper`](https://github.com/Pianomello/Amazon_Web_Scraper)

**Goal:** This project's main objective is to create an automated web scraper that monitors a product's price on Amazon.in and notifies the user via email when the price falls below a predetermined threshold. This enables customers to buy the things they want at the best prices.

**Description:** The purpose of this Python-based web scraping project is to track a product's price on Amazon's Indian marketplace. Periodically, it retrieves product details, extracts the current price, logs it, and sends the user an email if the price drops below a predetermined threshold.

Web scraping is the process of extracting the product title and current price from an Amazon product page by parsing the HTML content using BeautifulSoup and requests.

1. Data Extraction & Cleaning: Working with raw HTML to precisely extract the product's name and price, including removing any non-digital characters.

2. Timestamping: Using the datetime module, note the date of every price check.

3. CSV Data Storage: Web_Scraper_data.csv is a CSV file that contains the scraped data (Product Title, Price, Date). With each price check, the script adds new data and, if the file doesn't already exist, creates it.

4. Automated Price Monitoring: Establishing a time-based loop. To enable continuous monitoring, we use time.sleep() to pause the script for a predetermined amount of time (say, a day) before running the subsequent price check.

5. Email Notification System:  When the scraped price falls below a user-specified threshold (for example, ₹65,000 for the DJI Osmo Pocket 3 Creator Combo), an automated email is sent via Smtplib. Secure SMTP server login is part of this feature.



**Skills:** web scraping, HTTP requests, HTML Parsing, Data Extraction, File I/O (CSV), Email Automation.

**Technology:** Python, Pandas, BeautifulSoup, smtplib, requests

**Results:** This project effectively illustrates how to develop a useful tool for tracking Amazon prices.


### Excel Dashboard for Coffee Sales Analysis
**Repo:** [`Coffee_Sales_analysis`](https://github.com/Pianomello/Coffee_Sales_analysis)

**Overview:**
This project presents a comprehensive Coffee Sales Dashboard created in Microsoft Excel, offering key insights into customer behavior, product performance, and revenue trends. Leveraging Excel functions, pivot tables, slicers, and dynamic visualizations, the dashboard serves as a powerful business intelligence tool to support data-driven decisions in a coffee sales environment. I have learned the methodology and layout from the following YouTube tutorial titled "Excel Dashboard for Data Analysis - Coffee Sales Analysis" by Mo Chen, while also tailoring the design and interactivity based on personal exploration.

**Skills:** Pivot Tables, Dashboard Layout Design, Data Cleaning & Categorization, Data Sorting and Formatting, Excel Formulas (IF, Nested IF, SUM, etc.), Slicers for interactivity.

**Software:** Microsoft Excel



### Interactive Excel Dashboard for Bike Purchase Trends Analysis
**Repo:** [`Bike_Sales_analysis`](https://github.com/Pianomello/Bike_Sale_Analysis)

**Overview:**
I created an interactive Bike Sales Dashboard in Excel by cleaning and preparing the data first—de-duping, substituting codes such as "M" with "Married", and aggregating ages with nested IF formulas. I formatted income into currency and segmented users into age groups. I investigated insights such as how income, age, and commute distance affect bike buying with Pivot Tables. The last dashboard has dynamic marital status, region, and other filters (Slicers) so it is simple to investigate trends at a glance.

**Skills:** Pivot Tables, Dashboard Layout Design, Data Cleaning & Categorization, Data Sorting and Formatting, Excel Formulas (IF, Nested IF, SUM, etc.), Slicers for interactivity.

**Software:** Microsoft Excel




# Education
Indian Institute of Science Education and Research (IISER) Kolkata,


BS-MS, Earth Sciences



# Contacts
- LinkedIn: [@aayan_angkit_kashyap](https://www.linkedin.com/in/aayan-angkit-kashyap-02215425b)
- Email: aayanak04@gmail.com
