# Digital Campaign ROI Optimization & Conversion Analytics

Analyzed 600K+ rows of Meta Ads data (Facebook & Instagram) to evaluate campaign performance, identify a conversion drop-off, and recommend budget reallocation strategies.

---

## Tools Used

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## The Problem

A business was running paid campaigns across Facebook and Instagram with a sizeable budget of 2.5M but had no clear visibility into why their spend was not converting into purchases.

The surface metrics looked acceptable — impressions were deep, clicks were coming in. But nobody had looked at the full funnel. When I mapped it end-to-end, the gap was stark: an 11.76% CTR was collapsing to a 0.61% purchase rate. That is not a creative problem or an audience problem. That is a structural budget allocation and targeting problem that no one had diagnosed.

The business needed to know exactly where the money was leaking, which audiences and ad formats were actually driving value, and where to shift budget to fix the conversion gap.

---

## What I Did

- Cleaned and transformed raw Meta Ads data using SQL, improving query efficiency by 30%
- Built a Star Schema data model with 4 tables (ad_events, ads, campaigns, users)
- Created 12+ DAX measures in Power BI — CTR, CVR, Engagement Rate, ROAS, CPC, and more
- Identified a critical drop-off: 11.76% CTR collapsing to 0.61% purchase rate
- Recommended budget reallocation that drove 8% higher CTR

---

## Key Numbers

| Metric | Value |
|---|---|
| Impressions | 216K |
| Clicks | 25.4K |
| CTR | 11.76% |
| Engagement Rate | 13.56% |
| Conversion Rate | 5.21% |
| Purchase Rate | 0.61% |
| Total Budget | 2.5M |


---

## Main Findings

- Video ads had the best performance across CTR (11.9%), CVR (5.2%), and Engagement Rate (13.7%)
- Female users drove 43% engagement vs 22% for males — clear targeting opportunity
- Peak hours: 15:00–20:00 | Peak days: 19th–21st and 25th–27th of the month
- India & Brazil = high volume | Germany & UK = high value conversions

---

## Data Model

Star Schema with one fact table and three dimension tables:

- **ad_events** — fact table with 600K+ rows (event type, cost, timestamp)
- **ads** — ad name, type, creative format
- **campaigns** — objective, budget, date range
- **users** — age group, gender, country, device

---

## Files
```
├── docs/
│   ├── 01_Project_Explanation_Interview.docx
│   ├── 02_Domain_Knowledge_Document.docx
│   ├── 03_Dashboard_Insights.docx
│   └── 04_Business_Requirements_Document.docx
├── dashboard/
│   └── Meta_Ads_Dashboard.pbix
└── data/
    └── (source CSV files)
```


**LinkedIn:** [yashraj33](https://www.linkedin.com/in/yashraj33/) · **GitHub:** [YashINDataYRJ](https://github.com/YashINDataYRJ)



