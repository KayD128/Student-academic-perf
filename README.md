# Student-academic-perf

## Information on each columns in the table
person_id - will be dropped, since it is a unique primary key
Age - useful
gender - useful
nationality - maybe...
first_generation - first generation guys face higher drop our risk. 1 = first to attend college in family
disability_status - 1 = one with learning disability
family_income_level - low, middle, high status
scholarship_holder - 1 = one with scholarship
tuition_up_to_date - 1 = fees paid on time
part_time_job - 1 = student working part time
weekly_work_hours = 0 for students not holding a job
course_type = field of study
study_mode = full-time and part-time
semester = 1 - 8
international_student - student studying outside their home
admission_grade - 0-200 scale
previous_qualification - 30-200 scale
units_enrolled - 
units_passed - 
units_failed - there's a formula here somewhere.
gpa_semester_1 - out of 4.0        
gpa_semester_2 - declining GPA between semester 1 and 2
attendance_rate - out of 100
assignments_submitted_rate - percentage of submitted assignments
library_visits_per_month - number of visits
lms_logins_per_week - higher for online students. Does it have to do with the target column?
extracurricular_activities - 1 = at lest in 1 club
missed_deadlines - sign of disengagement
stress_level - Self-reported chronic stress score where 1 is minimal and 10 is extreme. 
mental_health_support - 1 = student has accessed counselling or mental health services on campu, check relation to stress_level.         
satisfaction_score - self-reported campus and course rating 
commute_time_mins - Daily one-way commute time in minutes. Longer commutes reduce campus engagement and increase fatigue.
sleep_hours - how does it affect drop out?                
dropout - 1= dropout, 0 = enrolled or graduated


## Objectives
Binary Classification - Predict dropout (0 or 1)
Early Warning System - Identify at-risk students early
Fairness Analysis - Does the model perform equally across income levels, gender, and first-generation status?
Feature Importance - Which academic vs financial vs behavioural signals matter most?
Subgroup Analysis - How does dropout risk vary by course type and study mode?
Threshold Optimization - Tune for recall (catching all dropouts) vs precision


## Recommended Models
- Logistic Regression · Random Forest · XGBoost · LightGBM · CatBoost · Neural Networks
