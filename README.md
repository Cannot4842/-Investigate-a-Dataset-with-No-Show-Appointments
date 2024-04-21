# No-Show Appointments Analysis Project

## Project Overview
This project analyzes a dataset of 110,527 medical appointments in Brazil to uncover factors influencing patient no-shows. By exploring various demographic, socioeconomic, and geographical variables, the project aims to identify key determinants that affect whether patients miss their scheduled medical appointments.

## Dataset Description
The No-Show Appointments dataset includes the following key information for each medical appointment:
- **PatientId**: Unique identifier for each patient
- **AppointmentID**: Unique identifier for each appointment
- **Gender**: Gender of the patient
- **ScheduledDay**: The day the appointment was scheduled
- **AppointmentDay**: The day of the actual appointment
- **Age**: Age of the patient
- **Neighbourhood**: Location of the appointment
- Additional indicators for health conditions, scholarship status, and other relevant attributes.

## Research Questions
This project focuses on several analytical questions to understand the dynamics behind appointment no-shows:
1. **Health Conditions and No-Show Rates**: How does the presence of hypertension affect appointment attendance?
2. **Socioeconomic Factors**: Does the availability of a scholarship impact a patient's likelihood to attend an appointment?
3. **Geographic and Temporal Factors**: What are the top 20 neighborhoods with the highest no-show rates?

## Installation
To run the analysis, you need Python and several libraries. Install the necessary dependencies with:
```bash
pip install pandas matplotlib seaborn numpy
