📌 Project Overview

The project options cover real-world datasets from different domains and focus on data cleaning, exploratory analysis, statistical analysis, and data visualization.

The assignment provides five project topics:

🦠 COVID-19 Data Analysis and Visualization

😊 Global Happiness Report Analysis

🚢 Titanic Survival Analysis

🌍 Air Quality Analysis

📈 Stock Market Analysis

🦠 1. COVID-19 Data Analysis and Visualization

📌 Description

Analyze the spread of COVID-19 over time by examining trends in cases, recoveries, and deaths across different countries or regions. Visualizations can be used to understand the impact and spread of the virus.

📊 Dataset Sources

Our World in Data – COVID-19 Dataset

Our World in Data – COVID-19 Data on GitHub

Our World in Data notes that its COVID-19 data now uses WHO data for the main cases/deaths time series; the older Johns Hopkins-based series is available as an archive.

🛠️ Tools / Libraries

Pandas

Matplotlib

Seaborn

Plotly

🔍 Possible Analysis

COVID-19 cases over time

Death and recovery trends

Country/region comparison

Date/time analysis

Missing-value handling

Trend visualization

Interactive charts

😊 2. Global Happiness Report Analysis

📌 Description

Analyze World Happiness Report data to understand what factors contribute to happiness in different countries. The analysis can explore relationships between happiness scores and factors such as GDP per capita, social support, life expectancy, freedom, generosity, and perceptions of corruption.

📊 Dataset Sources

World Happiness Report – Kaggle Dataset

Official World Happiness Report – Data Sharing

🛠️ Tools / Libraries

Pandas

Matplotlib

Seaborn

🔍 Possible Analysis

Happiness score by country

Highest and lowest happiness scores

GDP vs happiness

Social support vs happiness

Life expectancy vs happiness

Correlation analysis

Country comparison

Statistical visualizations

🚢 3. Titanic Survival Analysis

📌 Description

Perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors that influenced passenger survival. Visualizations can represent survival patterns by passenger class, gender, age, and other variables.

📊 Dataset Source

Titanic Dataset – Kaggle

The Kaggle dataset provides train.csv and test.csv; the training data contains the survival outcome used for analysis.

🛠️ Tools / Libraries

Pandas

Matplotlib

Seaborn

🔍 Possible Analysis

Overall survival count

Survival by gender

Survival by passenger class

Age distribution

Fare analysis

Missing-value analysis

Correlation analysis

Exploratory Data Analysis

🌍 4. Air Quality Analysis

📌 Description

Analyze air quality data from different locations to understand pollution levels over time. Visualizations can be used to study air-quality measurements and their relationships with environmental variables.

📊 Dataset Sources

UCI Machine Learning Repository – Air Quality Dataset

OpenAQ – Global Air Quality Data

OpenAQ API Documentation

The UCI Air Quality dataset contains hourly measurements from an air-quality multisensor system and includes pollutant and environmental measurements.

🛠️ Tools / Libraries

Pandas

Matplotlib

Seaborn

🔍 Possible Analysis

Pollution trends over time

Missing-value handling

Date/time analysis

Statistical analysis

Location-wise comparison

Correlation analysis

Scatter plots

Heatmaps

📈 5. Stock Market Analysis

📌 Description

Analyze historical stock market data to identify trends and patterns in stock prices over time. The project can visualize stock performance using indicators such as moving averages and trading volume.

📊 Dataset Sources

Yahoo Finance – Historical Data

Yahoo Finance Historical Data Help

Kaggle – Stock Market Datasets

For Python-based data retrieval, the project may also use the yfinance library.

🛠️ Tools / Libraries

Pandas

NumPy

Matplotlib

Seaborn

yfinance

🔍 Possible Analysis

Historical price analysis

Open, High, Low and Close prices

Trading-volume analysis

Moving averages

Return analysis

Price trends

Stock indicator comparison

Financial visualizations

🛠️ Common Technologies

Technology

Purpose

Python

Programming and analysis

Pandas

Data manipulation and cleaning

NumPy

Numerical calculations

Matplotlib

Data visualization

Seaborn

Statistical visualization

Plotly

Interactive visualization

yfinance

Historical stock-market data

📂 Suggested GitHub Structure

If you are keeping all five projects in one repository:

PR-Final-Project/
│
├── README.md
│
├── Project-1-COVID19/
│   ├── covid_19.ipynb
│   └── covid_19.csv
│
├── Project-2-Global-Happiness/
│   ├── global_happiness.ipynb
│   └── happiness.csv
│
├── Project-3-Titanic/
│   ├── titanic.ipynb
│   └── titanic.csv
│
├── Project-4-Air-Quality/
│   ├── air_quality.ipynb
│   └── air_quality.csv
│
└── Project-5-Stock-Market/
    ├── stock_market.ipynb
    └── stock_market.csv

If the submission contains only one selected project, keep the repository simpler:

PR-Final-Project/
│
├── README.md
├── project.ipynb
├── dataset.csv
└── screenshots/

🔄 Project Workflow

Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Statistical Analysis
   ↓
Data Visualization
   ↓
Insights & Conclusions

▶️ How to Run

1. Clone or download the GitHub repository

Open the repository in VS Code or Jupyter Notebook.

2. Install required libraries

pip install pandas numpy matplotlib seaborn plotly yfinance

3. Open the Jupyter Notebook

Open the required .ipynb file.

4. Run the notebook

Run the cells sequentially and review the outputs, charts, analysis, and insights.

📚 Learning Outcomes

Through this project, I practiced:

Working with real-world datasets

Data loading and inspection

Data cleaning and preprocessing

Handling missing and invalid values

Data manipulation using Pandas

Exploratory Data Analysis (EDA)

Statistical and correlation analysis

Time-series analysis

Creating meaningful visualizations

Interpreting trends and relationships

Presenting analytical results professionally

🔗 Dataset Source vs GitHub Project Link

The Dataset Source links in this README are where the original/recommended datasets can be obtained.

The GitHub Repository link is the link you share with your teacher for your completed project.

Example:

Dataset Source
      ↓
Download Dataset
      ↓
Create Jupyter Notebook
      ↓
Perform Analysis
      ↓
Upload Notebook + Dataset + README to GitHub
      ↓
Copy GitHub Repository Link
      ↓
Share Repository Link with Teacher

👩‍💻 Author

Vaibhavi Khokhani

Python & AI Fresher | BCA Graduate

⭐ Project Submission

This project is maintained on GitHub. The GitHub repository contains the project documentation, notebook, dataset, analysis, and visualizations required for submission.
