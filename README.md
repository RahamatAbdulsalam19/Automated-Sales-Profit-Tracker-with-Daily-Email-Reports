##  Project: Automated Sales Profit Tracker with Daily Email Reports

###  Overview

This project automates daily profit tracking for online sellers using **Google Sheets** and **Apps Script**. It provides real-time insights into actual profitability by factoring in marketplace commissions, shipping costs, and ad spend metrics that are often ignored in raw revenue dashboards.

###  Problem

Most small e-commerce sellers monitor revenue but struggle to calculate **true profit** after deductions such as commissions, logistics, and advertising. This lack of visibility makes it difficult to measure performance and make informed pricing or marketing decisions.

###  Solution

I built an automated system that integrates data, analytics, and reporting in a single workflow:

* Imports daily sales data (from Amazon/Etsy CSVs or dummy datasets).
* Applies formulas to calculate net profit after marketplace commissions, shipping costs by region/dimension, and manual ad spend inputs.
* Generates a **Daily Summary** sheet with consolidated totals and a dynamic profit-over-time chart.
* Uses **Google Apps Script** to automatically:

  * Retrieve yesterday’s total profit.
  * Export the latest chart as an image.
  * Send a **Daily Profit Report** email at 8:00 AM with the chart embedded and profit summary included.

###  Technical Implementation

* **Tools:** Google Sheets · Google Apps Script · Gmail Service · Automation Triggers
* **Structure:**

  * **RawData Sheet:** Base sales input (orders, price, quantity, region).
  * **Calculated Sheet:** Commission and cost computations.
  * **Config Sheet:** Adjustable rates and settings.
  * **Daily Summary Sheet:** Final profit table and chart visualizations.
* **Automation:** Apps Script runs on a scheduled trigger to fetch, summarize, and email daily reports automatically.

###  Results & Impact

The solution delivers a **clear, daily snapshot of business profitability** without manual calculation. Sellers can instantly see whether they were profitable the previous day, enabling faster decision-making on marketing spend and pricing.

> “Gives sellers a clear profit snapshot every morning — no more guessing if yesterday was actually profitable.”

###  Portfolio Visuals

1. **Profit Table:** Daily Summary sheet displaying calculated profit metrics.
2. **Profit Trend Chart:** Visualization of profit growth over time.
3. **Email Report:** Automated morning report with embedded chart and total profit.

