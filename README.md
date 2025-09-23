# 📚 Project Overview: NYC School Data Analysis  

## Purpose and Mission   

This project presents an in-depth exploration of NYC school data, illustrating the entire data analysis workflow — from initial exploration and cleaning through analysis, visualization, and database integration. 
It highlights the use of **Google Sheets**, **Python (pandas & matplotlib)**, and **SQL (PostgreSQL)** to extract actionable insights from real-world data.

---

## Data Sources  
The project uses four primary datasets related to NYC schools:  

- **school_safety_report**: Data on school incidents  
- **high_school_directory**: A directory of high schools  
- **school_demographics**: Demographic data for schools  
- **sat_results**: SAT exam results  

---

##  Approach  

- **Initial Data Exploration**  
  - Basic data cleaning and analysis in Google Sheets  
  - Normalizing column names and identifying the most frequent incident types  

- **Python-Powered Analytics**
  - Jupyter Notebook with pandas for loading, filtering, and grouping data  
  - Developed visualizations to reveal patterns in school and student distribution  

- **SQL-driven Insights**  
  - Stored data in a PostgreSQL database  
  - Queried with SQL in Python to answer questions about school distribution and demographic trends  

- **Data Engineering**  
  - Inspected and cleaned a new dataset (SAT scores)  
  - Designed a database schema  
  - Wrote a Python script to reliably append the cleaned data into the database  

---

## Results & Key Findings  

- **Uneven Distribution**: Brooklyn and the Bronx have the most schools; Staten Island the fewest  
- **School Efficiency**: Schools in Staten Island and Queens are, on average, larger and more densely populated than those in Brooklyn and the Bronx  
- **Incident Analysis**: The most frequent type of incident was “non-criminal”  
- **Student Support**: Identified schools with a significantly high percentage of students requiring special needs support  
- **Data Integration**: A cleaned and prepared dataset of SAT scores was successfully integrated into the database  

---

## ⏭Next   

- **Data Merging**: Conduct deeper analysis by joining all four datasets into a single data model  
- **Correlation Analysis**: Explore relationships between incident rates and demographics, or between school size and SAT scores  
- **Dashboard Creation**: Develop an interactive dashboard to visualize key metrics and insights  
- **Advanced Analytics**: Apply machine learning to predict SAT results based on other school characteristics  
