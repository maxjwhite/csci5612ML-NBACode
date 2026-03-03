# 🏀 NBA Analytics Project

## Overview

This project explores statistical patterns in the National Basketball Association (NBA) to better understand what differentiates teams across seasons — and what characteristics are most commonly associated with championship-level performance.

Using publicly available NBA data, the analysis applies dimensionality reduction, clustering, and pattern discovery techniques to uncover meaningful structure within team performance metrics.

The goal of this project is not prediction, but interpretation — identifying trends, similarities, and statistical relationships that help explain team success.

---

## Data Source

All data is accessed through the [`nba_api`](https://github.com/swar/nba_api), a community-supported Python API that provides structured access to official NBA statistics.

The dataset includes:

* Team-level performance statistics
* Seasonal outcomes
* Efficiency and scoring metrics
* Historical comparisons across multiple seasons

---

## Methods Used

This project integrates several analytical approaches:

### 🔹 Principal Component Analysis (PCA)

Used to reduce high-dimensional performance metrics into a smaller number of interpretable components that capture the majority of variance in team statistics.

### 🔹 Clustering Techniques

Used to identify natural groupings of teams based on statistical similarity.

* **K-Means Clustering** – Partitions teams into clearly defined groups
* **Hierarchical Clustering** – Reveals nested similarity relationships
* **DBSCAN** – Detects dense clusters and potential outliers

### 🔹 Association Rule Mining (ARM)

Identifies combinations of performance characteristics that frequently occur together, particularly among high-performing or championship teams.

---

## Key Questions Explored

* How have scoring patterns changed over time?
* What statistical features distinguish winning teams from losing teams?
* Are championship teams statistically similar to one another?
* Do natural team archetypes emerge from clustering?
* Which performance metrics tend to co-occur among elite teams?

---
