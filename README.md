### Bright Learn Viewership Analysis

📊 Project Overview

Dashboard https://blviewershipanalysis.lovable.app/

# 📺 Bright Learn Project | Viewership Analytics Case Study

This project presents an executive-level viewership analysis for the **Bright Learn Project**, built to inform product, content, and platform strategy for leadership.

As a **Data Analyst**, the objective was to break down platform usage, audience engagement tiers, day-of-week and quarterly viewing patterns, content behavior, and play-event mix across **64,610 total viewing hours** and **108,661 active customers**, and translate that into a concrete set of strategic recommendations.

---

## 🎯 Project Objectives

This analysis focuses on answering critical executive business questions:

* **Platform Performance:** Which platforms (Leanback/CTV, Web, iOS, Android) drive the most hours, customers, and per-user engagement?
* **Audience Composition:** How is the customer base distributed across Light, Occasional, Regular, and Heavy engagement tiers?
* **Temporal Behavior:** How does viewing volume shift across the days of the week, and what does that mean for scheduling?
* **Content Discovery:** How much viewing goes to known catalog titles versus generic/undirected browsing, and does that shift on weekends?
* **Growth & Retention Signals:** What does the Q4 2020 → Q2 2021 quarterly trend reveal about acquisition spikes versus sustained retention?
* **Consumption Mode:** How much of total viewing activity is Live TV versus Catch Up versus other on-demand behavior?

---

## 📊 Key Executive Findings & Insights

* **Total Reach & Scale:** **64,610** total viewing hours across **108,661** active customers, with **66.6%** of the audience sitting in the Heavy engagement tier (200+ sessions).
* **Platform Concentration:** **Leanback (CTV)** leads decisively, capturing **68%** of all hours (44,010 of 64,610) and **66%** of customers (71,525 of 108,661).
* **Engagement Efficiency by Platform:** **Web** delivers the deepest per-user engagement at **0.70 hrs/customer**, ahead of Leanback's 0.62, despite carrying only 23% of hours; **mobile is under-indexed**, with iOS and Android holding 15% of customers but just 9% of hours.
* **Power-User Base:** **72,320 customers (66.6%)** fall into the Heavy tier, and **94%** of the base sits in Regular or Heavy tiers combined — a retention story, not an acquisition one.
* **Weekly Rhythm:** Viewing climbs steadily from **8,181 hours Monday** to a peak of **10,244 hours Sunday** (+25%), with weekends outperforming weekdays by **12.7%** and Friday already running **3.6%** above the Mon–Thu average.
* **Catalog vs. Browsing:** Known catalog titles hold a stable **67.4%** share of hours on both weekdays and weekends; roughly **a third of all hours remain undirected**, pointing to a discovery/personalization gap.
* **Quarterly Trend:** Hours grew **more than 10x**, from **4,965 (Q4 2020)** to **50,173 (Q1 2021)**, before retreating to **9,473 (Q2 2021)** — still nearly double the Q4 2020 baseline, suggesting partial retention of newly engaged viewers. *Flagged for validation: confirm date-range consistency across quarterly buckets.*
* **Consumption Mode:** **Live TV drives 74%** of all play events, **Catch Up captures 15%**, and downloads/offline viewing remain negligible.

---

## 🛠️ Tools & Technologies

* * **Databricks:** Data staging, cleansing, and transformation of the underlying viewership dataset.
* **SQL:** Analytical queries, aggregations, and metric calculations across platform, engagement-tier, day-of-week, content-type, quarterly, and play-event dimensions.
* **Excel:** Data validation, pivot summaries, and supporting calculations behind the headline KPIs.
* **Power BI:** Interactive report build-out and chart visualization (bar, column, line, and donut charts) covering platform share, audience segments, weekly trends, catalog behavior, quarterly performance, and play-event mix.
* **Interactive Web Dashboard:** Custom-built dashboard for executive review (Bright Learn brand theme — Navy `#1B2A5E` & Amber `#F5A623`).
* **PowerPoint:** Executive presentation deck, structured insight-by-insight with a dedicated recommendations closing section.
* **Miro:** Project scoping, data architecture planning, and workflow mapping.
* **Gantt Chart:** Project planning and timeline tracking across analysis phases and deliverable milestones.

---

## 📦 Project Deliverables

1. **Executive KPI Dashboard:** Six headline metrics summarizing scale, engagement mix, and consumption behavior at a glance.
2. **Six Insight Breakdowns:** Platform share, audience segment mix, day-of-week behavior, catalog vs. generic browsing, quarterly trend, and play-event share.
3. **Interactive BI Dashboard:** [https://blviewershipanalysis.lovable.app/](https://blviewershipanalysis.lovable.app/)
4. **Executive Recommendations:** Six action items covering CTV investment, mobile re-engagement, heavy-viewer retention, discovery/personalization, weekend programming, and Catch Up expansion.

---

## 💡 Demonstrated Skills

* **Data Analysis & Insight Generation**
* **Audience Segmentation & Engagement Modeling**
* **Data Visualization & Dashboard Design**
* **Trend Analysis & Anomaly Flagging**
* **Executive Communication & Strategic Recommendations**

###Data Coverage & Known Limitations

***Date Range

***The source dataset (Viewership Analysis.xlsx) covers 1 November 2020 – 16 April 2021 only. No data exists for any period outside this range, including Q3 2020 (July–September). This is not a data loss issue — the source file was never provided with Q3 data, so this reflects the actual scope of the extract received, not a processing error.

***Action required: If Q3 2020 (or any period outside Nov 2020–Apr 2021) is needed for reporting, this must be requested as a separate extract from the source system/owner.

#Missing Date

***Within the available range, 1 December 2020 has no viewership records, despite every other day in the sequence being present (166 of 167 expected calendar days). This gap exists in the original source file and was not introduced during ingestion or processing.

***Impact: Any day-over-day, weekly, or rolling analysis that spans this date may show an artificial dip. This has no material effect on the overall trend findings in this analysis but should be noted if building further reports on early December 2020.
