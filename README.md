## Threat Analysis Dashboard

### Overview

A Power BI-based cybersecurity intelligence dashboard designed to visualize threat incidents, risk exposure, and vulnerability patterns across organizational departments. This project converts raw incident data into actionable insights, enabling faster response and better decision-making.

### Key Insights

196K Total Alerts and 52K Devices Affected across multiple departments.

Average Incident per Device: 3.8

Top Threat-Exposed Department: Sales

Most Exploited Vectors: Application (78K), Device (52K), Network (32K), Identity (25K), User (9K)

High-Risk Departments: Legal, Engineering, Support

Top User Vulnerability: Marketing (23.98%), Operations (16.66%), Legal (10.11%)

### Key Features

Comprehensive incident overview with KPIs and visual indicators

Department-wise risk and threat segmentation

Heatmap-based Risk Scoring Model for quick prioritization

User Vulnerability Distribution to identify departments needing awareness programs

Visual storytelling through Power BI for executive decision support

### Data Model

| Table           | Description                                                           |
| --------------- | --------------------------------------------------------------------- |
| **Events**      | Incident-level data including timestamp, vector, and department       |
| **Departments** | Department metadata and hierarchy                                     |
| **Vectors**     | Categorization of attack types (App, Device, Network, Identity, User) |
| **Date**        | Time intelligence for trend analysis                                  |

### Visual Overview
#### Incident Overview
![Incident Overview](https://i.ibb.co/rKQ0rn3H/overview.jpg)

#### Events & Vectors
![Events and Vectors](https://i.ibb.co/nMbX4z1b/events-vectors.jpg)

#### Risk Scoring Model
![Risk Scoring Model](https://i.ibb.co/8DsGDhLD/rs.jpg)

### Insights Summary

Legal and Engineering departments show the highest cumulative risk levels.

Application and Device vectors account for over 65% of total incidents.

Marketing and Operations demonstrate significant user vulnerability trends.

The Risk Scoring Model provides a structured framework for prioritizing cyber risk mitigation actions.

### Tools and Technologies

| Tool            | Purpose                                   |
| --------------- | ----------------------------------------- |
| **Power BI**    | Dashboard creation and data visualization |
| **Power Query** | Data transformation and cleaning          |
| **Excel / CSV** | Source data inputs                        |
| **DAX**         | Business logic and measure calculations   |
