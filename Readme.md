# Brazil Medical Appointment Dataset Exploration
## by Mojeed Arikewuyo


## Dataset

The dataset consists of information on 109909 medical appointments in Brazil's hospitals, with 10 columns identifying specific characterisitics of the patients that booked the appointments (patientid, gender, scheduledday, appointmentday, age, neighbourhood, scholarship, sms_received, appointment and ailment). The dataset is available [here](https://www.kaggle.com/datasets/ariks90/cleaned-brazil-may2016-noshow-medical-appointments).

## Summary of Findings

The exploration process saw me verify the relationship of various predictor variables on the appointments being kept or missed. I deduced the modal age of the patients to be between 30 and 40, and a steady deline of older patients that booked medical appointments. I found that there was particularly more female patients booking appointments than their male counterparts, and that most of the patients generally were not registered under the [Bolsa Familia Welfare Program](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia). Further, most of the patients did not receive messages from the hospitals as regards their appointments. However, that did not cause a reduced number of present appointments, as a distinctly large bulk of the patients who didn't receive messages still kept their appointments. 

In a review beyond the main variable, and into the locations or neighbourhoods, it was found that patients generally kept more appointments than they missed, and that patients who had their appointment days on the same day they scheduled for it, tended to keep their appointments more than those whose appointment day fell on a different day. Through the analysis, I found that younger patients tended to be a part of the welfare program more than the adults, and that they kept more of their appointments than they missed.

## Key Insights for Presentation

The focus here is on the appointments as the main feature, and on the central characteristics of the patient, which are the age and the Bolsa Familia Welfare Scholarship Program. The appointment variable is first introduced, followed by the Patient's age, which is fine tuned through scaling and bins to better display the unique properties surrounding the ages.

Relationship analysis then begins, with the violin plot showing the relationship between age, a numeric variable, and the appointment, a categorical variable. The relationship between the Welfare scholarship and the appointment is then checked with the use of the Clustered Bar Chart, as this clearly shows all needed preliminary information about the relationship between them. The age and scholarship variables are then analysed together, before I then proceed to test how the relationship between all three variables via the barplot and the pointplot. The color encoding in the barplot and pointplot especially help to pinpoint the needed central tendencies being displayed and its significance to the analysis.