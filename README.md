# (  Investigating The Dataset No-Show Appointments )
## by (Adetimilehin  Pelumi)


## Dataset

The dataset ontains information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up
for their appointment. A number of characteristics about the patient are included in each row.

* **PatientId** Identification of a patient
* **AppointmentID** Identification of each appointment(was later dropped)

* **Gender** Male or Female.

* **ScheduledDay** The day of the actuall appointment, when they have to visit the doctor.

* **AppointmentDay** The day someone called or registered the appointment, this is before appointment of course.

* **Age** How old is the patient.

* **Neighbourhood** Where the appointment takes place.

* **Scholarship** True of False .

* **Hipertension** True or False

* **Diabetes** True or False

* **Alcoholism** True or False

* **Handcap** True or False

* **SMS_received** 1 or more messages sent to the patient.

* **No-show** True or False.


## Summary of Findings

It shows clearly the Females tends to see the doctors more than their male counterpart. And that was only possible due to their numbers, But when you compare the ratio,you see there is little too no difference in who sees the doctor the most.


A few percentage of patient were sponsored for the appointments. While that might seem like a good reason for people who are sponsored not to miss their appointments,It just wasn't. Been sponsored makes a very little difference in attending appointments

**Limitations**
1. The ratio of male to female in the data is not balanced so there will probably be a bias towards the females
2. Cannot show strong correlations between factors since my analysis is on  categorical data.
