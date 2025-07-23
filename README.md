# Auto Piste Analytics Dashboard – Real-Time Lead Intelligence

An **interactive Streamlit-based dashboard** that provides **real-time insights into lead quality**, **conversion potential**, and **campaign performance** from the **Auto Piste platform**. The dashboard features **dynamic KPI visualizations** and advanced filtering to support **strategic decision-making**.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.x-blue)
![Python](https://img.shields.io/badge/Python-3.x-brightgreen)
![Plotly](https://img.shields.io/badge/Plotly-4.x-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-purple)

---

## Features

- **Real-time Data**: Visualize live metrics from your lead intelligence platform.
- **Lead Quality**: Track lead quality scores to prioritize high-value prospects.
- **Conversion Potential**: Analyze the likelihood of lead conversion to refine strategies.
- **Campaign Performance**: Visualize and compare KPIs for different marketing campaigns.
- **Dynamic Filtering**: Filter data based on date ranges, campaign types, lead sources, and more.
- **KPI Visualizations**: Interactive graphs and charts using **Plotly** for actionable insights.
- **User-Friendly Interface**: Powered by **Streamlit** for an intuitive and engaging dashboard experience.

---

## Tech Stack

- **Backend**: Python
- **Data Analysis**: Pandas
- **Visualization**: Plotly
- **Dashboard**: Streamlit

---

## Screenshots

### Dashboard Overview
![Dashboard Overview](screenshots/dashboard_overview.png)

### Lead Quality Analysis
![Lead Quality 1](screenshots/lead_quality.png)

![Lead Quality 2](screenshots/campaign_metrics.png)

---

## Confidentiality Notice
Please note that the source code for this project is confidential and is not publicly available. This project is part of a proprietary solution developed for internal use or specific clients. As such, we are unable to share the full codebase, data, or detailed implementation publicly.

If you are interested in learning more about the project, please contact me directly.

---

## System Architecture
The system employs a distributed architecture to enhance security and scalability. The data infrastructure includes:

SSH Connection to Cloud Database: The application securely connects to a cloud-based SQL database using SSH, ensuring encrypted communication between the system and the database server.

Data Collection from External Cloud Database: APIs are used to collect real-time data from a separate cloud-based database hosted on OVH, enabling the dashboard to display live lead intelligence metrics and campaign performance data.

Distributed System for Security: The system is designed with multiple layers and distributed components to prevent single points of failure, increase data redundancy, and enhance security levels.