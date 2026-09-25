#  PhonePe Pulse Data Analytics Dashboard


**PhonePe Pulse Data Analytics Dashboard** is an executive-level data visualization project built using **Power BI**. The dashboard analyzes financial metrics, transaction trends, geographic growth, and technical failure reasons across a dataset of **10.51M INR total value** generated from **1.5K transactions** by **297 unique users**.

---

##  Data Source & Processing
* **Data Source:** Sourced from real-world PhonePe Pulse metrics tracking digital payments, transactional logs, and user demographics.
* **Data Cleaning & ETL:** Conducted end-to-end data processing, missing value treatments, and cross-table modeling using **Power Query** within Power BI to ensure calculation integrity.

---

##  Dashboard Structure & Pages

The dashboard is categorized into 5 highly interactive sections:
1. **Overview Page:** Displays high-level KPIs including Total Transaction Amount, Average Value (6.61K INR), and interaction curves broken down by App Platform and regional metrics.
2. **Geographic Insights:** Focuses on state-wise metrics identifying Delhi as the top state for transaction volumes, followed closely by Gujarat and Bihar.
3. **Transaction Trends:** Tracks behavioral data revealing that **Peer-to-Peer (P2P)** transfers are the highest drivers at **3.67M INR**, while card, UPI, and wallet forms maintain equal user adoption.
4. **Performance & Failure Analysis:** A deep-dive diagnostic dashboard parsing system performance. It highlights a healthy **85.27% overall success rate** and monitors transaction bottlenecks.
5. **Executive Summary:** A final textual data-driven wrap-up page presenting consolidated business metrics for executive stakeholders.

---

##  Key Business Insights

* **Platform Dominance:** Android captures **74% of the app platform share**, although iOS users display high transactional frequency relative to their lower user volume.
* **Category Drivers:** **Peer-to-Peer** transfers are the primary revenue generator (3.67M INR), followed closely by strong performance in Travel Bookings and Insurance.
* **Seasonality Trends:** Transaction numbers peak heavily during Q1 and Q2, but undergo a sharp downward drop post-August.
* **Technical Failure Bottlenecks:** System analytics isolate **"Bank Server Down"** as the #1 operational issue driving failed payments, followed by user-end issues like "Incorrect UPI PIN" and "Network Timeouts."

---

##  Technologies Used
* **Power BI Desktop** (Data Modeling, Dashboard Design & UX Layout)
* **DAX** (Data Analysis Expressions for time-series forecasting, custom KPI counts, and success rates)
* **Power Query** (Data Cleaning, Transformation & ETL operations)

---

##  Key Learnings
* Building comprehensive performance-monitoring fintech dashboards.
* Tracking infrastructure stability alongside revenue metrics (Success vs. Failure analytics).
* Implementing cross-filtering and demographic segmentation to drive targeted marketing insights.
