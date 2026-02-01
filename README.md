# Finance Navigator Pro – Loan Portfolio Dashboard

An interactive Tableau dashboard suite for analyzing loan applications, funding performance, risk (good vs. bad loans), and key metrics in a consumer lending business.

Built with Tableau Public/Desktop using a Lending Club-style loan dataset (~38K applications).

## Project Overview
This portfolio project visualizes critical lending KPIs to help stakeholders monitor:
- Total applications, funded & received amounts
- Month-over-Month (MoM) and Month-to-Date (MTD) trends
- Good vs. Bad loan performance (86% good issuance rate in this dataset)
- Breakdowns by purpose, state, term (36/60 months), employee length, home ownership, grade, verification status
- Detailed loan-level table with filters

Three main views:
- **Summary**: High-level KPIs, good/bad loan donuts, loan status table
- **Overview**: Trends over time, geographic map, term/purpose/employee breakdowns
- **Details**: Granular loan records table with filters

## Screenshots

### Summary Dashboard
![Summary Dashboard](summary_dashboard.png)

### Overview Dashboard
![Overview Dashboard](overview_dashboard.png)

### Details View
![Details Table](details_table.png)

## Live Interactive Version
View and interact with the full dashboards on Tableau Public:

- [Finance Navigator Pro | Summary](https://public.tableau.com/views/TableauPartofProjectRAJ/Summary?:language=en-US&:display_count=n&:origin=viz_share_link)
- Overview and Details views: Add links here if separate, or note they are in the same workbook (use the tabs)

> **Tip**: Click the views above → use filters (Purpose, Grade, Verification, etc.) for deeper exploration.

## Files in this Repository
- `Finance_Navigator_Pro.twbx` → Packaged Tableau workbook (download and open in Tableau Desktop or Public)
- Screenshots (PNG files) for quick preview
- README.md → This file

## How to Use
1. Download the `.twbx` file from this repo.
2. Double-click to open in Tableau Desktop (free trial) or Tableau Public.
3. Explore filters, tooltips, and interactions.
4. If you only want to view: Use the Tableau Public links above—no download needed.

## Tech Stack
- **Tool**: Tableau (Public/Desktop)
- **Dataset**: Anonymized loan data (~38.6K records) – similar to Lending Club public dataset
- **Key Visuals**: KPIs cards, donut charts, line trends, US map, bar charts, filtered table

## Key Insights (from the dashboard)
- Total applications: 38.6K | Funded: $435.8M | Received: $473.1M
- Good loans: 86.2% of funded amount ($370M+)
- Bad loans (Charged Off): 13.8% ($65.5M funded)
- Average interest: 12.05% | Average DTI: 13.3%
- Most loans: 60-month term (73%), debt consolidation purpose, rent home ownership
- Fully Paid dominates current status

## License
MIT License – feel free to use for learning/portfolio purposes (data & viz are anonymized).
