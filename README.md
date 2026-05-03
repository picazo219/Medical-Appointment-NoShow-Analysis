# Medical-Appointment-NoShow-Analysis
Data analysis project using Power BI and Python to identify clinical absenteeism patterns
![Dashboard Preview](Images/Medical%20Appointment%20NoShow%20-%20Dashboard.png)
1. Summary

This project analyzes a dataset of 110,521 medical appointments to identify the key drivers behind the 20.19% no-show rate. I developed this interactive dashboard to provide actionable insights into patient absenteeism. The goal is to optimize clinic operations and reduce revenue leakage caused by missed appointments.

2. Business Problem

High no-show rates disrupt clinical workflows, increase waiting times for other patients, and result in significant financial losses for healthcare providers. This analysis seeks to answer:

* Which demographic groups are most likely to miss appointments?
* How does the waiting period (Lead Time) affect attendance?
* Are SMS reminders effectively reducing absenteeism?

3. Key Insights

* Waiting Period Impact: The Average Waiting Period is 10.18 days. Analysis shows that as the "Lead Time" increases, the probability of a no-show rises significantly, stabilizing above 30% after the 10-day mark.

* Demographic Patterns: Patients in the "Teen" and "Young Adult" life stages have the highest no-show rates compared to Seniors, who are the most reliable attendees.
  
* Health Profiles: Patients with Hypertension represent the largest volume of appointments (21,801), highlighting a critical group where attendance is vital for chronic disease management.
  
* SMS Effectiveness: While SMS reminders help, there is still a noticeable gap in attendance for appointments scheduled far in advance, regardless of the reminder.

4. Tech Stack & Methodology
* Power BI: Data modeling, DAX measures (No-Show Rate %, Avg Waiting Days), and interactive visualization.
* Python (Pandas/NumPy): Data cleaning, handling missing values, and feature engineering.
* Excel: Initial data inspection and structure validation.

5. Strategic Recommendations
* Targeted Reminders: Implement a specialized SMS/Call campaign for the Teen and Young Adult segments.
* Scheduling Optimization: Reduce the "Lead Time" for chronic patients (Hypertension/Diabetes) to under 7 days to maximize attendance.
* Geographic Focus: Prioritize operational improvements in top no-show neighborhoods like Santos Dumont and Santa Cecília.
