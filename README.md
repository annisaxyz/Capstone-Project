# Capstone-Project

## Project Title
Academic Conditions Analysis by Total Score, Grade, Study Hours, and Stress Level

## Project Overview
This project analyzes students’ academic conditions across departments (Business, Engineering, Mathematics, CS) using the Students Grading Dataset. The research objective is to provide a concise overview of score distributions (Total_Score & Grade), study-hour patterns, and stress levels by department so prospective students and stakeholders can better consider abilities, interests, and mental readiness when choosing a major.

## Raw dataset link
- Kaggle dataset used: mahmoudelhemaly/students-grading-dataset
- Kaggle page: https://www.kaggle.com/mahmoudelhemaly/students-grading-dataset

## Insight & Findings
- Total_Score ranges roughly from 51 to 95. Business has the highest median (~82); Engineering has the lowest (~51). Mathematics and CS fall in the middle range.
- Score distribution is slightly right-skewed, with a few higher scores shifting the mean to the right; no obvious extreme outliers observed.
- Grade distribution: Business dominated by higher grades ('B' and 'C'), Engineering shows more lower grades ('D' and 'F'), while Mathematics and CS remain balanced.
- Study hours vs. scores: No uniform strong linear correlation across departments — individual variance is visible.
- Stress levels: Departments with lower average scores tend to show higher proportions of high stress.
- Brief recommendation: Prospective students should weigh both academic ability and mental readiness; choose a major informed by the observed characteristics rather than social trends.

## AI support explanation
In this project, the ibm-granite/granite-3.3-8b-instruct model was used via Replicate and integrated with a pandas dataframe agent from langchain_experimental. Granite AI played a key role in:
- Data Analysis: Producing analytical narratives (statistical and visualization explanations) based on the processed dataset.
- Visualization: Generating instructions to create boxplots, histograms, bar charts, scatter plots, and stacked bar charts according to research needs.
- Summarization & Interpretation: Crafting concise findings directly aligned with the research objective, namely to provide an overview of academic conditions across departments for prospective students’ decision-making.
