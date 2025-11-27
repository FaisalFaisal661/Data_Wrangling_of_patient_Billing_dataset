# 🏥 Hospital Patient Data Analysis

## 🎯 Project Overview

This project focuses on the **cleaning, integration, and initial analysis** of hospital patient and billing datasets. The primary goal was to process raw, messy patient records—which included duplicate entries, multiple follow-up rows, and missing billing information—to produce a single, unified, and accurate dataset suitable for deeper business intelligence and performance analytics (e.g., department revenue, doctor performance).

---

## ✨ Key Features & Deliverables

The successful completion of this assignment delivered the following:

* **Data Integrity:** Handled missing bill amounts by imputation with the mean.
* **De-duplication:** Identified and removed duplicate patient records based on a unique Patient ID.
* **Data Transformation:** Consolidated administrative columns to focus only on essential billing metrics.
* **Data Integration:** Successfully merged patient and billing datasets and concatenated new patient and new billing category dataframes.
* **Summary Analytics:** Calculated the **total bill amount per department** using aggregation.

---

## 🛠️ Technology Stack

| Category | Tool / Library | Purpose |
| :--- | :--- | :--- |
| **Language** | Python | Primary programming language. |
| **Core Library** | Pandas | Used extensively for data loading, cleaning, merging, and aggregation. |
| **Environment** | Jupyter Notebook / IDE (Implied) | Used for development and execution. |

---

## 🚀 Getting Started

This section outlines the steps required to set up and run the analysis.

### Prerequisites

You need Python installed, along with the Pandas library.

```bash
pip install pandas
# (If using Jupyter)
pip install jupyter

