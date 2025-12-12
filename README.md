# 📜 Bellabeat Strategic Transition: Final Analysis Report 📜

## &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; How Can a Wellness Technology Company Play It Smart?
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

This analysis was executed using a rigorous methodology, prioritizing **complex data processing** and aggregation techniques to achieve temporal consistency.

### Technologies & Analysis Used

| Category | Tools | Kind of Analysis Used |
| :--- | :--- | :--- |
| **Data Manipulation** | SQL, Excel Desktop | ETL (Extract, Transform, Load), Data Aggregation, Filtering, Data Type Conversion. |
| **Data Visualization** | Excel, PowerPoint, Google Slides | Exploratory Data Analysis (EDA), Trend Analysis, Comparative Analysis. |
| **Analysis** | Excel, Google Data Analytics Framework | **Diagnostic Analysis**, Statistical Summaries, Pattern Identification (Churn Rate). |

### Google Data Analytics Framework

The project followed the **Google Data Analytics Life Cycle** , which ensures a structured, iterative, and solution-oriented approach:

* **Ask:** Defining the business problem and stakeholders.
* **Prepare:** Collecting and storing data.
* **Process:** Cleaning and transforming data (Crucial in this project).
* **Analyze:** Identifying patterns and trends.
* **Share:** Communicating findings effectively.
* **Act:** Applying recommendations to drive business strategy.

### Critical Methodology Highlights

* **Data Transformation & Temporal Consistency:** We performed a rigorous transformation process, including the **deletion of nearly 50% of duplicated records** and **zero-imputation** for missing hourly entries to ensure temporal consistency, which was critical for habit tracking.
* **Addressing Data Limitations:** The analysis faced **multiple inherent limitations** due to the third-party nature of the dataset. To ensure findings were robust and market-relevant, we mitigated these limitations by incorporating **external market validation**, including **Industry Churn Reports** (e.g., Flurry Analytics) and **Digital Fitness Benchmarks** (analysis of UX/gamification metrics from competitors like Oura and Apple Fitness). This external data was used to validate the identified 8-12 Day Churn pattern.
* **Aggregation Bias:** To create usable daily averages (e.g., `Avg_MinutesAsleep`), data consolidation was necessary. We acknowledge that this process introduced an **aggregation bias** (loss of individual variance), which led the strategy to focus on **group-level behavior intervention** (like Nudges and Campaigns) rather than extreme personalization.
---

## 💡 Key Findings & Strategic Insights 💡

The analysis yielded three non-obvious insights that collectively drive the final strategic recommendations:

1.  **Habit Failure is the Core Problem:** Inconsistency is pervasive, resulting in a **71% drop-off** clustered in the hyper-sensitive **8-12 Day churn window**. This problem is compounded by the **Total Calories metric** being structurally ineffective for motivation due to **BMR dominance**, proving a fundamental flaw in habit formation.
2.  **Recovery is the Untapped Market:** A vast **91% Sleep Deficit** exists among users. This lack of recovery is crucial because the analysis proves a **direct dependence:** the small segment of High\_Sleep users accounts for the overwhelming **majority (89%)** of high-intensity activity.
3.  **Targeted Intervention is Necessary:** Weekly usage patterns show significant **inactivity gaps** (e.g., weak engagement on Tuesday) and **sedentary peaks** forced by work/commuting hours. This requires a strategy focusing on tactical intervention during optimal activity windows (Wednesday and Saturday) to reinforce habit formation.
---

## 🌟 Proposed Strategy 🌟

The final strategy recommends a pivot in the **Bellabeat App's** value proposition from simple activity tracking to a focus on **consistency and restorative recovery (sleep)**. This strategy is segmented into three phases to maximize long-term growth.

### 🎯 Defining Growth Opportunities

In the context of marketing strategy, **growth opportunities** extend beyond simple sales increases. For Bellabeat, they represent the sustainable expansion of the company's value and reach by:
1. **Maximizing LTV:** Preventing high user churn in critical early-use windows.
2. **Developing Value:** Creating new, premium features that leverage Bellabeat’s unique focus on women's health.

### Recommended Strategic Phases

| Element | Content | Stakeholder Action |
| :--- | :--- | :--- |
| **PHASE 1: Metric Correction & Positioning Pivot** | Abandon **Total Calories**. Replace it with Active Calories or Avg. METs (validated by a high 0.97 correlation to Heart Rate). Product Repositioning: Launch a Premium Readiness Score (or Recovery Score) based on sleep quality to capitalize on the 95% deficit. | Product Team, Marketing/Branding |
| **PHASE 2: User Habit & Retention** | **Habit Campaign:** Implement a compulsory 30-Day Habit Campaign to push users past the 8-12 Day churn window. **Tactical Nudge:** Utilize 7:00 PM push notifications (the user's peak activity window) to prompt sleep logging, directly reinforcing habit formation. Launch a Post-Churn Survey for Strategic Validation and Risk Mitigation. | Growth/Retention Team, UX/Engineering |
| **PHASE 2: Strategic Weekly Intervention** | Launch a Dynamic, Compensatory Nudge Cycle: Implement gamified incentives (e.g., access to premium content or reward plans) to incentivize usage on low-inertia days and to foster active compensation during peak workday sedentary hours. | Marketing/Product Team |
| **PHASE 3: Differentiation** | Capitalize on Niche: Integrate advanced features focused on women's health, linking Recovery to **Menstrual Cycle Syncing**. This utilizes the core advantage of the Bellabeat brand to secure differentiation from competitors. | Product Team, R&D |

## Authors

* **[Your Name]** - **Data Analyst** - All phases of the project: Data Cleaning, Exploratory Data Analysis, Strategic Recommendation, and Final Report Generation.
    * **Email:** [Your Professional Email]
    * **GitHub:** [Your GitHub Profile URL]

## License

This project is intended for portfolio demonstration and learning purposes. It is covered under the **MIT License**.
