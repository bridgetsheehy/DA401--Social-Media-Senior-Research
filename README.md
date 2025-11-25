# DA401--Social-Media-Senior-Research
Beyond Facebook: Using the General Social Survey to Study Snapchat and Well-Being
Author: Bridget Sheehy
Course: DA 401 — Senior Seminar
Semester: Fall 2025

Overview: This project looks at whether using Snapchat is linked to well-being among adults in the United States.

Past research focuses mostly on Facebook and Instagram. Very little work looks at Snapchat, even though it is extremely popular. This project uses data from the 2016 General Social Survey (GSS) to explore how Snapchat use relates to: Spirituality, Optimism, Stress, Job satisfaction, Feeling personally successful

All analysis was done in R and is fully reproducible using the .Rmd file provided.

RQ: How does Snapchat use relate to mental health and well-being indicators?

Data: This project uses the GSS 2016, a large, nationally representative survey.
Main variables: 
  Predictor: snapchat — whether the respondent uses Snapchat
  Well-being outcomes: sprtprsn — spirituality, lotr6 — optimism, stress — stress level, jobsat — job satisfaction, hope4 — feeling successful 
  Control variable: dwelown — whether the respondent owns their home

Notes about the data- Some variables such as internet use, income, and education could not be used because they were too strongly related to Snapchat use or had too many missing values. Keeping them in the model caused errors or made the sample too small. For this reason, homeownership was the only control variable kept in all models.

Reproducibility: 
1. Open Sheehy-First-Draft.Rmd in RStudio
2. Install/load the required packages
3. Run the file from top to bottom
This will create all tables, figures, and results used in the paper.

Key Findings:
Snapchat use was not strongly related to optimism, stress, job satisfaction, or personal success.
Snapchat use had a small negative association with spirituality.
None of these relationships can be taken as causal.
The results suggest Snapchat does not show the same negative patterns found for Facebook or Instagram in past studies.
