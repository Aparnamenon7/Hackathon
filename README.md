![githubpic](https://user-images.githubusercontent.com/126552313/221784874-670cd550-8440-4f18-bc5e-44257752c230.png)

# Medical Idem

ABSTRACT

MEDICAL IDEM

The idea that we present you with is medical idem which means medical identity. A centralized system in which the medical records of entire population is safely stored,handled and added by verified hospitals and doctors making it easier to know the medical history of a particular person which in turn increases the efficiency of doctors and make it easier to diagnose  a disease. Medical idem demonstrates that hospital systems can organize and act quickly in any circumstance with the necessary details required. 

The application consists of 2 views consisting of the  client side and administrator side. In the clientside people are able to access their own medical records once their identity is created and in this view the viewer can only view their records to get the information. Any changes to a person’s medical record can be done in the administrator side which is only handled by verified hospitals and the doctors are verifies under different hospitals. In order to make changes to a person’s medical record, he or she will have to visit an hospital and have a checkup to induce changes to the record.

The most challenging part of it is the security as once leaked a person’s medical history and their life is put at stake, for which 2 factor authentication is implemented. A person can only get a verified medical idem account once they book an appointment in an hospital for which the person has to go to the hospital with certificates of each disease, vaccinations and allergies which will be verified and entered by the hospital staff and an medical id is generated and given to the person. An hospital itself may not be able to access a persons medical record but can access them only with a permission of a person who will be sent an OTP/ secret code which will be given to the authorised person in order  to access the records.

The objective of medical idem is  :-
•	To provide a comprehensive range of treatment services.
•	To Shape the process of treatment according to the needs of patient. 
•	Increase the efficiency of medical services.
•	Advancement of Treatments that can be provided.
•	Diagnosing of diseases with ease.

 Platforms used to make the application   :-
•	Node Js
•	Flutter
•	React 
•	Postgres SQL


## Team members
1. Paul Prince (https://github.com/paulprince24542)
2. Aparna Menon (https://github.com/Aparnamenon7)
3. Bijoy Anil  (https://github.com/bijoy7034)
4. Adithya S Nair (https://github.com/Adithya-S-Nair)
## Team Id
Team id here
## Link to product walkthrough
[[link to video]] https://drive.google.com/file/d/15vscj_UG0zmZNnn_7aNe7BuJBDFU-iEC/view?usp=share_link
## How it Works ?
1. Working of the project 

Steps

Creating an account for the user to enter the name address and other basic details with the nearest hospital to add the records and then manually go to the hospital to get the user login details and completion of the records

Logging in into the system by a perticular hospital. 

The admin gets the appointment booking and their profile is verified.

After the verification of the profile the Records are updated and additional details are added to the medical record.

In the user view the user visits their profile with all the details about them and their records.

2. https://drive.google.com/file/d/15vscj_UG0zmZNnn_7aNe7BuJBDFU-iEC/view?usp=share_link
## Libraries used
Node Js
Flutter
React
Postgres SQL
## How to configure
Instructions for setting up project
## How to Run
The prototype of medical idem is a web application which can be accessed using the link of the application. It can also be made into an mobile application for the ease to access the records.

It consists of 2 views user view and an admin view in which the user view is non editable but can only be read, any changes to details of a patient cannot be done by the patient except for personal details like address, phone number, email etc. 

The admin view can only be accessed by verified hospitals and doctors in which a person's new record can be added, no changes can be done to the previously existing records. The entered medical record is only entered by the hospital if the user gives consent to add particular details to the record. For an administrator to access the records of a patient, a 2 step authentication is performed to make sure that the records are accessed with the consent of the patient.

In order to generate an medical identity the user has to book an appointment with one of the listed verified hospitals and then manually go to the hospital to enter medical records with appropriate certificates of each chekups, vaccination, allergies which is then entered into the system after which the account is verified and an medical identity is generated which given as user id in the application

After this the medical identity can then be linked to adhaar card with athe approval of government in order to make it more successfull

Once medical id is generated the user can then have all their medical records entered by each authorised hospitals and store their medical records for throughput their life.

In the admin view the prototype consists of elements  which consists of information about:-

Dashboard: It consists of information like appointment count and other basic details.

Search Patient: Here a particular patient can be searched/viewed by their medical identity and then their details are accessed using the appropriate security measures.

Hospital records: Under this details such as Patient, Appointments, Doctors , Diagnosis is stored

Doctor Details : Where a verifies Doctors details can be viewed including details like their name, doctor id etc of a particular hospital.

Help : To clear any difficulties faced by the user.

The most important factor of this application is its security which can never be compromised as it contains a detailed record of a person's health and their issues, therefore implementation of proper security plays a vital role. In this prototype we have ensured security with a 2 factor authentication such as otp and secret code which the admin has to enter in order to access a patients record. 


