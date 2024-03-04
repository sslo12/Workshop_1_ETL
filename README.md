# Python Data Engineer Code Challenge
This repository contains the code developed for the Python Data Engineer technical challenge.
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
# Structure
   * data/: Contains the original CSV data file
   * notebooks/: Jupyter notebooks with database loading and visualization code
   * visualization/: Files with generated visualizations
***
# Implementation Instructions
## Step 1: Clone the Repository
    git clone https://github.com/sslo12/Workshop-1-ETL

## Step 2: Execute step-by-step these notebooks in the following order
    - connection and loading.ipynb -> Database connection and csv loading
    - EDA.ipynb -> Exploratory Dataset Analysis
    - Challenge.ipynb -> Data processing

## Step 3: Graphics
Connect Power BI Desktop to `ScriptVisualization` to run the report

## Step 4: Dashboard
    https://app.powerbi.com/view?r=eyJrIjoiNzUzNjgwYWUtODcxZi00OWM5LWI2ZWQtN2VmM2ViODgzMjdiIiwidCI6IjY5M2NiZWEwLTRlZjktNDI1NC04OTc3LTc2ZTA1Y2I1ZjU1NiIsImMiOjR9&pageName=ReportSection08db08d3c0ae3ee36dcf
***
# Conclusions
