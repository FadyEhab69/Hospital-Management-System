# Hospital-Management-System
This Entity-Relationship Diagram (ERD) represents a Hospital Management System with the following entities and relationships :

HOSPITAL: Includes attributes like ID (primary key), Name, and Address. A hospital has multiple doctors, workers, departments, and patients.
DOCTORS: Contains attributes such as ID (primary key), Name, and Specialties. Doctors are associated with a hospital and assigned to a department.
WORKERS: Has attributes like ID (primary key), Name, and Address. Workers are employed by a hospital to support its operations.
DEPARTMENT: Includes attributes such as ID (primary key) and Name. A hospital has one or more departments where doctors and workers are assigned.
PATIENTS: Contains attributes like ID (primary key), First_name, Last_name, and Phone_number. Patients are in section at a hospital and make payments for services.
PAYMENT: Includes attributes like ID (primary key), Name, Payment_method, and Amount. Payments are made by patients for medical services.
# Relationships:

A HOSPITAL has one or more DOCTORS.
A HOSPITAL has one or more WORKERS.
A HOSPITAL has one or more DEPARTMENTS.
A HOSPITAL has one or more PATIENTS who are in section.
A DOCTOR is assigned to a DEPARTMENT.
A PATIENT does PAYMENT for services received.
The ERD uses diamonds to represent relationships (e.g., "HAS," "In_Section," "Does_payment") and ovals for attributes, with primary keys underlined.
