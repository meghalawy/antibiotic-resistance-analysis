# Antibiotic Resistance Trend Analysis of *Klebsiella pneumoniae*

## Overview

This project explores antimicrobial resistance (AMR) patterns in *Klebsiella pneumoniae* using a large-scale microbiology dataset derived from electronic health records (EHRs). The objective was to investigate resistance trends across antibiotics, culture types, patient demographics, and clinical settings while demonstrating practical data wrangling, exploratory data analysis (EDA), and statistical visualization using R.

The project was completed as a data analytics capstone, combining domain knowledge in microbiology with modern data analysis techniques to generate clinically meaningful insights.

---

## Background

Antimicrobial resistance is one of the most significant global public health challenges. *Klebsiella pneumoniae* is an important opportunistic pathogen associated with hospital-acquired infections and increasing multidrug resistance.

Understanding resistance patterns helps support:

* Antimicrobial stewardship
* Infection prevention strategies
* Clinical decision-making
* Public health surveillance

---

## Dataset

**Source:** Antibiotic Resistance Microbiology Dataset (ARMD)

The dataset is a de-identified resource derived from electronic health records containing microbiology laboratory results, patient demographics, clinical encounters, antibiotic susceptibility testing, and socioeconomic indicators.

### Dataset Highlights

* 283,715 unique adult patients
* Multiple culture types (blood, urine, respiratory, etc.)
* Susceptibility testing for 55 antibiotics
* Clinical and demographic information
* Publicly available through the Dryad repository

---

## Project Objectives

The analysis aimed to:

* Explore antimicrobial resistance patterns in *Klebsiella pneumoniae*.
* Identify the most frequently isolated microorganisms.
* Investigate temporal trends in resistance rates.
* Compare resistance across different culture types.
* Examine resistance by antibiotic class.
* Explore relationships between patient demographics and infection patterns.

---

## Data Preparation

The dataset was cleaned and prepared prior to analysis.

Data preprocessing included:

* Handling missing values
* Data cleaning and formatting
* Variable preparation
* Exploratory quality assessment

---

## Exploratory Data Analysis

The project includes several visual analyses, including:

* Top ten isolated microorganisms
* Temporal trends in *Klebsiella pneumoniae* resistance
* Resistance rates across culture types
* Antibiotic resistance by drug class
* Inpatient versus outpatient culture distribution
* Relationship between patient age and infection prevalence

---

## Technologies Used

* R
* tidyverse
* dplyr
* ggplot2
* RStudio

---

## Repository Structure

```text
antibiotic-resistance-analysis/

├── README.md
├── analysis/
│   └── antibiotic_resistance_analysis.R
├── presentation/
│   └── Graduation_Project.pdf
├── figures/
└── data/
```

---

## Key Insights

The analysis demonstrates how large-scale microbiology datasets can be used to identify clinically relevant antimicrobial resistance patterns.

Key findings include:

* Identification of the most prevalent microbial isolates.
* Visualization of temporal resistance trends for *Klebsiella pneumoniae*.
* Comparison of resistance patterns across specimen types.
* Differences in resistance among antibiotic classes.
* Exploration of demographic and healthcare setting factors associated with infection.

---

## Future Improvements

Potential extensions include:

* Predictive modeling of antimicrobial resistance.
* Geographic analysis of resistance patterns.
* Interactive dashboards for antimicrobial surveillance.
* Machine learning models for resistance prediction.
* Integration with additional clinical variables.

---

## References

* Antibiotic Resistance Microbiology Dataset (ARMD), Dryad Digital Repository
* Supporting literature referenced in the accompanying presentation

---

## Author

**Reem Elmeghalawy**

Veterinary Medicine graduate transitioning into healthcare data analytics and machine learning, with research interests in biomedical AI, infectious diseases, antimicrobial resistance, and predictive analytics.


