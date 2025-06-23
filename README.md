# Python Data Engineer Code Challenge
This repository contains the code developed for the Python Data Engineer technical challenge, its main purpose is to demonstrate in a tangible way a complete data Extraction, Processing and Data Ingestion (ETL) flow using tools such as Python and MySQL. In this work, he uses information about job applicants at a technology company. After applying sequences of manipulation to the data including data collection, cleansing and restructuring, the results are stored in a structured database for further visual analysis in Power BI.

***
# Objective
The objective of the challenge is to show metrics and visualizations from a set of candidate data for selection processes. It must:

* Load data from a CSV to a relational database
* Develop visualizations showing:
    - Hires by technology (pie chart)
    - Hires by year (horizontal bar chart)
    - Hires by seniority (vertical bar chart)
    - Hires by country over the years (USA, Brazil, Colombia and Ecuador) (multiple line chart)
***
# Technologies Used
  * <img src="https://github.com/sslo12/Workshop-1-ETL/assets/115416417/b23a91ab-151a-4dd8-b421-fc87111e3481" alt="Looker Studio" width="21px" height="21px"> Python
  * <img src="https://cdn.icon-icons.com/icons2/2667/PNG/512/jupyter_app_icon_161280.png" alt="Looker Studio" width="21px" height="21px"> Jupyter Notebook
  * <img src="https://cdn.icon-icons.com/icons2/2415/PNG/512/mysql_original_wordmark_logo_icon_146417.png" alt="Looker Studio" width="21px" height="21px"> Relational database (MySQL)
  * <img src="https://i.pinimg.com/736x/7a/f2/1e/7af21eaf89a449831a1e12d640b54fae.jpg" alt="Looker Studio" width="21px" height="21px"> Power BI Desktop
***
# Data Information
The provided data corresponds to 50k random records of candidates.csv with the following fields:

  * Name
  * Last Name
  * Email
  * Country
  * Application Date
  * Years of Experience
  * Seniority
  * Technology
  * Code Challenge Score
  * Technical Interview

A candidate is considered "hired" when they have scores greater than or equal to 7 in the last two metrics.
***
# Workflow
![image](https://github.com/sslo12/Workshop-1/assets/115416417/0bbbacad-b0c4-4b54-a73e-9d69e71921f7)
***
# Implementation Instructions
### Step 1: Clone the Repository
    git clone https://github.com/sslo12/Workshop-1-ETL

### Step 2: Execute step-by-step these notebooks in the following order
  - connection and loading.ipynb     -> Database connection and csv loading
  - EDA.ipynb                        -> Exploratory Dataset Analysis
  - Challenge.ipynb                  -> Data processing

### Step 3: Graphics
Connect Power BI Desktop to `ScriptVisualization` to run the report

### Step 4: Dashboard
<sub>https://app.powerbi.com/links/kxYRj3CA2Y?ctid=693cbea0-4ef9-4254-8977-76e05cb5f556&pbi_source=linkShare</sub>
