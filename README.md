# Supply Chain Analytics Dashboard Portfolio

## Overview

This repository showcases a portfolio of business analytics dashboards built with **Python**, **Pandas**, **Jupyter Notebook**, and **Tableau**. The project uses synthetic datasets designed to reflect realistic operational patterns across multiple industries.

The dashboards were developed to demonstrate how analytics can support decision-making in logistics, supply chain operations, and healthcare inventory management.

### Industries Included
- Military logistics operations
- Retail supply chain management
- Healthcare supply chain analytics

---

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- Tableau

---

## Project 1: Military Logistics Operations Dashboard

This dashboard analyzes logistics activity across operational theaters and transportation modes.

### Key Analytics
- Shipment transit time trends
- Carrier mode utilization
- Logistics hub shipment volume
- Equipment readiness distribution
- Units shipped by theater

### Business Value
This dashboard demonstrates how analytics can improve visibility into logistics throughput, readiness, and transportation performance.

![Military Logistics Dashboard](images/military_dashboard.png)

---

## Project 2: Retail Supply Chain Performance Dashboard

This dashboard analyzes a retail distribution network using operational and financial performance metrics.

### Key Analytics
- Revenue trends over time
- Backordered units by category
- Warehouse utilization
- Regional revenue distribution
- Transportation cost per unit

### Business Value
This dashboard highlights how analytics can identify backorder pressure, regional performance differences, and warehouse capacity trends.

![Retail Supply Chain Dashboard](images/retail_dashboard.png)

---

## Project 3: Healthcare Supply Chain Analytics Dashboard

This dashboard analyzes healthcare supply usage, supplier delivery performance, and inventory patterns across hospital locations in the United States.

### Key Analytics
- Hospital supply demand across the United States
- Supplier delivery performance
- Top medical supplies by utilization
- Healthcare supply spend by category
- Average inventory levels by hospital

### Business Value
This dashboard demonstrates how analytics can support healthcare supply planning, supplier management, and inventory visibility.

![Healthcare Supply Chain Dashboard](images/healthcare_dashboard.png)

---

## Data Generation

All datasets in this repository were generated in Python using Pandas to simulate realistic operational conditions without exposing proprietary or sensitive business data.

The synthetic data was structured to support:
- executive KPI reporting
- geographic analysis
- category and supplier comparisons
- operational performance measurement

---

## Repository Structure

```text
supply-chain-analytics-dashboard-portfolio/
│
├── data/
│   ├── military_logistics_dataset.csv
│   ├── retail_distribution_dataset.csv
│   └── healthcare_supply_chain_dataset.csv
│
├── notebooks/
│   ├── military_dataset_generation.ipynb
│   ├── retail_dataset_generation.ipynb
│   └── healthcare_dataset_generation.ipynb
│
├── dashboards/
│   └── supply_chain_analytics_dashboards.twbx
│
├── images/
│   ├── military_dashboard.png
│   ├── retail_dashboard.png
│   └── healthcare_dashboard.png
│
└── README.md
