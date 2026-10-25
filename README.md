# support-mis-dashboard-excel
# Support Operations MIS Dashboard (Excel)

An automated MIS report built on a synthetic customer-support ticket dataset.

## Problem
Support managers need a quick view of ticket volume, SLA performance and agent
productivity without rebuilding reports by hand each day.

## Tools
Excel, Power Query, PivotTables and slicers, VBA

## Dataset
Synthetic data: 5,000 tickets, 15 agents, Jan-Mar 2025. No real company data.

## What I built
- Cleaned the raw data in Power Query (fixed agent names, removed 15 duplicates)
- KPI cards: total tickets, average resolution time, SLA %, SLA breaches
- Charts: tickets per day, SLA % by agent, tickets by category, resolution time by priority
- Slicers for month, agent and category
- VBA macros to refresh the report and export it as a dated PDF

## Key findings
- Overall SLA compliance: 80.6% (972 breaches out of 5,000 tickets)
- SLA compliance varies widely by agent, from about 62% to 96%
- Delivery Delay is the largest ticket category

## Screenshots
![Dashboard](screenshots/dashboard.png)

## How to use
Open the .xlsm file, enable macros, and click Refresh Report.
