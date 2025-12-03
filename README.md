# MEdical_Appointments_EDA
📌 Healthcare Appointment No-Show Analysis (EDA)

A data-driven exploration of patient appointment behavior

# 📖 Project Overview

This project analyzes a real-world healthcare dataset containing 110K+ patient appointment records to understand why patients miss their medical appointments.
Through extensive Exploratory Data Analysis (EDA), I uncovered trends related to gender, weekdays, waiting time, and patient behavior that influence the likelihood of a patient showing up ("Yes") or missing ("No") their appointment.

The project focuses on cleaning messy date columns, engineering time-based features, detecting outliers, and generating meaningful business insights for healthcare scheduling optimization.

# 🎯 Objectives

Clean and preprocess healthcare appointment data

Analyze factors affecting patient attendance

Study gender distribution, weekday behavior, and waiting time impact

Identify patterns in No-Show vs Show appointments

Generate insights to help reduce no-show rates in hospitals

# 🧹 Data Cleaning & Feature Engineering

Key steps performed:

Converted ScheduledDay and AppointmentDay into proper datetime formats

Extracted weekdays and waiting time (days difference)

Removed irrelevant columns like PatientID, AppointmentID

Handled missing values and corrected datatype issues

Standardized categorical and numerical features

Verified distributions and detected outliers in Age, WaitingTime, etc.

# 🔍 Exploratory Data Analysis (EDA)
Key Questions Explored:

Do males or females attend appointments more?

Which weekdays have the highest/lowest attendance?

Does longer waiting time increase no-show probability?

Are certain patient conditions (like diabetes or hypertension) related to attendance?

What patterns exist in overall no-show behavior?

# 📊 Key Insights

Female patients attended more appointments compared to males.

Monday and Wednesday had the highest attendance, while Friday/Saturday had lower turnout.

Patients with longer waiting time between scheduling and appointment day were more likely to be No-Show.

Majority of the patients did not have chronic conditions such as diabetes or hypertension.

Age distribution showed that younger patients skipped appointments more frequently than older ones.

Data quality issues were resolved through timezone correction, date parsing, and removing unnecessary columns.

# 📈 Visualizations

The notebook includes plots for:

Gender vs Attendance

No-Show Distribution

Attendance by Weekday

Waiting Time Distribution

Correlation Matrix

Age Distribution & Outliers

Boxplots for categorical vs numerical analysis

(All created using Pandas, Matplotlib, Seaborn)

# 🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook
