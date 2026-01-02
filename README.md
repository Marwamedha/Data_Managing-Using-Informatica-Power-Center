# ETL-Project-Informatica-Power-Center

In this project, I utilized **Informatica PowerCenter** to tackle real-world data engineering challenges with a strong focus on **Extraction, Transformation, and Loading (ETL)**. The solution processes customer churn data from two CSV files: `Churn_Modelling2.csv` and `Churn_Modelling3.csv`, applies business rules, ensures data quality, and produces analytical outputs suitable for reporting and decision-making.

---

## 🔧 Source Data

* **Churn_Modelling2.csv**
* **Churn_Modelling3.csv**

Both files are treated as flat-file sources and integrated into a unified ETL pipeline.

---

## ✅ Key Accomplishments

### 1️⃣ Sum of Balances for Male and Female Customers

Aggregated customer balances by gender using **Aggregator transformations**, providing insights into gender-based financial trends.

### 2️⃣ Number of Active Male and Female Customers

Filtered active customers and calculated counts by gender to analyze customer engagement patterns.

### 3️⃣ Customer Age Distribution

Categorized customers into age groups using **Expression transformations**:

* Age between **18–30**
* Age between **30–45**
* Age **> 45**

This distribution reveals valuable demographic insights.

### 4️⃣ Users with Available Balance Data

Identified customers with available balance data (**Balance > 0**) and ranked them in ascending order to enable targeted analysis.

### 5️⃣ Top 5 Balances

Extracted complete customer information for the **top 5 balance holders** using **Rank transformations**, supporting identification of high-value customers.

### 6️⃣ Highest and Lowest Credit Score Values

Determined **minimum and maximum credit score values**, which are vital metrics for assessing overall customer creditworthiness.

---

## 🚀 Advanced & Innovative Enhancements

### 🔹 Data Quality & Validation Framework

Implemented data quality checks to ensure reliable analytics:

* Invalid records (e.g., Age < 18, Balance < 0, NULL CreditScore) are redirected to **reject files** with rejection reasons.

### 🔹 Parameterization & Reusability

Introduced workflow and mapping parameters such as:

* `$$SRC_FILE_PATH`
* `$$TARGET_PATH`
* `$$RUN_DATE`

This enables easy deployment across **DEV / TEST / PROD** environments.

### 🔹 Incremental Load Strategy

Designed incremental load logic using **Lookup** and **Update Strategy** transformations to:

* Insert new customers
* Update existing customer records

This improves performance and scalability.

### 🔹 Credit Score Risk Classification

Extended credit score analysis by deriving a **Credit Risk Level**:

* **High Risk**: CreditScore < 580
* **Medium Risk**: 580–670
* **Low Risk**: > 670

This bridges technical ETL with business intelligence use cases.

### 🔹 ETL Audit & Control Framework

Captured operational metadata including:

* Records read / loaded / rejected
* Workflow execution time
* Execution status

This supports monitoring, traceability, and production readiness.

### 🔹 Performance Optimization Techniques

Applied best practices such as:

* Sorted input for aggregations
* Lookup caching
* Pushdown optimization (where applicable)

---

## 🗺️ Mapping Screenshots

### 1️⃣

![Screenshot (195)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/2801fbc5-30a7-411e-8a83-1d144d766200)

### 2️⃣

![Screenshot (194)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/78c7a0ee-d57a-428e-95c7-5467ba5f83a5)

### 3️⃣

![Screenshot (193)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/afc6400d-478c-4b35-99b7-6d520d741deb)

### 4️⃣

![Screenshot (192)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/b1d1975d-0196-4b65-81b8-45b8776fac4b)

### 5️⃣

![Screenshot (191)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/ff4a90a5-6f6e-46ea-838a-485479e37f85)

### 6️⃣

![Screenshot (190)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/b371aadb-343d-4a4d-8d12-ffd55c012fca)

---

## 🎯 Project Value

This project demonstrates strong command of **Informatica PowerCenter**, real-world ETL design patterns, data quality handling, incremental loading, and performance optimization. It is well-suited for **ETL Developer, BI Developer, and Data Engineer** roles.
# ETL-Project-Informatica-Power-Center

In this project, I utilized Informatica skills to tackle intriguing data challenges, with a focus on extraction, transformation, and loading from two CSV files: `Churn_Modelling2.csv` and `Churn_Modelling3.csv`. Here's a breakdown of the key accomplishments:

## 1️⃣ Sum of Balances for Male and Female Customers
Aggregated balances for male and female customers, offering insights into gender-based financial trends.

## 2️⃣ Number of Active Male and Female Customers
Identified active customers by gender, illuminating engagement patterns.

## 3️⃣ Customer Age Distribution
Categorized customers by age groups, revealing demographic insights.

## 4️⃣ Users with Available Balance Data
Identified users with balance data and ranked them, facilitating targeted analysis.

## 5️⃣ Top 5 Balances
Extracted detailed information on top 5 balance holders, crucial for identifying high-value customers.

## 6️⃣ Highest and Lowest Credit Score Values
Determined extreme credit score values, vital metrics for assessing creditworthiness.


# Maps Screenshots
## 1️
![Screenshot (195)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/2801fbc5-30a7-411e-8a83-1d144d766200)
## 2️
![Screenshot (194)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/78c7a0ee-d57a-428e-95c7-5467ba5f83a5)
## 3️
![Screenshot (193)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/afc6400d-478c-4b35-99b7-6d520d741deb)
## 4️
![Screenshot (192)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/b1d1975d-0196-4b65-81b8-45b8776fac4b)
## 5️
![Screenshot (191)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/ff4a90a5-6f6e-46ea-838a-485479e37f85)
## 6
![Screenshot (190)](https://github.com/Mostafa2096/ETL-Project-Informatica-Power-Center/assets/106194954/b371aadb-343d-4a4d-8d12-ffd55c012fca)
