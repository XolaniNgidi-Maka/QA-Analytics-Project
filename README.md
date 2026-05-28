# QA Testing Analytics & Prediction Platform

## 🎯 Project Overview

During my 8 months as a Software Manual Tester at eCOGRA, I tested nearly 100 games and captured detailed data on each testing cycle. This project transforms that raw data into actionable insights to answer one question:

**"What can I do to reduce the QA notes I receive from the Quality Assurance department?"**

This project demonstrates skills from three Microsoft certifications:
- **DP-900** – Azure Data Fundamentals (data storage concepts)
- **DP-700** – Data Engineering (ETL, Fabric Lakehouse, PySpark)
- **PL-300** – Data Analysis (Power BI, DAX, dashboard design)

---

## 📁 Dataset

**Source:** Synthetic data generated based on real testing patterns at eCOGRA  
**Time period:** April–May 2026  
**Rows:** ~200 events  
**Key columns:**

| Column | Description |
|--------|-------------|
| `event_date` | When the workflow state changed |
| `game_name` | Name of the game being tested |
| `event_state` | Testing, QA Note Received, Retesting, Ready for QA |
| `severity` | Low / Medium / High |
| `hours_spent` | Time spent on the task |
| `game_complexity` | 1–5 scale |

---

## 🏗️ Architecture
