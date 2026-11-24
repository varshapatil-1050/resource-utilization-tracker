# resource-utilization-tracker
resource-management |utilization| power-bi |excel |power-query| pivot-tables| dax| forecasting data-analysis
# Resource Utilization & Availability Tracker

Personal project built with sample data. All employees, clients and
projects are fictional.

## What it does
Tracks how busy each person is, who has free capacity, and who is
over-booked, the same kind of work a resource management team does.

## Data
- 20 sample employees, 8 projects, 12 weeks (8 past, 4 planned)
- 7,724 booked hours in total
- 40 hours per week capacity per person

## What I built
- Excel: utilization % and available hours using SUMIFS and
  INDEX/MATCH, conditional formatting for over-allocation (above
  100%), a 4-week availability forecast, and Pivot Tables
- Power Query: loaded and merged the schedule, employee and
  project tables
- Power BI: KPI cards, a weekly utilization matrix with red alerts
  above 100%, a utilization trend line, and an available-hours chart

## Key results (sample data)
- Team utilization: about 84% (past weeks), 73% (next 4 weeks)
- 4 people over-allocated in the next 4 weeks
- 942 available hours in the next 4 weeks

## Screenshots
![Dashboard](screenshots/dashboard.png)

## Files
- Resource_Utilization_Tracker.xlsx: Excel model
- Resource_Utilization_Dashboard.pbix: Power BI report
- Resource_Utilization_Dashboard.pdf: dashboard export

## Tools
Excel, Power Query, Pivot Tables, Power BI (DAX)

## Screenshots


