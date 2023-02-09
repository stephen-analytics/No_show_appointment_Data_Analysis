# No-show Appointment Dataset Analysis


## by Stephen Onyeukwu


## Introduction
 The project is based on a dataset containing information about 100,000 medical appointments in Brazil, including characteristics of the patients and whether or not they showed up for their appointments. This project is a partial requirement for earning a certificate from the Udacity Data Analyst Nanodegree program.

 The project involves cleaning and exploring the data, and conducting analysis to test hypotheses and draw conclusions about the relationships between variables and the reasons why patients miss appointments.



## Dataset


The dataset contains information about 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row, such as:

- AppointmentID: Identification of each appointment.
- Gender: Male (M) or Female (F).
- ScheduledDay: The day someone called or registered the appointment, this   is before appointment of course.
- AppointmentDay: The day of the actual appointment, when they have to       visit the doctor.
- Age: How old is the patient.
- Neighbourhood: Where the appointment takes place.
- Scholarship: True (1) of False (0).
- Hipertension: True (1) or False (0).
- Diabetes: True (1) or False (0).
- Alcoholism: True (1) or False (0).
- Handcap: The handcap refers to the number of disabilites a person has.
- SMS_received: 1 or more messages sent to the patient.
- No-show: Yes or No.


## Installation

To run this project, you'll need to install the following libraries:

- pandas
- numpy
- matplotlib
- seaborn

## Project Overview

The project is divided into the following steps:

1. Data cleaning: Handle missing values, remove duplicate data, and convert data types to appropriate formats.

2. Data exploration: Use visualizations to understand the distribution of variables, relationships between variables, and patterns in the data.

3. Data analysis: Test hypotheses and draw conclusions about the relationships between variables and the reasons why patients miss appointments.



## Summary of findings

- Patients who did not receive SMS reminder showed up for their appointment more than those who received the SMS.
- Females showed up more than males for their appointment, also more females missed their appointment than males. we can say, gender is not  significant factors in determining whether or not a patient will show up for their appointment. The results of my research are not enough   to confidently assert that gender is not a determining factor in no-show responses due to the limitations in my study.
- Patients with certain health conditions, such as hypertension and diabetes showed up for their appointment at a very high rate. Due to the  limitations in the results, it is not possible to definitively state that hypertension and diabetes can accurately predict whether or not   a patient will show up for their appointment based on the data in this dataset.




