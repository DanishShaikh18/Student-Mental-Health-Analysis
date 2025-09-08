# 🧠 Mental Health in Students Post-COVID: A Silent Crisis
📊 An Exploratory Data Analysis of 16,000+ Students
## 📌 Project Overview

The COVID-19 pandemic brought major disruptions across the globe, but among the most silent and deeply felt effects has been the toll on students’ mental health. This project dives into analyzing various mental health indicators and behavioral patterns in students post-COVID.

---

## 🎯 Objective

- Understand how mental health was impacted across different age groups, genders, and academic pressures.
- Investigate the relationship between depression, suicidal thoughts, and academic/daily lifestyle factors.
- Draw actionable insights from real survey data to highlight at-risk groups.

---

## 🗂️ Folder Structure

```
datasets\
    # Used Datasets
post_covid_mental_health_cleaned.xlsx
Mental_Health_in_Students_Post_COVID_EDA.ipynb
```

---

## 📊 Dataset Details

The dataset contains the following columns:

- **Gender**
- **Age**
- **City**
- **Academic Pressure**
- **CGPA**
- **Study Satisfaction**
- **Sleep Duration**
- **Dietary Habits**
- **Degree**
- **Suicidal Thoughts**
- **Study Hours**
- **Financial Stress**
- **Family History of Mental Illness**
- **Depression**

Source: Survey datasets related to mental health post-COVID

---

## 🧼 Data Preprocessing

- Converted categorical data to numerical for modeling (e.g., Healthy = 2, Moderate = 1, Unhealthy = 0)
- Cleaned duplicated or inconsistent data entries (`Class 12` and `Class 12` merged)
- Mapped values for binary responses like `Yes/No` → `1/0`
- Removed or imputed missing values

---

## 📈 Exploratory Data Analysis (EDA)

Key EDA activities included:

- **Demographic Distributions** — Age, Gender-wise Depression and Suicidal Thoughts
- **Top Degrees vs Depression Rates** — Visualized top 20 degrees with highest percentage of depressed students
- **Daily Habits** — Sleep duration, dietary habits, and their correlation with mental health
- **Academic Pressure & Satisfaction** — Observed mental health variations across satisfaction and pressure levels
- **Financial Stress & Family History** — Understanding external and inherited factors

Graphs used:

- Countplots
- Barplots with annotations
- Grouped Percentage Charts

All plots were styled for clarity, professionalism, and storytelling.

---

## 📌 Insights & Observations

- Students aged **21** had the highest number of depression cases.
- Depression was significantly higher among students with high academic pressure and low study satisfaction.
- Some degrees (e.g., `B.Tech`, `MBBS`) showed over **50%+** depression rates.
- Students getting < 6 hours of sleep and unhealthy diets were more likely to report suicidal thoughts.

---

## 📘 Tools Used

- Python (Pandas, Seaborn, Matplotlib, NumPy)
- Jupyter Notebook
- Excel for cleaned output

---

## 💾 Output Files

- `Mental_Health_in_Students_Post_COVID_EDA.ipynb` — All analysis & visualizations
- `post_covid_mental_health_cleaned.xlsx` — Cleaned dataset for reuse

---

## 🔗 Important Links

- 🔗 [LinkedIn - Danish Shaikh](https://www.linkedin.com/in/danish-shaikh-b6442a212/)
- 📊 [Kaggle Profile](https://www.kaggle.com/danishshaikh18)
- 💻 [GitHub Profile](https://github.com/DanishShaikh18)

---

## 🙌 Final Note

This project aims to bring attention to a problem that's often overlooked but critical — the mental well-being of our future generation. As we visualize the silent crisis post-pandemic, let’s ensure our solutions aren’t silent.

> "Mental health is not a destination, but a process. It's about how you drive, not where you're going."
