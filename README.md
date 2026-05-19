# customer_behavior_analysis
This project demonstrates a complete data analysis workflow using Python, PostgreSQL, and Power BI. The project includes loading and exploring a dataset, cleaning and preprocessing data, performing SQL analysis on a PostgreSQL server, and creating an interactive Power BI dashboard to visualize insights.

The goal of this project is to analyze the dataset, identify meaningful patterns, and present the findings through clear visualizations and reports.

## Dataset

The dataset used in this project contains structured data related to customer transaction and sales analysis.

### Dataset Features

* Numerical and categorical attributes
* Missing and duplicate values
* Data suitable for statistical analysis and visualization

### Example Columns

* Customer ID
* Purchase Amount
* Category
* Item Purchased
* Shipping Type
* Subscription Status

## Tools & Technologies

* Python
* PostgreSQL
* Power BI
* VS Code

## Project Steps

### 1. Data Loading

* Imported dataset using Python
* Loaded data into Pandas DataFrames
* Inspected dataset structure and data types

### 2. Exploratory Data Analysis (EDA)

Performed:

* Summary statistics
* Distribution analysis
* Correlation analysis
* Missing value analysis
* Data visualization using charts and graphs

### 3. Data Cleaning

Handled:

* Missing values
* Duplicate records
* Incorrect data types
* Outliers and inconsistent values

### 4. PostgreSQL Analysis

* Connected Python with PostgreSQL server
* Created database tables
* Imported cleaned dataset into PostgreSQL
* Executed SQL queries for analysis

Example SQL operations:

* Filtering data
* Aggregations
* Joins
* Group By queries
* Trend analysis

### 5. Power BI Dashboard

Created an interactive dashboard to visualize:

* Key performance indicators (KPIs)
* Sales trends
* Customer insights
* Category performance
* Regional analysis

---

## Dashboard Features

The Power BI dashboard includes:

* Interactive filters and slicers
* Charts and graphs
* KPI cards
* Trend analysis visualizations
* User-friendly layout for better decision-making

---

## Results & Insights

Some key insights identified from the analysis:

* Top-performing categories and regions
* Customer purchasing patterns
* Sales trends over time
* Business performance indicators
* Data-driven recommendations

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Gnilu/customer_behavior_analysis.git
```

### 2. Install Required Libraries

```bash
pip install psycopg2.binary sqlalchemy
```

### 3. Run Python Notebook

Open the Jupyter Notebook or Python files and run all cells.

### 4. Setup PostgreSQL

* Create a PostgreSQL database
* Update database connection credentials in the Python script
* Import cleaned dataset into PostgreSQL

### 5. Open Power BI Dashboard

* Open the `.pbix` file in Power BI Desktop

## Conclusion

This project demonstrates an end-to-end data analysis process, from raw data preprocessing to business intelligence dashboard creation. It highlights the use of Python for analysis, PostgreSQL for database management, and Power BI for visualization and reporting.

