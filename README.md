🎓 OULAD E-Learning Analytics: Data-Driven Student Success Model
DEPI Graduation Project | Data Analysis Track
This project focuses on transforming the Open University Learning Analytics Dataset (OULAD) into a high-performance analytical environment. As a Data Analyst, my goal was to engineer a robust Star Schema that enables deep dives into student demographics, engagement patterns on the VLE (Virtual Learning Environment), and academic outcomes.

🎯 Project Objective
The primary objective is to analyze the factors affecting student success and retention. By processing raw data through a multi-layer pipeline, I created a clean "Source of Truth" for building interactive dashboards that help educators identify at-risk students.

🏗️ Data Preparation Lifecycle (Medallion Approach)
Even though the focus is analysis, I implemented a structured data preparation process to ensure Data Quality:

Bronze (Raw): Initial ingestion of student and course data.

Silver (Cleansed): Performed advanced data cleaning, including Hierarchical Imputation for socio-economic data (imd_band) and resolving logical gaps in enrollment timelines.

Gold (Curated): Developed the final Star Schema, aggregating millions of rows into a structured format optimized for lightning-fast analysis in Power BI.

📊 Analytical Modeling (Star Schema)
I designed a Dimensional Model consisting of 4 Dimensions and 3 Fact Tables to allow cross-functional analysis between student profiles and their digital footprints.

(Note: Diagram illustrating the relationships between students, assessments, and VLE interactions)

🚀 Key Performance Highlights (Analyst Perspective)
Big Data Handling: Successfully aggregated and analyzed 8.4 Million rows of VLE interaction data, turning "noisy" clicks into meaningful engagement metrics.

Advanced Data Cleaning: Replaced critical NULL values in registration data with logical proxies, ensuring 100% data consistency for retention analysis.

Outcome Focus: Treated final_result as the primary target variable, enabling predictive-style reporting on student performance categories.

🛠️ Toolset & Skills
SQL (T-SQL): Data transformation, aggregation, and complex joins.

Data Modeling: Star Schema design and Dimensional modeling.

Analytics: Handling large-scale datasets and trend analysis.

Visualization: Power BI (Transforming data into insights).

👨‍💻 Developed By
Abdelrahman Ahmed
Data Analyst Trainee
Digital Egypt Pioneers Initiative (DEPI)