# 📊 Global Data Jobs & Skills Market Analysis with Python & Pandas

This project explores and visualizes the demand for data job roles and required skills globally using the `lukebarousse/data_jobs` dataset from HuggingFace. It highlights trends across roles (Data Analyst, Data Scientist, Data Engineer), evaluates top skills by popularity and salary, and uncovers patterns in hiring across countries.

![pandas1](https://github.com/user-attachments/assets/fc21df51-15a4-4da6-8305-a78f5abb4b58)


---

## 📌 Objectives

- Identify most in-demand skills across **all data job titles**.
- Compare skill sets needed for **Data Analysts, Engineers, and Scientists**.
- Examine **geographic hiring trends** for top 10 countries.
- Correlate **skills with median salary** to identify high-value competencies.
- Visualize findings through clear and compelling charts using `matplotlib`.

---

---

## 🛠️ Technologies Used

| Tool          | Purpose                                     |
|---------------|---------------------------------------------|
| `Python`      | Primary programming language                |
| `Pandas`      | Data analysis and preprocessing             |
| `Matplotlib`  | Data visualization                          |
| `HuggingFace` | Access to real job posting dataset          |

---

## 🔄 Workflow Overview

1. **Data Loading**
   - Used `datasets.load_dataset()` to import job postings.

2. **Cleaning & Preprocessing**
   - Parsed skill strings into lists.
   - Normalized text data (lowercasing, trimming).
   - Segmented roles by titles: `"data analyst"`, `"data scientist"`, `"data engineer"`.

3. **Skill Extraction**
   - Aggregated and counted skills using `collections.Counter`.
   - Segmented skills per role and globally.

4. **Visualization**
   - Created bar plots for role-specific and global skills.
   - Built salary vs. skill correlation plot.
   - Constructed multi-role country hiring comparison chart.

---

## 🔍 Analysis & Visual Insights

### 🔹 Top Job Skills Across All Nations


![pandas2](https://github.com/user-attachments/assets/50aa6c91-f6d1-404d-ae68-11a3bdbe65a6)

- **SQL** and **Python** are by far the most essential skills across all data job postings globally.
- Cloud platforms and BI tools (like **AWS**, **Azure**, **Power BI**) are also widely requested.
- Technologies like **Java**, **Spark**, and **Excel** support auxiliary or legacy systems.

---

### 📊 Data Analyst - Skill Focus

![pandas3](https://github.com/user-attachments/assets/6b549bc1-cf04-4cde-9c6c-fd0b7621e48a)


- Analysts require high proficiency in **SQL**, **Excel**, **Python**, and **Power BI**.
- **Tableau**, **R**, and **Word/PowerPoint** are supporting tools, reflecting report and dashboard needs.
- Suggests a **strong demand for data storytelling and reporting** skills.

---

### 🛠️ Data Engineer - Tech Stack
![pandas 5](https://github.com/user-attachments/assets/6b8db289-55e6-41c4-b79c-35087d0ae433)




- Engineers need hands-on with **SQL**, **Python**, **AWS**, **Azure**, **Spark**.
- **Kafka**, **Scala**, **Databricks**, and **Hadoop** point to Big Data and pipeline skills.
- Clear bias toward **cloud-native data engineering** and streaming infrastructure.

---

### 🔬 Data Scientist - Analytical Core
![pandas4](https://github.com/user-attachments/assets/a9eb8fa9-c90a-45ed-91de-0afece849056)



- Scientists lean heavily on **Python**, **SQL**, and **R** for analysis and modeling.
- Tools like **TensorFlow**, **SAS**, and **Tableau** support model development and visualization.
- Compared to engineers, their skill set is more **modeling and analytics-centric**.

---

## 🌍 Country-Wise Job Role Analysis
![pandas1](https://github.com/user-attachments/assets/597d578b-71af-4d4a-a64f-9f3306c9a3c9)




-  **USA**, **India**, and 🇩🇪 **Germany** dominate job postings in all three roles.
-  **Netherlands** shows exceptional demand for **Data Scientists**.
- Balanced market trends seen in 🇸🇬 Singapore and 🇪🇸 Spain.

---

## 💰 Skills vs. Median Salary

![pandas7](https://github.com/user-attachments/assets/edae3d8e-d0ff-497e-8f0b-93f428a5ed14)

- Although **Python** and **SQL** are most common, **Spark**, **AWS**, and **Java** correlate with **higher salaries**.
- **Excel** and **Power BI**, while popular, align with **lower-paying jobs**, likely due to their operational nature.
- **Azure** and **Tableau** offer a balanced skill-value tradeoff.

---

## 🧠 Key Takeaways

- ✅ **SQL + Python** are foundational — required across all roles and nations.
- ☁️ Cloud platforms (AWS, Azure, GCP) are a major differentiator, especially for engineers.
- 📊 Analysts benefit from **reporting tools** like Tableau and Power BI.
- 📈 High-paying skills include **Spark**, **Java**, **AWS**, and **Python**.
- 🌍 Hiring is global, with growing opportunities in emerging tech hubs.

---



