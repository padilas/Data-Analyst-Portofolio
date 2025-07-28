# Asyifa N. Fadhilah - Data Analyst Portofolio
## About
Hi! I'm Asyifa and welcome to my Data Analyst Portfolio!

I am a data analyst with experience in utilizing various tools and technologies to collect, organize, explore, analyze, and visualize data to inform business decisions. I am proficient in Python, SQL, Tableau, BigQuery, Looker Studio, Excel, and Google Cloud Storage. I have a good understanding of data analytics techniques, including, but not limited to, statistics, exploratory data analysis (EDA), data mining, data management, dashboard building, report writing, critical thinking, and, most importantly, effective communication to convey my findings.

In this repository, I've included a variety of projects that showcase both my technical and analytical skills. You will find links to each project I've created. These projects demonstrate my ability to analyze and present data in a clear and visually appealing way, making it easy for anyone to understand the insight and take action.

My resume in [pdf](https://github.com/padilas/Data-Analyst-Portofolio/blob/main/Asyifa%20Nur%20Fadhilah%20-%20Resume.pdf)

## Table of Contents
* About
* Portfolio Projects
    - Python
    - SQL
    - R / R Shiny
      1. [Dynamic Dashboard: Indonesia Labour Data Visualization (2020 - 2021)](https://github.com/padilas/R-Shiny-Tenaga-Kerja/blob/main/README.md)
    - Excel
    - Tableau
      1. [Creative & Marketing Team "TV-Shows" Report and Plan](https://public.tableau.com/views/CandyCrush_TV-Shows/Homepage?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
      2. [Data + Movies: IMDb's Non-commercial Dataset Visualization](https://public.tableau.com/views/DataMoviesIMDbVisualization/Page01?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
    - Looker Studio
      1. [Analisis Pola Penyewaan DVD Rental Oleh Customer dalam Sistem](https://lookerstudio.google.com/reporting/e84e18e2-68d3-4f78-8c15-daec4de5d39d)
* Education
* Certificates
* Contact

## Portfolio Projects
In this section, I'll list data analytics projects and briefly describe the tools/technology stack I used to solve the cases.
### Production Company Management Systems
**Report:** [Production Company Management System.pdf](https://drive.google.com/file/d/11wO4HWbbs328_gN4BfcSDHoQ616v5VGQ/view?usp=sharing)

**Goal:** To develop a management system for a production company with a robust security layer, RBAC. Integrated management system development, database optimization, data management, and  data analysis.

**Description:** The project focused on developing a data management system that was structured for four different roles: Admin, Executive, Producer, and Marketing team. Each role has a dashboard with personalized functions designed to enhance their workflow. Role-Based Access Control is implemented in this system to ensure system security by granting each user access based on their role and function.

**Skills:** DML(Data Manipulation Language), DQL (Data Query Language), DDL (Data Definition Language), Database Management System, Data Management, Data Warehouse, SQL.

**Result:** Production company management system featuring distinct dashboards and functionalities to enhance team productivity. 

### IMDB's Non-Commercial Data Visualization Projects
**Report:** [Data + Movies IMDb Visualization.pdf](https://drive.google.com/file/d/1t1qwZF6Rwixkg9xAMKxF8RB__mUOy22J/view?usp=sharing)

**Tableau:** [Data + Movies: IMDb's Non-commercial Dataset Visualization](https://public.tableau.com/views/DataMoviesIMDbVisualization/Page01?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**Goal:** Building IMDbs data warehouse and analyzing movie trends based on several aspects, such as, not limited to, genres, ratings, and year.

**Description:** This project involved all data lifecycle, including gathering data that was needed, performing ETL process to load IMDb data to the database, designing a star schema for the data warehouse, creating data marts to help analysis, and building an interactive dashboard using Tableau to visualize findings.

**Skills:** ETL process, Data Cleaning, Data Visualization, Data Analysis, Tableau, PostgreSQL.

**Result:** An interactive dashboard that provides data-driven insights, helping with decision-making and offering appealing visualizations. The dashboard includes analysis of the average ratings and runtime over the decades, showing that the ratings and runtime of movies have increased from the 1900s to the present.

### Hybrid OLAP (HOLAP) Data Warehouse for DVD Rental Store System
**Report:**

**Looker Studio:**

**Goal:** Implement a Hybrid Online Analytical Processing (HOLAP) data warehouse system for a DVD rental service to analyze customer rental behavior patterns. The analysis aims to provide quick and comprehensive insights to support decision-making in improving operational and service efficiency.

**Description:** The project proposes implementing HOLAP in a data warehouse for a DVD rental service. HOLAP is chosen for its combination of fast data access (MOLAP) and its flexible storage (ROLAP). The data used is from an extended Sakila database and processed using Apache Airflow, Hive, and Google BigQuery. A constellation schema is designed to support multidimensional analysis. Then, the results are visualized in a dashboard to identify rental trends, rush hour, and customer behavior.

This system is designed to handle big data efficiently and provide a flexible and responsive analytical environment.

**Skills:** Data warehouse, Apache Airflow, Apache Hive, Google Cloud Storage, Google BigQuery, ELT, Python, Looker Studio, HDFS, SQL.

**Results:** 
1. The data is successfully integrated into Hive, and then from Hive to BigQuery by using Apache Airflow as the tool.
2. Successfully transformed the original database into a data warehouse constellation schema, allowing multidimensional analysis.
3. The HOLAP implementation on this service successfully handles large data volumes and provides a flexible environment for analysis.
4. The dashboard created with Looker effectively visualized data in analyzing customer rental behavior patterns.
5. Based on the data,
   - January had the highest total DVD rental, making the month the peak rental month.
   - The web and mobile platforms are used almost equally by the customers, with 54% and 46% for each.
   - Good, Damaged, and Lost conditions for returned DVDs were almost equally distributed. By this findings, the company needs to review their terms and conditions, or also give customers instructions on how they should take care of the DVD so that the damaged and lost conditions can be decreased.

### Hybrid Hashing and Neural Network Model for Robust Data Security in Detecting Suspicious Activities on Ethereum Transactions

**Report:**

**Goal:** The main goal of this project is to propose a hybrid model combining the SHA-256 hashing algorithm with a Long Short-Term Memory (LSTM) neural network to enhance data security in detecting anomaly activities in Ethereum transactions.

**Description:** This hybrid model integrates the SHA-256 hashing algorithm with a Long Short-Term Memory (LSTM) to enhance data security on Ethereum transactions. The LSTM model is used to detect anomaly patterns in transactions based on the numerical features, while hashing is applied to verify data integrity by matching computed hashes with reference hashes. The dataset is first processed through normalization, handling class imbalance using SMOTE, and evaluated using accuracy, precision, recall, and F1-score metrics. Then we do a simulation via Postman to demonstrate practical application in transaction classification and data verification.

**Skills:** Machine Learning, Python, Blockchain concepts, API, Database, Hashing Algorithm

**Results:**
1. Model achieved 97% accuracy in identifying fraudulent transactions
2. The model also demonstrated a high recall value, indicating its effectiveness in correctly identifying fraud cases.
3. SHA-256 algorithm was successfully used to create unique 256-bit hashes for key transaction features (Address, Total Ether sent, Total Ether received, Time Diff between first and last (Mins), Unique Sent To Addresses, Unique Received From Addresses), serving as digital fingerprints for data integrity checks.
4. The LSTM model showed strong classification performance with:
    - Label 0 (Non-Fraud): 99% Precision, 97% Recall, 98% F1-Score.
    - Label 1 (Fraud): 90% Precision, 95% Recall, 93% F1-Score.
5. The model correctly classified 1,501 non-fraud transactions and 401 fraud transactions. There were 46 false positives (non-fraud classified as fraud) and 21 false negatives (fraud classified as normal).
6. Simulations conducted via Postman successfully demonstrated:
    - Suspicious Activity Classification: The system accurately classified transactions as "fraud" with a prediction score.
    - Data Integrity Verification: The system recalculated and compared hashes, confirming "Data Unchanged" for verified transactions.

### Integrated AI Framework for Lung Cancer Patient Risk Prediction and Treatment Approaches

**Goal:** The goal of this research is to determine the health risk level of lung cancer patients by implementing an integrated artificial intelligence (AI) system. The system will analyze patient medical data (including health history, habits, and cancer stage) to provide a personalized risk level and identify appropriate treatment methods, ultimately reducing the potential mortality rate.

**Description:** The system utilizes a Support Vector Machine (SVM) with a one-to-rest approach to analyze patient medical data. The data, sourced from Kaggle, undergoes extensive preprocessing (null/duplicate checking, data transformation, outlier checking, data balancing, and the addition of a 'risk_level' column based on predefined criteria: 'high', 'medium', 'low'). Feature selection is performed to identify the 9 most correlated parameters to prevent overfitting. The data is then split into 80% training and 20% testing sets. Hyperparameter tuning using GridSearchCV is applied to optimize the model's performance. The model's performance is evaluated using metrics such as Precision, Recall, F1-score, Accuracy, and ROC-AUC curves. The project highlights the importance of AI in clinical decision support and improving patient care for lung cancer.

**Skills:** Artificial Intelligence (AI), Machine Learning (ML), Data Preprocessing, Data Analysis, Project Research.

**Results:**
1. The model achieved an accuracy of 95% in predicting lung cancer risk levels after feature selection and hyperparameter tuning. This is an improvement compared to using all 38 features (93% accuracy).
2. The model showed an excellent ROC-AUC value of 98% for all three risk classes ('low', 'medium', 'high'), indicating its strong ability to differentiate between these categories.
3. The process of selecting the top 9 most correlated features significantly improved the model's accuracy and reduced the risk of overfitting.
4. Performance per class after tuning:
    - Class 0 (Low Risk): Precision 0.96, Recall 0.94, F1-score 0.95.
    - Class 1 (Medium Risk): Precision 0.98, Recall 0.98, F1-score 0.98.
    - Class 2 (High Risk): Precision 0.82, Recall 0.91, F1-score 0.86.
      
The high accuracy and discriminative power of the model demonstrate its potential to assist doctors in diagnosing the severity of lung cancer and support personalized treatment decisions, potentially leading to earlier intervention and reduced mortality rates. Specific treatment recommendations are provided for each risk level (low, medium, high).

## Education
Universitas Sebelas Maret, Bachelor's degree, Data Science, 2023-2027

## Certificates
The best way to showcase skills is by doing and sharing your job done, but sometimes certificates appear as an indirect result. Here's a list of the ones I have:
- [What is Data Science?](https://coursera.org/share/9d0d2e0cc16cd11e3439ebd8d014db60) (August 2024) Coursera - IBM
- [Tools for Data Science](https://coursera.org/share/a4fa93f94b226147a7191cbe722f7cf7) (August 2024) Coursera - IBM)
- [Data Science Methodology](https://coursera.org/share/06f04150ef83f374e72332949f0c80f7) (September 2024) Coursera - IBM
- [R Fundamental for Data Science](https://academy.dqlab.id/certificate/pdf/DQLABINTR1SHGRID) (September 2024) DQLab
-  [Membuat Data Warehouse Untuk Arsitek Database (Data Engineer)](https://skillacademy.com/sertifikat/3OFC1185YJW94O) (October 2024) Skill Academy by Ruangguru
- [Python Project for Data Science ](https://coursera.org/share/b1326e20974d313a18c54aa9eb9d26ab)(January 2025) Coursera - IBM
  
## Contacts
- Linkedin: [@asyifadhilah](https://www.linkedin.com/in/asyifadhilah/)
- Email: asyifadhilaah@gmail.com
