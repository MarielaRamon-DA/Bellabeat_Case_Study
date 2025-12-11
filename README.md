# 📜 Bellabeat Strategic Transition: Final Analysis Report 📜

## How Can a Wellness Technology Company Play It Smart?

![Bellabeat Logo or Project Header](images/Bellabeat_logo.jpg)

## 👁️ Project Overview 👁️

This project investigates the strategic shift required by Bellabeat, a women's wellness company, by analyzing public fitness tracker data. The core goal was to diagnose the primary cause of high user churn and propose a data-driven pivot from generic activity tracking to rewarding **consistency and recovery**. The analysis identified critical issues, including the **structural failure of the Calorie metric** (due to BMR dominance) and the **8–12 day user drop-off window**. The final recommendation centers on monetizing the untapped sleep/recovery deficit.

---

## 🔗 Key Deliverables & Resources 🔗

| Resource | Description | Link |
| :--- | :--- | :--- |
| **Interactive Report (Code)** | Published Kaggle Notebook containing the complete code, analysis narrative, and visualizations. | [View Published Kaggle Notebook] (**INSERT KAGGLE URL HERE**) |
| **Executive Presentation** | Final Google Slides presentation summarizing strategic recommendations for leadership. | [View Executive Slides] (**INSERT GOOGLE SLIDES URL HERE**) |

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
