# Hospital-Management-System
The purpose of the project entitled as HOSPITAL MANAGEMENT SYSTEM is to computerize the Front Office Management of Hospital to develop software which is user friendly simple, fast, and cost-effective. It deals with the collection of patient’s information, diagnosis details, etc. Traditionally, it was done manually. The main function of the system is register and store patient details and doctor details and retrieve these details as and when required, and also to manipulate these details meaningfully. System input contains patient details, diagnosis details, while system output is to get these details on to the screen. The Hospital Management System can be entered using a username and password. It is accessible either by an administrator or doctor. Only they can add data into the database. The data can be retrieved easily. The data are well protected for personal use and makes the data processing very fast.

## Tools and Technologies Used
### Hardware Requirements: 
PROCESSOR : Intel dual Core ,i3
RAM : 1 GBHARD
DISK : 80 GB
### Software Requirements:
OPERATING SYSTEM : Windows 7/ XP/8/10
FRONT END : Java NetBeans/Eclipse IDE
DATABASE : MySQL

## Database Schema
* Hospital (Hosp_id , Hosp_name , City , State)
Hospital table has multi-valued attribute contact_no.
* Hospital_contact (Hosp_id , contact_no)
* General_ward (ward_id , rate, no_of_days, patientID)
* Single_ward (ward_id , rate, no_of_days, patientID)
* Duo_ward (ward_id , rate, no_of_days, patientID)
* Patients (patientID , Name , Address , Age , Gender, bloodGroup, anyMajorDisease)
Patients table has multi-valued attribute set_of_phone.
* Patients_phone (patientID , set_of_phone)
* Patientreport(patientID, symptoms, diagnosis, medicines, doc_id, wardReq, typeWard, no_of_days)
* Doctors (doc_id , doct_name , specialization_in, email, address)
Contact_no is a multi-valued attribute.
* Doctor_contact (doct_id , contact_no)
* Doctor_login(username, password)
* Medicine(med_name, price)

## Database Design using Schema Diagram
![schema dia](https://user-images.githubusercontent.com/68106718/133877682-2e3cb5b0-0a69-4c21-ab42-90c77f53ab6d.png)

