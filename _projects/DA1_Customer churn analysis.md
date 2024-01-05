---
name: Customer churn analysis [Data Analysis]
tools: [Power BI, Power Query, DAX, Data Analysis, Data visualisation]
image: /assets/images/customerChurnAnalysis/customerChurnAnalysis_1.png
description: Utilised Power Query, DAX, and visualisation tools within Power BI to analyse a fictional telecom company's dataset, examining customer churn patterns and facilitating data-driven insights for retention strategies.
---

# Customer churn analysis

---

{% capture list_items %}
Final report
Overview
Tasks details
{% endcapture %}
{% include elements/list.html title="Table of Contents" type="toc" %}

# Final report

<iframe title="Customer churn analysis" width="900" height="547" src="https://app.powerbi.com/view?r=eyJrIjoiODQ4YmMzMDEtM2JmNi00NThiLWE4NDEtZjFlNDc0YWYyNjM2IiwidCI6ImNhYmFmZjVlLWExMTMtNDJhMS1iMjliLTIwMDk2N2M0NTZmYSIsImMiOjEwfQ%3D%3D&pageName=ReportSection83d234cc1bdbe978d3df" frameborder="0" allowFullScreen="true"></iframe>

# Overview

## Purpose

Investigate the underlying reasons for customer churn for a fictional telecom company through analysing its dataset.

## Steps

- Data check
- Explore data
- Analyse and visualise data
- Dashboarding
- Communicate insights

# Tasks details

## Data check

- Create 2 measures to check if the count of customer ids is equal to the count of unique customer ids and remove duplicate rows if exist.

## Explore data

- Calculate churn: `Number of Churned Customers`, `Churn Rate`
- Investigate churn reasons
- Investigate churn categories
- Investigate churn by state

## Investigate churn patterns

- Analyse demographics: age groups, age bins, gender
- Inspect multiple fields: contract category, extra services, usage of those services
- Investigate topics related to customers

## Collate information and create a report

- Organise the visualisations created in the previous steps into new pages:
  - Overview
  - Age Groups, Payment and contract
  - Extra charges
  - other Insights

## Publish

The final report and dashboard is published to Power BI Service and shared as at the top of this page. Below are the links to the report on Power BI Service, and its static PDF version 👇
{% include elements/button.html link="https://app.powerbi.com/view?r=eyJrIjoiODQ4YmMzMDEtM2JmNi00NThiLWE4NDEtZjFlNDc0YWYyNjM2IiwidCI6ImNhYmFmZjVlLWExMTMtNDJhMS1iMjliLTIwMDk2N2M0NTZmYSIsImMiOjEwfQ%3D%3D&pageName=ReportSection83d234cc1bdbe978d3df" text="Customer Churn Analysis Report - Power BI Server" block=true %}
{% include elements/button.html link="/assets/PDFs/customerChurnAnalysis/report.pdf" text="Customer Churn Analysis Report - PDF" block=true %}
