# 🧠 Mental Health Questionnaire Analysis

This project explores the mental health status of children aged 8–10 using questionnaire data collected in conflict-affected areas. 
The goal is to analyze psychological indicators, assess the effects of trauma, and evaluate the need for psychosocial support using statistical and machine learning techniques.

---

## 📂 Project Structure

```bash
Mental health questionnaire analysis/
│
├── Data gathering/                  # Raw and preprocessed Excel data from Google Forms
│   ├── QA (Responses).xlsx
│   ├── English responses before encoding.xlsx
│   └── Study of mental health of children aged 8-10 - Google Forms.pdf
│
├── Factor based analysis/          # Feature engineering and EDA
│   ├── Data_prep.ipynb
│   ├── Analysis.ipynb
│   ├── Model_prep.ipynb
│   └── QA_encoded.csv
│
├── ML model/                       # Model training and evaluation
│   ├── Mobel_building_and_evaluation.ipynb
│   └── Model_input.csv
│
├── SPSS/                           # Statistical analysis using SPSS
│   ├── Chi-square.spv
│   ├── ANOVA.spv
│   ├── Paired sample t-test.spv
│   ├── Independent sample t-test.spv
│   ├── QA(Responses)SPSS.sav
│   └── Questionnaire analysis.pdf
│
├── Assets/                         # Plots and visual summaries
│   ├── confusion_matrix.png
│   ├── Correlation.png
│   ├── mental_health_by_district_destruction.png
│   ├── mental_health_by_displacement_bombs.png
│   └── psych_support_by_trauma.png
