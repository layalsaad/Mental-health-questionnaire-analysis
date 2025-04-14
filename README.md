# 🧠 Mental Health Questionnaire Analysis

This project explores the mental health status of children aged 8–10 using questionnaire data collected in conflict-affected areas. 
The goal is to analyze psychological indicators, assess the effects of trauma, and evaluate the need for psychosocial support using statistical and machine learning techniques.

### To run the code, install libraries in requirements.txt and run all notebook cells.

Key Insights from Data Analysis:
 - “Home” Isn’t Always Safe: Children who knew about their house destruction whether experiencing it or not suffered severe mental distress, proving uncertainty can be as traumatic as direct exposure.
 - Silent Suffering: Kids who avoided war topics had the highest anxiety levels, hiding pain behind silence.
 - Family Over Everything: Parental separation whether caused by death or other circumstances harmed mental health more than losing a home. Stability and connection are lifelines.
 - Education = Resilience: Children attending school in-person coped better. Routine and community matter.


Attributes of the dataset
The following are the attributes used in the data.
 - Age: The numerical age of the individual in the data set.
 - Gender: Male or female.
 - Current residence: The location where the person currently lives.
 - District: Specific administrative area or region of residence.
 - Parent occupation: Job or professional status of the person’s parent(s) before the war.
 - Displacement: Whether the individual has been forced to move from their original home.
 - Displaced months: Number of months spent in displacement.
 - Parent current employment: Current employment status of the person’s parent(s).
 - Experiencing bombs: Exposure to bombing experiences of direct conflict.
 - Family member loss: Whether the person has lost a family member during the conflict.
 - House destruction: The extent of damage or complete destruction of the person’s home.
 - Separated from parent: Determines whether the child was separated from one or both parents.
 - Food/water shortages: Experience of limited access to food and water.
 - Sleeping before: Sleep patterns or quality before the war.
 - Hypervigilance after: Increased state of alertness or anxiety after the event.
 - Nightmares before: Frequency or presence of nightmares before the war.
 - Nightmares after: Frequency or presence of nightmare patterns after war.
 - Worry/fear before: Level of anxiety or fear before the conflict.
 - Worry/fear after: Level of anxiety or fear after the war.
 - Aggressive behavior before: Level of aggressive behavior before the war.
 - Aggressive behavior after: Level of aggressive behavior after the war.
 - Family/friends withdrawal before: Patterns of social interaction before the war.
 - Family/friends withdrawal after: Patterns of social interactions after the war.
 - Mood swings before: Emotional stability or mood fluctuations before the conflict.
 - Mood swings after: Emotional stability or mood fluctuations after the conflict.
 - Avoid war topics after: Tendency to avoid discussions related to conflict.
 - Mental health currently: Current mental health status of the child.
 - Coping Activities: Coping strategies to avoid stress.
 - Received psychological support: Whether professional mental health support was obtained.
 - Effectiveness: Impact of psychological interventions on the child.
 - Attend school during: Educational participation during the conflict period.
 - Attend school currently: Current educational attendance.
 - Academic performance after: Educational achievement after the war.
 - Participation in social activities: Involvement in social interactions and community events.
 - Current need of psychological support: The need for mental health assistance.
 - Current need of educational materials: The need for learning resources.
 - Current need of safe housing: The need for secure housing.
 - Current need of medical care: The need for medical health requirements.
 - Current need of food/water: The need for food and water.

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
├── Factor based analysis/          # Data analysis, Feature engineering, and EDA
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
