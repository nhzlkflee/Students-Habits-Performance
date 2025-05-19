# Project: Students-Habits-Performance

---
## 📘 Dataset Overview

- This synthetic dataset simulates the academic and lifestyle behaviors of 80,000 students, including diverse features like study habits, mental health, family background, motivation, and environmental factors. The goal is to explore how different variables affect student performance in terms of GPA and exam scores.
---
## 🧠 Project Goals
- Predict exam scores: Use study habits, sleep, and motivation to predict exam_score.
- Classify dropout risk: Predict dropout_risk (Yes/No) using behavioral and environmental data.
- Explore correlation: Find key features that most influence academic performance.
----

## 📊 **Dataset**  
The dataset contains the following columns:  
| Column Name      | Description                              |  
|-------------------|------------------------------------------|  
| **student_id**    | Unique student identifier.     |  
| **gender**        | Gender of the students.                 |  
| **age**           | age of the students.                    |  
|**major**          | Field of study (e.g., Computer Science, Engineering, Arts).|
|**study_hours_per_day** | Average hours studied daily. |
|**social_media_hours, netflix_hours, screen_time** | Time spent on various screens. |
|**part_time_job** | Whether the student has a job (Yes/No). |
|**attendance_percentage** | Academic attendance in percentage. |
|**sleep_hours, exercise_frequency, diet_quality** | Lifestyle factors. |
|**mental_health_rating, stress_level, exam_anxiety_score** | Psychological indicators (1–10). |
|**extracurricular_participation, access_to_tutoring** | Support and engagement. |
|**family_income_range, parental_support_level, parental_education_level** | Background and support. |
|**motivation_level, time_management_score** | Self-management skills (1–10). |
|**learning_style** | Preferred method of learning. |
|**study_environment** | Common location for studying. |
|**dropout_risk** | Yes/No — derived from stress and motivation levels.|
|**previous_gpa, exam_score**| Target performance indicators.|

---

## 📌 Usage Ideas
- Regression & classification ML models
- Exploratory data analysis
- Education research
- Student success prediction
- Academic risk detection
---
## 📊 Interpreting Results
- RMSE (Root Mean Squared Error): Lower is better. Gives average error size.
- MAE (Mean Absolute Error): Also lower is better. Easier to interpret directly.
- R² (R-squared Score): Between 0 and 1. Higher means better fit.
