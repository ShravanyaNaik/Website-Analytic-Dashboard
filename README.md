# Website Analytics Dashboard

This project presents an interactive **Website Analytics Dashboard** built using **Power BI**, based on a dataset containing website traffic, user behavior, and session-level metrics. The goal is to gain insights into how users interact with a website and to monitor key performance indicators (KPIs) effectively.

---

## Dashboard Features

The dashboard includes the following key performance indicators and visualizations:

### KPI Cards
- **Total Views** – Total number of page views recorded.
- **Average Duration** – Average session duration (in seconds).
- **Bounce Rate** – Number of sessions with a single interaction.
- **Total Countries** – Unique user locations by country.
- **Total Browsers** – Number of browsers used by visitors.
- **Total Traffics** – Total number of sessions/visits.

### Visualizations
- **Total Views by Browser** – Bar chart showing browser-wise page view distribution.
- **Traffic by Country and Browser** – Donut chart breaking down traffic by country and browser.
- **Total Duration by Country** – Tree map representing cumulative session duration by country.
- **Session Duration vs Views by Browser** – Pie chart for comparing session time with browser usage.
- **Top Countries Table** – Tabular view of key metrics per country (duration, traffic, views).
- **Conversion Count vs Non-conversion** – Clustered column chart showing session conversion analysis.

---

## Dataset

- File: `Website_Analytics_Sample_300.csv`
- Rows: 300 (sampled from original 62,000+)
- Fields include: `Country`, `Browser`, `Session Duration (sec)`, `Traffic Source`, `Device`, `Page Views`, etc.

---

## Tools & Technologies

- **Power BI Desktop** – for building and publishing the dashboard
- **CSV (Comma-Separated Values)** – sample analytics data
- **DAX** – used for creating custom calculated measures like average duration

---

## Key Insights

- Chrome and Opera are the most used browsers.
- India and the United States account for the majority of the total traffic.
- Average session duration is **71.59 seconds**.
- Bounce rate and conversion patterns highlight areas for engagement improvement.

---

## How to Use

1. Clone this repository or download the .pbix file.
2. Open it using *Power BI Desktop*.
3. Interact with slicers (Device Type, Browser, Month, Traffic Source) to explore various dimensions.

## Dashboard Preview
![image alt](https://github.com/ShravanyaNaik/Website-Analytic-Dashboard/blob/cd4b1f58bc916eb358a3f78d70ff16335ccc4fe4/Image.png)

