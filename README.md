![no-show-patients](https://github.com/user-attachments/assets/5fd8d457-284e-43be-a008-5461cb8961e3)

# No-Show, No-Go! Unraveling the Mystery of Missed Appointments. 
No-Show Appointments: Exploratory data analysis project. 

# Description
This project focuses on analyzing and predicting medical appointment no-shows using Python. No-shows can lead to inefficiencies in healthcare, increased costs, and longer wait times for patients. The goal of this project is to identify key factors influencing patient attendance and develop a data-driven approach to minimize missed appointments.

By performing exploratory data analysis (EDA), this project aims to:
- Identify patterns and trends in no-show appointments
- Understand the impact of factors like age, gender, medical history, and SMS reminders

This analysis can help healthcare providers optimize scheduling, improve patient engagement, and reduce appointment no-shows, leading to better resource management and patient care.

# Dataset

The dataset consists of 110,527  made in Brazil. medical appointments with 14 associated variables, capturing key details about each appointment and patient. These variables help in understanding factors that influence patient attendance and no-show behavior.

Key Features in the Dataset:
- Patient ID: Unique identifier for each patient
- Appointment ID: Unique identifier for each appointment
- Gender: Patient’s gender (Male/Female)
- Scheduled Day: The date when the appointment was scheduled
- Appointment Day: The actual date of the appointment
- Age: Patient’s age in years
- Neighborhood: The location of the hospital/clinic where the appointment was scheduled
- Scholarship: Whether the patient is enrolled in a social welfare program (e.g., Bolsa Família)
- Hypertension: Indicates if the patient has hypertension (0 = No, 1 = Yes)
- Diabetes: Indicates if the patient has diabetes (0 = No, 1 = Yes)
- Alcoholism: Indicates if the patient has a history of alcoholism (0 = No, 1 = Yes)
- Handicap: Indicates if the patient has a disability (0 = No, 1 = Yes)
- SMS Received: Whether the patient received an SMS reminder (0 = No, 1 = Yes)
- No-Show: The target variable indicating whether the patient attended the appointment (No = Attended, Yes = Did Not Attend)

# How to Run

## Dependencies
The following is a list of libraries used in this project:- 
1. Data Manipulation: packages like pandas and numpy that are used to handle and import datasets.
   - import pandas as pd
   - import numpy as np 
2. Data Visualization: packages that were used to plot graphs for analysis or to comprehend matplotlib and seaborn.
   - import matplotlib.pyplot as plt
     matplotlib was used to create basic visualizations like bar charts and histograms
   - import seaborn as sns:
     builds more advanced and aesthetically pleasing plots, such as heatmaps and pair plots, to explore relationships in the data. Together, these libraries enable efficient analysis and visualization of medical appointment no-shows.
