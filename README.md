# IoT-Based Intelligent Building Decision Support System

## Project Overview

The rapid adoption of Internet of Things (IoT) technologies has transformed conventional buildings into intelligent environments capable of continuously monitoring energy consumption, occupancy, environmental conditions, and operational activities through interconnected sensors and smart devices. Although modern Building Management Systems (BMS) collect large volumes of operational data, they primarily focus on monitoring rather than providing intelligent decision support for facility managers.

This project proposes an **IoT-Based Intelligent Building Decision Support System** that integrates multi-source IoT datasets to support intelligent building operations. The proposed framework combines statistical analysis, machine learning, explainable artificial intelligence (XAI), and natural language processing (NLP) to generate data-driven operational insights and recommendations for smart building management.

> **Note:** This repository currently contains the project setup, dataset information, documentation, and reproducible structure required for the Capstone Project Synopsis. Model development and implementation will be added in subsequent project phases.

---

# Project Objectives

The primary objective of this project is to develop an intelligent decision support framework that assists facility managers in analysing IoT-enabled building operations using real-world sensor data.

Specific objectives include:

- Integrate heterogeneous IoT datasets from multiple sources.
- Perform exploratory statistical analysis of building operational data.
- Develop machine learning models for operational state classification.
- Apply Explainable AI (SHAP) to interpret model predictions.
- Generate intelligent recommendations for facility managers.
- Produce natural language operational reports using NLP.
- Validate the proposed framework using an external smart building dataset.

---

# Datasets

The project utilises three publicly available datasets.

## Dataset 1 – I-BLEND Dataset

**Purpose**

Primary IoT smart building dataset used for model development.

Contains:

- Electrical energy consumption
- Occupancy information
- Weather observations
- Academic calendar

Source

Figshare – IIIT Delhi

---

## Dataset 2 – NASA POWER

**Purpose**

Environmental enrichment dataset.

Variables include:

- Solar Radiation
- Wind Speed
- Precipitation

Source

NASA POWER Data Access API

---

## Dataset 3 – Smart Building Dataset (Nature Scientific Data, 2025)

**Purpose**

Independent external validation dataset.

Contains:

- Electricity consumption
- Heating load
- Cooling load
- Weather measurements

Source

Dryad Repository (Nature Scientific Data)

---

# Repository Structure

```

IoT-Based-Intelligent-Building-DSS/

├── data/
│ ├── raw/
│ ├── processed/
│ ├── sample/
│ └── README.md
│
├── docs/
│ └── references.md
│
├── images/
│
├── notebooks/
│ └── 01_dataset_overview.ipynb
│
├── reports/
│
├── src/
│ └── main.py
│
├── README.md
├── PROJECT_STATUS.md
├── requirements.txt
├── LICENSE
└── .gitignore

```

---

# Installation

Clone the repository

```bash
git clone https://github.com/sriharimudakavi5/IoT-Based-Intelligent-Building-DSS.git