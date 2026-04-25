# Aviation-Fleet-Sustainment-Dashboard
Interactive Excel Dashboard for tracking aircraft readiness and maintenance cycles for a 50-asset aviation fleet

![Fleet Dashboard Preview](Fleet_Sustainment_Dashboard_Preview.png)

# Project Overview
This project is a dynamic **Fleet Management & Sustainement Tool** designed to provide key insights into aircraft availability and operational efficiency.The dashboard allows to identify maintenance bottlenecks and fuel efficieny gaps across a 50-asset global fleet.


# Quick Links

- Interactive Dashboard:
- Raw Dataset:

# Data Source

- Original Dataset: 


# Tools Used
**Excel:** Data Cleaning, Visualization and Dashboarding

# The Process

## 1.Initial Data Inspection & Preparation (Excel)
- **Visual Audit:** Performed a scan in **Excel** to identify column relationships, data types and obvious data errors.
  
## 2. Advanced Feature Engineering
- **Maintenance Thresholds:** Utilized **XLOOKUP** to assign service interval hours to assets based on Engine Type. Calculated Service Interval Remaing to predict downtime.
- **Operational Logic:** Developed a nested Readiness Status engine with **conditional formatting** for instant visual alerts.
- **Economic Metrics:** Derived Fuel Per Seat to analyze fleet efficiency.
- **Binary Flags:** Implemented a Maintenance Flag to maintain data integrity during multi-use of slicers.
  
## 3. Interactive Visualization
- **KPI development:** Calculated key metrics including **Total Seat Capacity,Operational Readiness Rate, Average Hours to Next Maintenance, and Assets in Maintenance.**
- Developed a **Maintenance Priority** graph to identify assets approching critical maintenance thresholds.
- Built a **Mission Capabiity Breakdown** to track the Operational Readiness Rate (ORR).
- Integrated **Slicers** to allow for multi-dimensional filtering (Airline/Model/Status).
