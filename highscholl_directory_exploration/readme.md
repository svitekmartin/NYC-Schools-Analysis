# Python Data Exploration

### 🎯 Project Goal

This project explored the **NYC High School Directory dataset** using **Python** in a Jupyter Notebook. The objective was to clean and structure the data, perform exploratory analysis, create visualizations, and extract meaningful insights about schools across different boroughs.

---

### ✅ Key Steps Completed

1. **Data loading & cleaning:**
   The dataset was imported into a pandas DataFrame, and column names were standardized (lowercase, underscores instead of spaces, removal of special characters).

2. **Filtering & analysis:**
   Schools in Brooklyn were isolated for targeted analysis. Specific questions—such as the number of unique schools and Grade 9 entry availability—were answered.

3. **Grouping & summarization:**
   Data was aggregated by borough to calculate:

   * Number of schools
   * Average number of students per borough
   * Summary statistics for `grade_span_max`

4. **Visualizations:**
   Two bar charts were generated to highlight borough-level patterns:

   * [Number of Schools per Borough](/Number_of_Schools_per_Borough.png)
   * [Number of Students per Borough](Number_of_Students_per_Borough.png)

5. **Insights derived:**
   Three main observations were drawn from the analysis, detailed below.

---

### 🧠 Insights from Analysis

**1. Number of Schools vs. Student Population**
The number of schools generally aligns with borough population size, but the more important metric is the **average number of students per school**, which reveals deeper differences between boroughs.

**2. School Efficiency & Size**

* **Staten Island** and **Queens** show the **highest average student counts per school**, indicating larger and more densely populated schools.
* **Brooklyn, the Bronx, and Manhattan** have lower averages, suggesting a preference for smaller or more specialized schools.
  This may reflect differences in school types, resource allocation, or population density.

**3. Borough-Level Comparison**

* **Brooklyn** leads with both the largest number of schools and total students.
* **Queens**, however, operates with only 80 schools compared to the **Bronx** with 118, yet serves nearly twice as many students per school.
  This contrast highlights two distinct educational strategies: many smaller schools (Bronx, Brooklyn) vs. fewer but larger schools (Queens). Such findings are valuable for shaping educational policies—e.g., whether to build more large schools or distribute students across multiple smaller ones.

