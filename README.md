![COVERPAGE](https://user-images.githubusercontent.com/75902424/151086143-ccf7836e-fe64-486b-95b4-0a37afeae4d3.JPG)
![contri](https://user-images.githubusercontent.com/75902424/151090705-15bd72b7-eb68-40fa-9941-6ae4c34b410e.JPG)
![con2](https://user-images.githubusercontent.com/75902424/151090830-8351f5b0-bd69-4ecd-b3ab-78f78ed0521d.JPG)
1. Title of the project: Hospital Management System.
2. Introduction of the proposed web application: 
	The proposed web application is created to simplify and organise the hospital management system. This system can make the administration process easier by storing users’ data in the system instead of using a manual way such as keeping data on physical documents. This system includes adding, deleting, updating and managing data in a systematic and efficient manner.  

3. Objective of the proposed web application: 
The  “Hospital Management System” will be developed in Laravel frame. All the record stores in the database. It manages inpatient, outpatient, doctors, and employee’s record. This is the complete software application of the Hospital management system. This project will be designed and coded in Visual Studio & database management is handled by XAMPP Server. This system mainly focuses on basic operations in a Hospital like Appointment module, Inpatient and Outpatient module, Treatment module, Payment, billing module, Reports, and statistics module. This application is easy to use for both beginners and advanced users. It features a familiar and well thought-out, an attractive user interface, combined with strong searching insertion and reporting capabilities. The report generation facility of this application helps to get the complete overview of hospitals. 

4. Features and functionalities of the proposed web application: 
The main objectives of our Hospital Management System are Design a system for better patient care, reduce hospital operating costs, provide MIS (Management Information System) report on demand to management for better decision making. Moreover, it would focus on managing doctors, managing patients, appointments, and the registration. 

4.1 Managing doctors: Through that panel, the user can add new listings of doctors. It is possible to edit and delete the list. Records that have been deleted will be shown in a tabular format that can be undeleted. 
4.2 Managing patients: handle patient records and perform operations such as change, delete, and undelete on them. 
4.3 Appointments: Appointments can be managed in the application using the doctors and patients IDs. 
4.4 Registration: Check-in and check-out procedures for patients, automation in the laboratory, manage schedule, manage pharmacy, keeping track of patients records, managing financial, keeping track of patients records, managing financial, keeping track of employees, managing lap, payroll system for employees, managing lap, payroll system for employees, manage prescriptions, consultant doctor, manage beds, manage human resources. 
Admins may manage physicians, patients, add doctor specialisations, and review the session records of both doctors and patients. This approach simplifies hospital management for both patients and clinicians. This project’s design is simple, and the user will find it easy to comprehend, use, and navigate. 

5. Properly define the views, controllers, routes and models. Include ERD for your database tables with one-to-many relationship: 

Entity Relation diagram:

![entity](https://user-images.githubusercontent.com/75902424/151086375-88fb9f96-29ad-4bb0-b65d-2976fe925b89.JPG)

View:
main.jsp,
Header.jsp,
HospitalInfo.jsp,
DoctorInfo.jsp,

Controller:
Login.java,
Appoitment.java

Model:
Login.java,
Patient.java,
Doctor.java

6. A sequence diagram to represent the interaction of the proposed web application: 

![Se](https://user-images.githubusercontent.com/75902424/151086518-e6168594-1c55-4ba4-9cc4-acbf7871b77d.JPG)

![Part2](https://user-images.githubusercontent.com/75902424/151086872-a79f1711-c0d1-41c3-9e2b-817dc184e1e8.JPG)

1. Departments: In this Hospital Management System, the management could able to add departments, also could able to see the departments list. 

![addDepartment](https://user-images.githubusercontent.com/75902424/151087055-e708d29f-32ed-4f34-b926-8b92defd0b25.JPG)
                                                                 Figure 1.1: Add Department 
![DepartmentList](https://user-images.githubusercontent.com/75902424/151087066-278c4c4d-7560-4939-ae27-6641c723476e.JPG)
                                               Figure 1.2: Department List 
					       
2. Doctors: The hospital management could add doctors, and could see the doctors list. Here would be doctors personal information for example: Name, National ID address, Medical Degree and Specialist then there are two buttons either to submit or to cancel.


![addDoctor](https://user-images.githubusercontent.com/75902424/151087167-2d96fffa-ff2a-4ff1-b961-5d5a155b6fac.JPG)
Figure 2.1: Add Doctor
![DoctorsList](https://user-images.githubusercontent.com/75902424/151087187-790cfd55-c7dc-49be-9e88-4536097275ff.JPG)
Figure 2.2: Doctors List

3. Patients: In this section the management of hospital could add patients, patients list, documents. This part would carry patients personal information such as: Patient first name, Phone number, Gender and Blood Group.


![addPatients](https://user-images.githubusercontent.com/75902424/151087333-ff50a692-856b-4a12-b728-ecc6869d832b.JPG)
Figure 3.1: Add Patients 
![PatientList](https://user-images.githubusercontent.com/75902424/151087350-984e9fce-c18d-4470-8993-9e6dd973019e.JPG)
Figure 3.2: Patients List

4. Human Resources: In human resources the hospital could add nurses, pharmacists, receotionists. Along with, the hospital could see the lists of lists and hostory. 

![AddNurse](https://user-images.githubusercontent.com/75902424/151087685-9c0f6298-f97d-488c-9848-f2d709825b9e.JPG)
Figure 4.1: Add Nurse
![NurseList](https://user-images.githubusercontent.com/75902424/151087700-612b9121-b22e-47e6-8cd2-eda43e76f984.JPG)
Figure 4.2: Nusres List
![AddPharmacist](https://user-images.githubusercontent.com/75902424/151087715-15f22f98-f177-4936-b9d1-1e192aeafe1e.JPG)
Figure 4.3: Add Pharmacist
![PharmacistList](https://user-images.githubusercontent.com/75902424/151087741-fe099d7b-3b22-4457-bd61-5acdd59e0888.JPG)
Figure 4.4: Pharmacist List
![addReceptionist](https://user-images.githubusercontent.com/75902424/151087784-f67e6cd7-e216-4e94-9b79-417b4cc3106f.JPG)
Figure 4.5: Add Receptionist 
![ReceptionistList](https://user-images.githubusercontent.com/75902424/151087802-0d2658a4-dacb-47b4-b00a-b3fb28880f55.JPG)
Figure 4.6: Receptionist List

5. Schedules: The management of hospital could maintain doctors schedule list, and day off schedule. 

![ScheduleList](https://user-images.githubusercontent.com/75902424/151088129-0c5a698c-2682-488c-b86c-ab875cf11db8.JPG)
Figure 5.1: Schedule List
![DayOffSchedule](https://user-images.githubusercontent.com/75902424/151088162-d0efd47c-1bc1-4455-9fa9-66cfbad1b2d1.JPG)
Figure 5.2: Day Off Schedule

6. Appointments: Patients could make an appointment, the appointments list would be visible.

![AddAppointment](https://user-images.githubusercontent.com/75902424/151088607-7a2c7624-c308-4df8-a6fc-9a606eb05581.JPG)
Figure 6.1: Add Appointment

7. Services: The management of the hospital could be able to add services, and the services list would appear in the system. 

![AddService](https://user-images.githubusercontent.com/75902424/151088860-3ee76fb0-72ca-43f4-8af0-8540f54d449a.JPG)
Figure 7.1: Add Service
![ServiceList](https://user-images.githubusercontent.com/75902424/151088882-653f36f7-af15-46f2-9aa0-cdf45c292716.JPG)
Figure 7.2: Service List

8. Beds: The hospital could allocate beds for its patients. 

![AddBedAllotment](https://user-images.githubusercontent.com/75902424/151089052-9876ff12-a07e-46ea-bfdd-79b371d2ecaf.JPG)
Figure 8.1: Add Bed Allotment 
9. Financial: Financial is an important part of this Hospital Management System. This system would keep records of all of the payments history. 

![AddPaymentItem](https://user-images.githubusercontent.com/75902424/151089297-80d5ad46-f987-4cab-975f-8549f15a8a01.JPG)
Figure 9.1: Add Payment Item
![PaymentItemsList](https://user-images.githubusercontent.com/75902424/151089329-5e3633e9-9cc9-4136-9da5-e04dfcf6b517.JPG)
Figure 9.2: Payment Item List

![Challenges](https://user-images.githubusercontent.com/75902424/151089510-89723b84-c78f-428f-99cc-4f7531c5b83c.JPG)

The common challenges that we have faced:

1) Time limitations: the period was not enough for developing and creating a perfect system. 
2) Limited resource: lack of resources and tools to develop a strong system.
3) Lack of experience: the group members do not have experience in developing a system.
4) Team mates distance: the distance of our team members is far. Thus, the communication was hard and the time difference was long.
5) Lack of knowledge: as students we have limited view of hospital background and how they manage, add and use the IT system. 


References: https://www.diagrameditor.com/

            https://laravel.com/

