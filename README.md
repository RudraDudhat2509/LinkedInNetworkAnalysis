# LinkedIn Network Intelligence Pipeline

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-5A9?style=for-the-badge"/>
</p>

A structural analytics engine that transforms LinkedIn connection data into measurable network intelligence.

Author: Rudra Dudhat
GitHub: [https://github.com/RudraDudhat2509](https://github.com/RudraDudhat2509)

---

## Overview

This project analyzes exported LinkedIn connection data to quantify network structure, diversity, and growth dynamics.

It converts networking activity into:

* Measurable growth velocity
* Company concentration metrics
* Role distribution analysis
* Seniority segmentation
* Structural gap detection

The goal is to treat professional networking as a measurable graph system rather than a passive activity.

---

## System Architecture

LinkedIn CSV Export
->
Data Cleaning & Normalization
->
Feature Engineering
->
Growth & Diversity Metrics
->
Visualization & Structural Insights

---

## Core Metrics

### 1. Network Size

Total number of connections.

### 2. Company Diversity Ratio

Company Diversity = Unique Companies / Total Connections

Indicates network concentration and referral surface area.

### 3. Role & Seniority Distribution

Quantifies actionable segments within the network.

### 4. Monthly Growth

Connections aggregated by month from timestamp parsing.

### 5. Cumulative Growth Function

G(t) = Σ monthly_connections

Used to detect acceleration phases.

### 6. Networking Velocity

Velocity(t) = G(t) − G(t−1)

Measures outreach intensity over time.

### 7. Structural Gaps

Identifies underrepresented industries and seniority bands.

---

## Example Dataset Results

Total Connections: 1,836
Unique Companies: 952
Unique Roles: 849

94.8 percent of connections built within a single year.
664 connections added in one month.

Company Diversity Ratio ≈ 0.52

Indicates low concentration and high company spread.

---

## Installation

Clone Repository

```
git clone https://github.com/RudraDudhat2509/linkedin-network-analyzer.git
cd linkedin-network-analyzer
```

Install Dependencies

```
pip install -r requirements.txt
```

---

## Usage

1. Export your LinkedIn connections CSV
2. Place the file in the project directory
3. Run the notebook
4. Review generated analytics and visualizations

---

## Design Principles

* Deterministic analysis
* Reproducible metrics
* Minimal dependencies
* Insight over aesthetics
* Quantification over intuition

---

## Roadmap

* Graph centrality analysis
* Community detection
* Referral probability modeling
* Industry transition mapping
* Time-series growth modeling

---

## License

MIT License

---
