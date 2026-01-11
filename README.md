# International Student Mental Health Analysis

![Mental Health Overview](mentalhealth.jpg)

This project explores mental health patterns among international students at a Japanese university, focusing on depression, social connectedness, and acculturative stress. The goal is to identify trends that can help universities provide better support for student well-being.

## Table of Contents
- [Overview](#overview)
- [Data Description](#data-description)
- [Analysis](#analysis)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [Technologies Used](#technologies-used)

## Overview
International students often face unique challenges that may increase the risk of mental health difficulties. This project investigates:

- **Social connectedness** – measured with the SCS test
- **Acculturative stress** – measured with the ASISS test
- **Length of stay** – time spent in Japan

The analysis aims to identify patterns in mental health outcomes based on how long students have been in Japan.

## Data Description
The dataset contains the following fields:

| Field Name     | Description                                         |
|----------------|-----------------------------------------------------|
| `inter_dom`    | Type of student: international or domestic         |
| `japanese_cate`| Japanese language proficiency                       |
| `english_cate` | English language proficiency                        |
| `academic`     | Current academic level: undergraduate or graduate  |
| `age`          | Age of student                                      |
| `stay`         | Current length of stay in years                     |
| `todep`        | Total depression score (PHQ-9)                     |
| `tosc`         | Total social connectedness score (SCS)            |
| `toas`         | Total acculturative stress score (ASISS)          |

## Analysis
The analysis explores relationships between student type, depression, social connectedness, and acculturative stress. 

- **Visualizations**: Charts highlight trends and patterns.
- **Focus areas**: Social connectedness, acculturative stress, and length of stay.

### Example Charts
 **Mental Health Overview by Length of Stay** 
 
   ![Mental Health Chart](MentalHealthMetrics.png)
   
   This horizontal bar chart illustrates average depression (PHQ), social connectedness (SCS), and acculturative stress (ASISS) scores by length of stay, showing patterns in mental health outcomes based on time spent in Japan.
   
## Key Findings
- International students generally report **higher depression scores** compared to domestic students.
- **Lower social connectedness** and **higher acculturative stress** are correlated with higher depression scores.
- **Length of stay** seems to moderate depression: students staying longer in Japan tend to adapt better and show slightly lower depression scores.

## Conclusion
Understanding these patterns can help universities:

- Identify students at risk
- Design targeted support programs
- Improve overall student well-being

## How to Run
1. Open `notebook.ipynb` in **Jupyter Notebook**, **VS Code**, or **Google Colab**.
2. Connect to a **PostgreSQL** database containing the `students` table.
3. Run queries to explore `tosc`, `toas`, `stay`, and `todep`.
4. Modify or extend queries to test new hypotheses or create additional visualizations.

## Technologies Used
- **PostgreSQL** – data querying and analysis
- **Python** – data manipulation and visualization
- **Pandas** & **Matplotlib / Seaborn** – charts and graphs
- **Jupyter Notebook** – project workflow and documentation

---

**Portfolio Note:**  
This project demonstrates skills in data analysis, visualization, and proficiency in PostgreSQL and Python, making it ideal for showcasing to recruiters or potential employers.
