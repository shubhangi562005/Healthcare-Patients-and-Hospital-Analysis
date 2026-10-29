# Healthcare Patients & Hospital Analytics

## Project Overview
Healthcare Patients & Hospital Analytics is a Power BI project designed to analyze patient information, appointment records, and hospital billing data. The project uses three CSV datasets to create interactive dashboards and understand healthcare operations.

## Objectives
- Analyze patient demographics and age groups.
- Understand patient distribution by gender and insurance provider.
- Track appointments by status, reason, and doctor.
- Analyze revenue, paid amounts, and pending payments.
- Present healthcare information through interactive Power BI dashboards.

## Dataset Description

### 1. patients.csv
Contains patient demographic, registration, and insurance information.

**Columns:** `patient_id`, `first_name`, `last_name`, `gender`, `date_of_birth`, `contact_number`, `address`, `registration_date`, `insurance_provider`, `insurance_number`, `email`

- Total Records: 50
- Total Columns: 11

### 2. appointments.csv
Contains patient appointment details, appointment dates, doctors, reasons for visits, and appointment statuses.

**Columns:** `appointment_id`, `patient_id`, `doctor_id`, `appointment_date`, `appointment_time`, `reason_for_visit`, `status`

- Total Records: 200
- Total Columns: 7

### 3. billing.csv
Contains billing information, treatment IDs, payment methods, billing amounts, and payment statuses.

**Columns:** `bill_id`, `patient_id`, `treatment_id`, `bill_date`, `amount`, `payment_method`, `payment_status`

- Total Records: 200
- Total Columns: 7

## Tools & Technologies
- Python is not used for the dashboard itself; the report is built in Microsoft Power BI.
- Microsoft Power BI Desktop
- Power Query
- DAX
- CSV datasets

## Data Preparation
- Imported all three CSV files into Power BI.
- Created relationships using the patient ID.
- Prepared date fields for analysis.
- Created measures for patient counts, appointment counts, and billing amounts.
- Created patient age and age-group analysis.
- Added slicers to make the dashboards interactive.

## Dashboard Pages

### 1. Hospital Overview
**Key Cards**
- Total Patients
- Total Appointments
- Total Revenue
- Paid Amount
- Pending Amount

**Charts**
- Appointments by Status
- Revenue Trend
- Payment Status by Revenue

### 2. Healthcare Patients Analysis
**Key Cards**
- Total Patients
- Male Patients
- Female Patients
- Average Patient Age

**Charts**
- Patients by Insurance Provider
- Patient Age Distribution
- Patient Registration Trend

**Slicers**
- Gender
- Insurance Provider

### 3. Healthcare Appointment Analysis
**Key Cards**
- Total Appointments
- Completed Appointments
- Cancelled Appointments
- No-show Appointments
- Scheduled Appointments

**Charts**
- Appointment by Reason
- Appointment Trend
- Total Appointments by Doctor

**Slicers**
- Status
- Reason to Visit

## Key Findings
- Total Patients: 50
- Male Patients: 31
- Female Patients: 19
- Total Appointments: 200
- Completed Appointments: 46
- Cancelled Appointments: 51
- No-show Appointments: 52
- Scheduled Appointments: 51

The dashboards also present insurance-provider distribution, patient age groups, registration trends, billing revenue, and payment status.

## Conclusion
This project demonstrates how Power BI can transform patient, appointment, and billing data into interactive dashboards. It helps users understand patient demographics, monitor appointment activity, and analyze hospital billing and payments.

## Data Privacy
The patient dataset contains contact numbers, email addresses, addresses, and insurance numbers. These fields should be removed or anonymized before publishing the datasets publicly on GitHub.

