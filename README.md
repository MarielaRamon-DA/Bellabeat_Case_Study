# 📜 Bellabeat Strategic Transition: Final Analysis Report 📜

##            How Can a Wellness Technology Company Play It Smart?

![Bellabeat Logo or Project Header](images/Bellabeat_logo.jpg)

## 👁️ Project Overview 👁️

This analysis was conducted as a **Junior Data Analyst** on the Marketing team at **Bellabeat**, a high-tech manufacturer of health products for women. 

The project was mandated by the executive team to analyze third-party smart device data and uncover consumer habits. The primary goal was to transform these insights into a refined **marketing strategy for the Bellabeat App**, focusing on leveraging its comprehensive health data (activity, sleep, stress, etc.). The final recommendations aim to maximize the app’s value proposition and unlock new growth opportunities in the global smart device market.

---
## 🔗 Key Deliverables & Resources 🔗

| Resource | Description | Link |
| :--- | :--- | :--- |
| **Interactive Report (Code)** | Published Kaggle Notebook containing the complete code, analysis narrative, and visualizations. | [View Published Kaggle Notebook](https://www.kaggle.com/code/marielaramoncorria/bellabeat-notebook) |
| **Executive Presentation** | Final Google Slides presentation summarizing strategic recommendations for leadership. | [View Executive Slides](https://docs.google.com/presentation/d/e/2PACX-1vTn0YeQQGLqyjmwCyo1NOmeXuaeBvzwR1Fyl6TX0IUc4DZgm6V-4i018ocKpJUX2nBZy8NZYEgl0siX/pub?start=true&loop=false&delayms=3000&present) |
---

## 🛠️ Tools & Methodology 🛠️

This analysis was executed using a rigorous methodology, including complex data cleaning and aggregation techniques.

### Technologies Used

| Category | Tools |
| :--- | :--- |
| **Data Manipulation** | SQL, R, Spreadsheets (for ETL) |
| **Data Visualization** | Tableau |
| **Analysis** | R (for statistical analysis), Google Data Analytics Framework |

### Critical Methodology Highlights

* **Data Integrity & ETL:** We performed a rigorous cleaning process, including the **deletion of nearly 50% of duplicated records** and **zero-imputation** for missing hourly entries to ensure temporal consistency, which was critical for habit tracking.
* **Aggregation Bias:** To create usable daily averages (e.g., `Avg_MinutesAsleep`), data consolidation was necessary. We acknowledge that this process introduced an **aggregation bias** (loss of individual variance), which was factored into our strategic recommendations.

---

## 💡 Key Findings & Strategic Insights 💡

The analysis yielded several non-obvious insights that drive the final strategic recommendations:

1.  **Critical Churn Window:** The most significant user abandonment occurs in the **8–12 day window** of initial use, pointing to a failure in early habit formation.
2.  **Structural Metric Failure:** A key finding that differentiates this analysis is the discovery that the **Basal Metabolic Rate (BMR) dominates the Calorie metric**. This renders the "Total Calories" metric ineffective for motivating true behavioral change.
3.  **Untapped Market Opportunity:** The **sleep/recovery deficit** was identified as the key performance indicator for driving high-intensity activity, representing the largest opportunity for Bellabeat's future product strategy.

---

## 🌟 Proposed Strategy 🌟

The report recommends that Bellabeat migrate its value proposition to a model that **rewards usage consistency** and focuses on **monetizing recovery (sleep)**, shifting the competitive landscape away from simple step counting.

## Authors

* **[Your Name]** - **Data Analyst** - All phases of the project: Data Cleaning, Exploratory Data Analysis, Strategic Recommendation, and Final Report Generation.
    * **Email:** [Your Professional Email]
    * **GitHub:** [Your GitHub Profile URL]

## License

This project is intended for portfolio demonstration and learning purposes. It is covered under the **MIT License**.
