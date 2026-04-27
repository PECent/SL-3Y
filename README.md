# SL‑3Y — Student Lifestyle & Academic Performance (3‑Year Longitudinal Dataset)

**SL‑3Y**  
**Student Lifestyle – 3 Years**  
A Longitudinal Dataset of Student Well‑Being, Behavior, and Academic Performance

SL‑3Y is a longitudinal dataset containing **1518 university students** tracked over **three academic years**.  
It includes **142 lifestyle‑related variables**, grouped into six domains:

- Study habits  
- Physical health  
- Mental well‑being  
- Time management  
- Technology use  
- Social engagement  

Academic performance is represented using **GPA normalized within each academic program**, allowing fair comparison across disciplines.

---

## Dataset Summary

- **Name:** SL‑3Y  
- **Type:** Longitudinal behavioral and academic dataset  
- **Participants:** 1518 students  
- **Duration:** 3 academic years  
- **Variables:** 142 lifestyle variables + normalized GPA  
- **Measurement frequency:** Semester-level observations  
- **Purpose:** Modeling how lifestyle factors influence academic outcomes

---

# 1. Study Habits (≈28 variables)

Variable | Description | Type | Unit  
--- | --- | --- | ---  
weekly_study_hours | total weekly hours spent studying | numeric | hours/week  
lecture_attendance_rate | percentage of attended lectures | numeric | %  
tutorial_attendance_rate | percentage of attended tutorials | numeric | %  
assignment_completion_rate | percent of assignments submitted | numeric | %  
note_taking_frequency | lecture note taking | numeric | times/week  
reading_materials_hours | reading time | numeric | hours/week  
library_visits | library visits | numeric | visits/week  
group_study_frequency | study group sessions | numeric | sessions/week  
study_consistency_index | variation in weekly study | numeric | index  
study_planning_score | planned study schedule score | numeric | 1–10  
revision_hours | exam preparation | numeric | hours/week  
late_study_sessions | after‑10pm sessions | numeric | sessions/week  
preferred_study_method | primary study method | categorical | —  
course_materials_downloads | downloads | numeric | count/week  
practice_problem_hours | time solving exercises | numeric | hours/week  
online_learning_usage | digital learning participation | categorical | —  
class_participation_score | active participation | numeric | 1–10  
lab_attendance_rate | lab attendance | numeric | %  
office_hour_visits | office hour visits | numeric | visits/month  
study_break_frequency | breaks per study session | numeric | count  
avg_study_session_length | typical session length | numeric | minutes  
study_environment_quality | quality of study space | numeric | 1–10  
course_engagement_index | engagement score | numeric | index  
flashcard_usage | flashcard usage | numeric | sessions/week  
study_material_organization | organization score | numeric | 1–10  
exam_preparation_duration | days before exam | numeric | days  
study_procrastination_level | procrastination | numeric | 1–10  
preferred_study_location | location | categorical | —

---

# 2. Physical Health (≈24 variables)

Variable | Description | Type | Unit  
--- | --- | --- | ---  
sleep_duration | avg sleep | numeric | hours/night  
sleep_quality_score | sleep quality | numeric | 1–10  
physical_activity_frequency | workouts | numeric | times/week  
exercise_duration | workout length | numeric | minutes/session  
bmi | body mass index | numeric | kg/m²  
resting_heart_rate | RHR | numeric | bpm  
steps_per_day | steps | numeric | steps/day  
alcohol_consumption | alcohol units | numeric | units/week  
caffeine_intake | caffeinated drinks | numeric | cups/day  
nutritional_quality_score | diet quality | numeric | 1–10  
water_intake | hydration | numeric | L/day  
smoking_status | smoking category | categorical | —  
chronic_condition_indicator | chronic illness | categorical | —  
screentime_before_bed | screen use before bed | numeric | minutes  
meal_regularities | regular meals | numeric | meals/day  
fruit_veg_servings | servings of produce | numeric | servings/day  
snacking_frequency | snacks | numeric | times/day  
fast_food_frequency | fast food | numeric | meals/week  
body_fat_percentage | fat % | numeric | %  
weight | body weight | numeric | kg  
standing_time | daily standing | numeric | hours/day  
sedentary_time | daily sitting | numeric | hours/day  
medical_appointments | health visits | numeric | visits/semester  
sleep_variability | sleep variation | numeric | hours

---

# 3. Mental Well‑Being (≈22 variables)

Variable | Description | Type | Unit  
--- | --- | --- | ---  
stress_level | perceived stress | numeric | 1–10  
anxiety_scale | anxiety index | numeric | 1–10  
depression_scale | depression index | numeric | 1–10  
mood_stability | mood fluctuation | numeric | 1–10  
life_satisfaction | life satisfaction | numeric | 1–10  
burnout_score | academic burnout | numeric | 1–10  
social_interaction_frequency | social outings | numeric | times/week  
club_participation | clubs joined | numeric | count  
friend_support_score | peer support | numeric | 1–10  
family_contact_frequency | family interaction | numeric | contacts/week  
loneliness_score | loneliness | numeric | 1–10  
mindfulness_practice | meditation | numeric | sessions/week  
hobby_engagement_hours | hobbies | numeric | hours/week  
emotional_regulation_score | emotional control | numeric | 1–10  
self_esteem_score | self‑esteem | numeric | 1–10  
academic_pressure_level | academic pressure | numeric | 1–10  
major_satisfaction | degree satisfaction | numeric | 1–10  
optimism_score | optimism | numeric | 1–10  
sleep_related_stress | stress affecting sleep | numeric | 1–10  
social_activity_hours | time with peers | numeric | hours/week  
screen_time_for_entertainment | entertainment screen time | numeric | hours/day  
stress_recovery_time | recovery from stress | numeric | hours

---

# 4. Time Management (≈22 variables)

Variable | Description | Type | Unit  
--- | --- | --- | ---  
schedule_regularities | routine consistency | numeric | 1–10  
calendar_usage | planner use | numeric | times/week  
task_completion_punctuality | tasks on time | numeric | %  
assignment_submission_timing | early submission time | numeric | hours  
time_spent_on_commuting | commute duration | numeric | minutes/day  
class_to_class_transition_time | between classes | numeric | minutes/day  
early_start_frequency | early days | numeric | days/week  
lateness_to_class | class lateness | numeric | events/month  
daily_free_time | free hours | numeric | hours/day  
work_life_balance | balance score | numeric | 1–10  
time_wasted_on_distractions | distractions | numeric | hours/day  
planner_accuracy | adherence to plan | numeric | 1–10  
break_scheduling | scheduled breaks | numeric | breaks/day  
deadline_awareness_score | deadline awareness | numeric | 1–10  
focus_block_duration | deep work | numeric | minutes  
multitasking_frequency | multitasking | numeric | count  
time_spent_in_meetings | meetings | numeric | hours/week  
task_overload_frequency | overload days | numeric | days/week  
routine_stability_score | week‑to‑week consistency | numeric | 1–10  
weekend_productivity | weekend productivity | numeric | 1–10  
evening_productivity | evening productivity | numeric | 1–10  
time_allocation_variability | allocation variability | numeric | index

---

# 5. Technology Use (≈22 variables)

Variable | Description | Type | Unit  
--- | --- | --- | ---  
daily_screen_time | screen time | numeric | hours/day  
educational_app_usage | learning platforms | numeric | hours/day  
social_media_time | social media | numeric | hours/day  
gaming_time | gaming | numeric | hours/day  
device_switching_frequency | switching devices | numeric | switches/day  
notifications_received | notifications | numeric | count/day  
notifications_checked | notification checks | numeric | count/day  
lms_login_frequency | LMS logins | numeric | logins/day  
online_forum_participation | forum posts | numeric | posts/week  
video_lecture_hours | online lecture hours | numeric | hours/week  
digital_note_taking | digital note usage | numeric | %  
cloud_storage_usage | cloud storage | numeric | GB  
internet_stability_score | internet quality | numeric | 1–10  
cyberloafing_time | unproductive browsing | numeric | hours/day  
tech_multitasking_level | apps used concurrently | numeric | count  
screen_break_frequency | breaks from screen | numeric | breaks/day  
late_night_tech_use | after‑midnight use | numeric | minutes/day  
device_usage_before_class | screen time pre‑class | numeric | minutes  
email_checking_frequency | email checks | numeric | checks/day  
wearable_device_usage | smartwatch use | categorical | —  
software_proficiency_score | tech proficiency | numeric | 1–10  
digital_distraction_score | distraction due to tech | numeric | 1–10

---

# 6. Social Engagement (≈24 variables)

Variable | Description | Type | Unit  
--- | --- | --- | ---  
study_group_participation | study groups | numeric | sessions/week  
extracurricular_activity_hours | extracurriculars | numeric | hours/week  
club_meetings_attended | club meetings | numeric | meetings/month  
sports_team_participation | sports membership | categorical | —  
campus_event_attendance | campus events | numeric | events/month  
volunteering_hours | volunteering | numeric | hours/month  
peer_interaction_frequency | peer interactions | numeric | interactions/day  
mentorship_sessions | mentorship meetings | numeric | meetings/month  
social_network_size | close contacts | numeric | count  
student_org_memberships | student orgs | numeric | count  
dorm_social_activity | dorm events | numeric | events/week  
academic_collaboration_time | collaboration | numeric | hours/week  
relationship_status | relationship | categorical | —  
conflict_frequency | conflicts | numeric | events/month  
interpersonal_support_score | support | numeric | 1–10  
communication_skill_score | communication | numeric | 1–10  
time_spent_with_roommates | roommate time | numeric | hours/week  
cultural_event_participation | cultural events | numeric | events/month  
networking_event_attendance | networking events | numeric | events/month  
peer_help_frequency | academic help given | numeric | times/week  
advisor_meeting_frequency | advisor meetings | numeric | meetings/semester  
team_project_involvement | team projects | numeric | count/semester  
campus_club_roles | leadership roles | categorical | —  
community_engagement_score | community involvement | numeric | 1–10

---

# Academic Performance

Variable | Description | Type | Unit  
--- | --- | --- | ---  
normalized_gpa | GPA normalized within program | numeric | 0–4 scale  

---

# How to Use

This dataset is suitable for:

- behavioral analytics  
- longitudinal modeling  
- academic performance prediction  
- feature selection research  
- lifestyle–performance correlation studies  


