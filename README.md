Solar Installation Intelligence Tracker

A live Business Intelligence dashboard built to manage project pipelines, track provincial demand, and monitor financial health for a renewable energy installation company.

🔗 **Live Interactive Dashboard (Looker Studio):** [View Live Dashboard](https://datastudio.google.com/s/gmHmJkxt0xg)

Why I Built This
Solar installation companies manage dozens of simultaneous projects across different stages (Proposal, Installation, Maintenance) and provinces. Without a centralized data system, tracking the financial gap between total costs and revenue received becomes a nightmare. I built this pipeline to give management a real-time, mobile-friendly view of their entire operational health.

The ETL Pipeline (How it works)
1. **Data Collection (Extract):** Project managers update project details, costs, and revenue via a Google Form.
2. **Storage:** The raw data is stored in a Google Sheet.
3. **Data Cleaning (Transform):** A custom Google Apps Script standardizes the data (e.g., fixing province names, calculating profit/loss) and pushes it to a processed sheet.
4. **Visualization :** Looker Studio connects to the clean data, updating the dashboard instantly.

Key Dashboard Features
*   **Active Project Pipeline Table:** Tracks 28 active projects, filtering by province, project stage, total cost, and revenue received.
*   **Provincial Demand Pie Chart:** Visually maps where the highest demand is coming from (e.g., 94.2% Gauteng).
*   **Weekly Financial Analysis:** Bar charts comparing Total Cost vs. Revenue Received on a weekly basis.
*   **Profit/Loss Monitoring:** Clear KPI cards that immediately flag if the company is operating at a loss for the week (e.g., -R55,000.00), allowing management to act fast.

Screenshots
<img width="410" height="598" alt="Screenshot from 2026-11-20 04-26-51" src="https://github.com/user-attachments/assets/87a7300b-4714-4963-b1f2-48eee70d9005" />
<img width="410" height="598" alt="Screenshot from 2026-11-20 04-29-14" src="https://github.com/user-attachments/assets/fb05f929-c534-4574-9757-d0bb71bb9a0f" />



Built by Setlhako N.C.
