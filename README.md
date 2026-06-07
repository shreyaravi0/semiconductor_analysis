# ChipShield

### AI-Powered Semiconductor Supply Chain Risk Intelligence Platform

Sentinel is a data-driven analytics platform designed to monitor, analyze, and predict semiconductor supply chain disruptions using trade intelligence, risk analytics, COVID-19 recovery assessment, and Graph Neural Networks (GNNs).

The platform combines global semiconductor trade data, supply chain risk indicators, and machine learning models to provide actionable insights into the resilience and vulnerability of semiconductor ecosystems across countries.

---

## Overview

The semiconductor industry forms the backbone of modern technology, powering everything from smartphones and automobiles to artificial intelligence and cloud computing. Recent disruptions caused by the COVID-19 pandemic, geopolitical tensions, and supply chain bottlenecks have highlighted the need for proactive risk monitoring.

Sentinel addresses this challenge by integrating:

* Global semiconductor trade analytics
* Risk and disruption assessment
* COVID-19 impact and recovery analysis
* Graph Neural Network (GraphSAGE) risk classification
* Interactive executive dashboards

---

## Key Features

### Global Trade Intelligence

* Analyze semiconductor trade flows from 2019–2022
* Monitor imports, exports, and trade growth
* Identify dominant trading economies and trade concentration patterns

### Risk Analytics

* Compute disruption, dependency, volatility, and conflict indicators
* Classify countries into risk categories
* Visualize global risk distribution

### COVID-19 Recovery Analysis

* Compare pre-COVID, COVID shock, recovery, and post-COVID phases
* Identify the most impacted and fastest recovering countries
* Measure resilience across semiconductor supply chains

### AI-Powered Risk Prediction

* Graph Neural Network based classification
* Comparative evaluation of:

  * GCN
  * GAT
  * GraphSAGE
* Automated country-level risk assessment

### Interactive Dashboarding

* Executive-level analytics interface
* Country-specific deep-dive exploration
* Dynamic visualizations and benchmarking tools

---

## Dataset Summary

| Dataset | Description                                 |
| ------- | ------------------------------------------- |
| T1      | Global Semiconductor Trade Dataset          |
| T2      | Risk & Disruption Metrics                   |
| T3      | COVID Impact & Recovery Analysis            |
| T4      | Country-Level Analytical Dataset            |
| T5      | GNN Prediction Outputs                      |
| T6      | Final GraphSAGE Risk Classification Results |

---

## Technology Stack

### Data Analytics

* Python
* Pandas
* NumPy

### Machine Learning

* PyTorch
* PyTorch Geometric
* Graph Neural Networks

### Visualization

* Tableau
* Matplotlib
* Seaborn

### Frontend

* React
* Next.js
* Tailwind CSS
* Recharts / ECharts

---

## Model Performance

| Model     | Accuracy | ROC-AUC   |
| --------- | -------- | --------- |
| GCN       | 88%      | 0.677     |
| GAT       | 53%      | 0.449     |
| GraphSAGE | **94%**  | **0.985** |

GraphSAGE achieved the highest performance and was selected as the final model due to its superior classification accuracy and ability to generalize across supply chain networks.

---

## Dashboard Modules

### Dashboard 1 — Global Trade Overview

Provides a macro-level view of semiconductor trade, growth trends, and trade concentration across countries.

### Dashboard 2 — Risk & Geographical Analysis

Visualizes global disruption exposure, risk distribution, and country-level risk rankings.

### Dashboard 3 — COVID Impact & Recovery

Analyzes pandemic disruptions, recovery trajectories, and resilience patterns.

### Dashboard 4 — Country Deep Dive

Enables interactive country-level exploration of trade, risk, dependency, volatility, and GNN predictions.

---

## Research Contributions

* Developed a semiconductor supply chain risk assessment framework.
* Integrated trade analytics with Graph Neural Networks.
* Quantified COVID-19 disruption and recovery dynamics.
* Built an interactive decision-support platform for policymakers and industry stakeholders.
* Demonstrated the effectiveness of GraphSAGE for supply chain risk classification.

---

## Key Findings

* Global semiconductor trade expanded significantly between 2019 and 2022.
* Only a small set of countries accounted for the majority of trade activity.
* Seven countries were identified as Medium Risk due to elevated disruption and dependency indicators.
* COVID-19 created significant supply chain shocks, followed by strong recovery in several emerging economies.
* GraphSAGE achieved 94% classification accuracy and near-perfect risk discrimination capability.

---

## Future Enhancements

* Real-time trade data integration
* Live geopolitical event monitoring using GDELT
* Explainable AI (XAI) for risk predictions
* Scenario simulation and forecasting
* Cloud deployment and enterprise integration

---

## Authors

**Shreya Ravi**
**Sharanya Rao**
**Aarush Jaiswal**

Department of Computer Science & Engineering
RV College of Engineering

---

## License

This project was developed for academic and research purposes.
