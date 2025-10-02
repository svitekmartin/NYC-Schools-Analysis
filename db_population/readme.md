**NYC School SAT Scores — Data Engineering**

🎯 **Objective**  
Evaluate, clean, model, and load a real-world SAT results dataset into an existing PostgreSQL schema. Tasks included data inspection, key identification, consistency fixes, and a Python-based append into the target table.

✅ **Completed Work**

-   **Data Profiling:** Reviewed `sat_results.csv` to understand structure, data types, candidate keys, and anomalies.
    
-   **Cleaning:**
    
    -   Removed duplicates and filtered invalid SAT scores (outside 200–800).
        
    -   Standardized inconsistent formats (e.g., values like `85%`).
        
    -   Normalized column headers and dropped nonessential fields.
        
-   **Schema & Modeling:** Selected final upload columns and defined a table schema aligned to the cleaned dataset (including appropriate keys/constraints).
    
-   **Load Script:** Implemented a Python script (psycopg2/SQLAlchemy) that connects to PostgreSQL and appends cleaned rows using parameterized queries to ensure integrity and security.
    

📦 **Deliverables**

-   `cleaned_sat_results.csv` — cleaned dataset, ready for load.
    
-   `sat_modeling.ipynb` — Jupyter notebook with the cleaning steps and database append script.
