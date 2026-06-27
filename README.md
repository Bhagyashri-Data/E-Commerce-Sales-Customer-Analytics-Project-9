# E-Commerce-Sales-Customer-Analytics-Project-9
# Retail Sales Data Cleansing Pipeline (Python Pandas)

## 📌 About the Project
In this project, I built an end-to-end data cleansing and transformation pipeline using the Python Pandas library. Working with raw and messy retail sales and customer datasets, I performed various data preprocessing steps to transform raw data into a structured format, making it completely ready for downstream data analysis.

## 🛠️ Key Pandas Core Concepts Covered
I practically implemented the following core data manipulation pillars during this project:
- **Data Loading & Inspection:** Utilized `.head()` to inspect dataframe structures and preview initial records.
- **Handling Missing Values:** Detected missing records using `.isnull().sum()` and imputed them appropriately using `.fillna()`.
- **Removing Duplicates:** Cleaned the dataset by identifying and dropping redundant rows using `.drop_duplicates()`.
- **Column Operations:** Streamlined the schema using `.rename()` for column mapping and modified data representations using `.astype()`.
- **Advanced Filtering:** Extracted specific data subsets by applying multi-condition logical operations using `.loc[]`.
- **Data Aggregation:** Summarized key business metrics by grouping data via `.groupby().agg()` combined with `.reset_index()`.
- **Combining Datasets:** Executed relational lookups and vertical stacking using `pd.merge()` (Inner/Left Joins) and `pd.concat()`.
- **Text Manipulation & Sorting:** Arranged transactions using `.sort_values()` and isolated specific text patterns using `.str.contains(case=False)`.

## 📈 Key Learning Outcomes
Through this practical workflow, I gained a deep understanding of the structural similarities between Pandas operations and SQL queries (e.g., how `.groupby()` mirrors SQL's `GROUP BY` and `pd.merge()` functions exactly like relational `JOINS`). I also mastered critical data behaviors, such as why `NaN` populates for unmatched left joins and how `case=False` ensures robust, case-insensitive text filtering.
