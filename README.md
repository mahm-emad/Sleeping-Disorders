# 💤 Sleep Health and Lifestyle Analysis

This project explores the Sleep Health and Lifestyle Dataset through detailed exploratory data analysis (EDA) and a Power BI dashboard to understand how sleep is influenced by various health and lifestyle factors.

---

## 📊 Dataset Overview

- **Records**: 400 individuals
- **Features**: 13 columns
- **Key Topics**:
  - Sleep duration and quality
  - Physical activity, stress, and BMI
  - Cardiovascular indicators
  - Sleep disorders (None, Insomnia, Sleep Apnea)

### 🧾 Dataset Features

| Column                        | Description |
|------------------------------|-------------|
| `Person ID`                  | Unique identifier for each individual |
| `Gender`                     | Gender (Male/Female) |
| `Age`                        | Age in years |
| `Occupation`                 | Profession or job category |
| `Sleep Duration (hours)`     | Average hours of sleep per day |
| `Quality of Sleep`           | Sleep quality rating (1–10) |
| `Physical Activity Level`    | Daily physical activity (minutes) |
| `Stress Level`               | Stress level (1–10) |
| `BMI Category`               | BMI status (Underweight, Normal, Overweight) |
| `Blood Pressure`             | Systolic/diastolic pressure |
| `Heart Rate`                 | Resting heart rate (bpm) |
| `Daily Steps`                | Steps taken per day |
| `Sleep Disorder`             | None, Insomnia, or Sleep Apnea |

---

## 🔍 EDA Highlights

### 🩺 Health Indicators
- **Blood Pressure** ranges from slightly elevated (130/85) to high (140/95).
- **Most people** fall into **normal or overweight** BMI categories.
- **Heart Rate and Steps** correlate with physical activity and overall sleep quality.

### 🧠 Mental Health
- **Stress Levels**:
  - Highest in **sales representatives**, **scientists**, and **lawyers**.
  - Lower in **engineers**, **accountants**, and **teachers**.
- **Stress is reduced** by higher sleep quality and longer sleep duration.

### 🧑‍⚕️ Occupation Insights
- Common professions: **Nurse, Doctor, Engineer**
- **Engineers** sleep the most and report the **highest sleep quality**.
- **Scientists** sleep the least.
- **Salespeople** have **lowest sleep quality** and highest stress.
- **Nurses** show **higher rates of sleep apnea**.
- **Teachers** and **salespeople** suffer more from **insomnia**.

### 🚶 Lifestyle & Physical Activity
- High activity variance: **Engineers, doctors, lawyers**
- Low/consistent activity: **Accountants, salespeople**
- **Increased physical activity** improves sleep quality.

### 🧬 Gender-Based Insights
- **Average Sleep Duration**: ~7 hours for both males and females.
- **Females** report **better sleep quality**, potentially due to hormonal differences.
- However, **females** are **more prone to sleep disorders** (linked to anxiety, hormonal changes).
- **Males** experience **higher stress levels** on average.

### ⏰ Age-Related Patterns
- **Older individuals** tend to **sleep longer**, but also show **higher prevalence of sleep disorders**.

### 😴 Sleep Patterns Summary
- Most people **do not suffer from sleep disorders**.
- **Sleep quality increases** with physical activity.
- **Sleep duration enhances** both quality and reduces stress.
- **Overweight individuals** are at **higher risk** for sleep disorders.

---

## 📈 Dashboard

Power BI Dashboard: "Shhh... I Wanna Sleep"


Key Insights from the Dashboard:
- Top Stressful Jobs: Sales roles and scientific positions top the list for average stress levels.

- Job Impact on Sleep: Engineers and lawyers sleep more; salespeople sleep the least.

- Physical Activity & Sleep: Higher physical activity is strongly linked to better sleep quality.

- Sleep Disorder Distribution: Nurses and teachers have more frequent sleep disorders.

- Age Group Analysis: People aged 57–66 report the best sleep rates.

- BMI vs Sleep Disorders: Overweight individuals are more likely to have sleep disorders like Sleep Apnea.

- Correlation Matrix:

  - Sleep Duration & Stress Level: -0.81
  - Sleep Quality & Physical Activity: +0.56
  - Sleep Quality & Stress Level: -0.86

You can explore metrics using filters by gender, age, occupation, and BMI category to see how lifestyle factors vary.

---

## 🚀 Tools & Technologies

- **Python (Pandas, Seaborn, Matplotlib)**: For EDA
- **Power BI**: For visualization and dashboarding
- **Jupyter Notebook**: Reporting and code organization
