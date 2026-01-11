# International Student Mental Health Analysis

![Mental Health Chart](mentalhealth.jpg)

**Exploring the impact of social connectedness, acculturative stress, and length of stay on depression among international students at a Japanese university.**

---

## Table of Contents
- [Overview](#overview)  
- [Data Description](#data-description)  
- [Analysis](#analysis)  
- [Key Findings](#key-findings)  
- [Conclusion](#conclusion)  
- [How to Run](#how-to-run)  
- [Technologies Used](#technologies-used)

---

## Overview
International students may experience higher risks of mental health difficulties than domestic students.  
This project investigates:

- **Social connectedness**: measured with the SCS test  
- **Acculturative stress**: measured with the ASISS test  
- **Length of stay**: time spent in Japan  

The goal is to identify patterns that may help universities support international students’ mental well-being.

---

## Data Description
The `students` dataset includes:

| Field Name       | Description                                      |
|-----------------|--------------------------------------------------|
| `inter_dom`      | Type of student: international or domestic      |
| `japanese_cate`  | Japanese language proficiency                    |
| `english_cate`   | English language proficiency                     |
| `academic`       | Current academic level: undergraduate or graduate |
| `age`            | Current age of student                           |
| `stay`           | Current length of stay in years                  |
| `todep`          | Total score of depression (PHQ-9 test)          |
| `tosc`           | Total score of social connectedness (SCS test)  |
| `toas`           | Total score of acculturative stress (ASISS test)|

---

## Analysis
We explored relationships between student type, depression, and contributing factors.

- **Visualizations**: Highlight trends using charts  
- **Focus areas**: Social connectedness, acculturative stress, length of stay

![Mental Health Chart](mentalhealth.jpg)

This chart illustrates how depression scores vary with social connectedness and acculturative stress, highlighting risk factors among international students.

---

## Key Findings
- International students generally show higher depression scores (`todep`) compared to domestic students.  
- Lower social connectedness (`tosc`) and higher acculturative stress (`toas`) correlate with higher depression scores.  
- Length of stay (`stay`) appears to moderate depression: students staying longer tend to adapt better and show slightly lower depression scores.

---

## Conclusion
Understanding mental health patterns among international students helps universities:

- Identify students at risk  
- Design targeted support programs  
- Improve overall student well-being

---

## How to Run
1. Open the `notebook.ipynb` file in **Jupyter Notebook**, **VS Code**, or **Google Colab**.  
2. Connect to a PostgreSQL database containing the `students` table.  
3. Run queries to explore `tosc`, `toas`, `stay`, and `todep`.  
4. Modify or extend queries to test new hypotheses or visualizations.

---

## Technologies Used
- **PostgreSQL** – data querying and analysis  
- **Python** – data manipulation and visualization  
- **Pandas & Matplotlib / Seaborn** – for charts and graphs  
- **Jupyter Notebook** – project workflow and documentation  

---

**Portfolio Notes:**  
This README shows clear **data analysis skills**, ability to **visualize trends**, and proficiency in **PostgreSQL and Python**, making it ideal for showcasing to recruiters.

