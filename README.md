# Titanic — Exploratory Data Analysis

## Overview

This project presents an exploratory data analysis (EDA) of the Titanic passenger dataset. The objective is to identify patterns and relationships between passenger characteristics and survival.

The analysis focuses on how survival varied according to passenger sex, passenger class, and age, including interactions between these variables.

## Objectives

* Explore the structure and characteristics of the dataset.
* Identify missing values and assess data completeness.
* Analyze the overall survival rate.
* Investigate survival differences by sex.
* Investigate survival differences by passenger class.
* Analyze the interaction between sex and passenger class.
* Explore the relationship between age and survival.
* Examine survival across combinations of age, sex, and passenger class.

## Dataset

The dataset contains information about 891 Titanic passengers and includes variables such as:

* Passenger ID
* Survival status
* Passenger class
* Name
* Sex
* Age
* Number of siblings or spouses aboard
* Number of parents or children aboard
* Ticket
* Fare
* Cabin
* Port of embarkation

The dataset was loaded from a publicly available GitHub repository.

## Tools and Technologies

* Python
* Pandas
* Matplotlib
* Google Colab
* Jupyter Notebook

## Key Findings

* Approximately 38.4% of the passengers in the dataset survived.
* Female passengers had substantially higher survival rates than male passengers.
* First-class passengers generally had higher survival rates than passengers in lower classes.
* The combination of sex and passenger class revealed substantial differences in survival rates.
* Age showed a less consistent association with survival than sex and passenger class.
* Some age-sex-class combinations contained very few observations and therefore should be interpreted cautiously.

## Methodology

The analysis followed an exploratory data analysis workflow:

1. Dataset loading and inspection.
2. Analysis of dataset dimensions and data types.
3. Identification of missing values.
4. Descriptive statistical analysis.
5. Survival rate analysis.
6. Analysis by sex and passenger class.
7. Analysis of age groups.
8. Analysis of interactions between age, sex, and passenger class.
9. Interpretation of findings and limitations.

## Project Structure

```text
python-data-analysis/
│
├── README.md
└── titanic_eda.ipynb
```

## Limitations

This project is an exploratory analysis and does not establish causal relationships between passenger characteristics and survival.

Additionally, the `Age` variable contains missing values, and some combinations of age, sex, and passenger class have small sample sizes. Therefore, those specific survival rates should be interpreted with caution.

## Author

Francisco Javier Urías Ortiz
