# 🧠 Mental Health in Students Post-COVID: A Silent Crisis 
  📊 An Exploratory Data Analysis of 16,000+ Students
<br>
<br>

## 📌 Project Overview

The COVID-19 pandemic disrupted education systems worldwide, but one of the most silent crises has been the toll on students’ mental health.
This project leverages real survey data (16k+ students) to explore depression, suicidal thoughts, and lifestyle/academic stressors affecting students post-COVID.
<br>

## 🎯 Business & Research Objective

- Identify at-risk student groups based on demographics, academic pressure, and lifestyle factors.
- Quantify the impact of financial stress, sleep, diet, and study satisfaction on depression & suicidal thoughts.
- Translate raw survey data into actionable insights that educators, policymakers, and mental health professionals can use.
<br>


## 🗂️ Project Structure

```
datasets/
    ├── post_covid_mental_health_cleaned.xlsx   # Cleaned dataset
notebooks/
    └── Mental_Health_in_Students_Post_COVID_EDA.ipynb
reports/
    └── EDA_Report.pdf   # Full PDF Storytelling Report

```
<br>



## 🧼 Data Preprocessing
- Encoding: Binary mappings (Yes/No → 1/0), ordinal scaling (Healthy=2 → Unhealthy=0).
- Cleaning: Merged duplicates (e.g., Class 12 inconsistencies), dropped irrelevant/missing entries.
- Feature Engineering: Academic pressure (1–5 scale), financial stress levels, lifestyle scores.
<br>


## 🔍 Exploratory Data Analysis

Key EDA activities included:

- **Demographics:** Gender & age-based risk patterns.
- **Academic Pressure:** High stress vs depression & suicidal thoughts.
- **Degree Programs:** “Prestige” degrees (MBBS, B.Tech) showing 65–70% depression rates.
- **Lifestyle Factors:** Sleep & diet vs mental health.
- **External Factors:** Financial stress & family history of illness.
<br>


## 📌 Insights & Observations

- Students aged **21** had the highest number of depression cases.
- Depression was significantly higher among students with high academic pressure and low study satisfaction.
- Some degrees (e.g., `B.Tech`, `MBBS`) showed over **50%+** depression rates.
- Students getting < 6 hours of sleep and unhealthy diets were more likely to report suicidal thoughts.

Example Visuals (from EDA)
<p align="center"> <img src="https://github.com/user-attachments/assets/1d38fa61-8259-4bcf-af74-9c0b52556a0a" width="500"/> <br> <em>Financial Stress vs Depression</em> </p> <p align="center"> <img src="https://github.com/user-attachments/assets/fd2034af-a379-481b-80ee-72ca1048ce42" width="500"/> <br> <em>Fee Hike Highlights</em> </p>
<br>


## 💡 Insights & Observations

- **Age Risk:** Students aged ~20–21 most affected (transition to adulthood + academic pressure).
- **Prestige Pressure:** Mechanical Engg. (70%), MBBS (67%), B.Tech (65%) show extreme depression levels.
- **Financial Stress Multiplier:**
    - Low academic + low financial stress → 8.8% depression
    - High academic + high financial stress → 96% depression
- **Sleep & Diet ≠ Protection:** Even healthy lifestyles don’t shield students when stress is systemic.
- **Study Satisfaction Buffer:** With high academic pressure, satisfaction reduced depression from 93% → 83%.
<br>


## 🛠️ Tech Stack

- Python (Pandas, Seaborn, Matplotlib, NumPy)
- Jupyter Notebook (analysis + visual storytelling)
- Excel (initial data cleaning, exploration) 
<br>


## 📌 Deliverables

- ✅ Cleaned dataset → post_covid_mental_health_cleaned.xlsx
- ✅ Full Jupyter Notebook EDA → Mental_Health_in_Students_Post_COVID_EDA.ipynb
- ✅ PDF Report (storytelling deck) → reports/EDA_Report.pdf
<br>


## 📢 Impact & Takeaways

- Depression isn’t just personal — it’s systemic (academic + financial + societal).

- Grades & hours studied matter less than stress, satisfaction, and financial security.

- Policy & education models must shift focus from “perfect students” → mentally healthy humans.
<br>


## 🔗 Connect

- 🔗 [LinkedIn - Danish Shaikh](https://www.linkedin.com/in/danish-shaikh-b6442a212/)
- 📊 [Kaggle Profile](https://www.kaggle.com/danishshaikh18)
- 💻 [GitHub Profile](https://github.com/DanishShaikh18)
<br>


## 🏆 Final Note

This isn’t just an analysis. It’s a data-driven story that uncovers how systemic pressures are breaking students silently.

“We don’t need more perfect students.
We need happier, healthier, heard humans.”
