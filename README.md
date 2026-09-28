# Workflow Automation Assignment 2

## BPMN Process Modeling

This repository contains BPMN 2.0 process models for three business process scenarios created using **Camunda Modeler**.

## Scenarios

### Scenario 1: Hotel Room Reservation

This BPMN model represents the process of booking a hotel room through an online reservation system.

**Process Flow:**
1. Guest submits a room booking request with check-in and check-out dates.
2. The reservation system checks room availability.
3. If rooms are unavailable, the guest is notified and the process ends.
4. If rooms are available, the system requests advance/deposit payment.
5. If payment is successful, the booking is confirmed and a booking reference number is generated.
6. If payment fails, the guest is notified about the payment failure and the process ends.
7. The system sends a booking confirmation email with reservation details.
8. The process ends.

**BPMN Elements Used:**
- Start Event
- User/Service Tasks
- Exclusive Gateways
- Multiple Sequence Flows
- End Events

### Scenario 2: Loan Application Processing

This BPMN model represents the process of handling a personal loan application submitted to a bank.

**Process Flow:**
1. Customer submits a loan application.
2. The bank verifies the applicant's documents and credit score.
3. If documents are incomplete or invalid, the application is rejected and the customer is notified.
4. If documents are valid, the system checks eligibility based on credit score and income.
5. If the applicant is not eligible, the loan officer sends a rejection notification.
6. If eligible, the application is forwarded to the loan officer for final approval.
7. If approved, the system disburses the loan amount and sends an approval notification.
8. If rejected by the loan officer, the system sends a rejection notification.
9. The process ends after the appropriate notification.

**BPMN Elements Used:**
- Start Event
- Multiple Tasks
- Exclusive Gateways
- Alternative Paths
- End Events

### Scenario 3: Job Applicant Recruitment Process

This BPMN model represents the recruitment process followed after a candidate submits a job application.

**Process Flow:**
1. Candidate submits a job application online.
2. The HR system screens the application against minimum eligibility criteria.
3. If the candidate is not eligible, a rejection notification is sent and the process ends.
4. If eligible, HR schedules a technical interview.
5. The technical panel evaluates the candidate's performance.
6. If the candidate fails the technical interview, HR sends a rejection notification.
7. If the candidate passes, an HR/managerial round is scheduled.
8. If the candidate is rejected in the HR round, a rejection notification is sent.
9. If selected, the system generates and sends an offer letter.
10. The process ends after the offer letter is sent.

**BPMN Elements Used:**
- Start Event
- Tasks
- Exclusive Gateways
- Alternative Paths
- End Events

## Repository Structure

```text
Workflow-Automation-assignment-2/
│
├── README.md
│
├── scenario1_hotel_room_reservation.bpmn
├── scenario1_hotel_room_reservation.png
│
├── scenario2_loan_application_processing.bpmn
├── scenario2_loan_application_processing.png
│
├── scenario3_job_applicant_recruitment.bpmn
└── scenario3_job_applicant_recruitment.png
```

## Tools Used

- **Camunda Modeler**
- **BPMN 2.0**
- **GitHub**

## Objective

The objective of this assignment is to practice modeling real-world business workflows using BPMN 2.0 concepts such as events, tasks, exclusive gateways, sequence flows, and alternative process paths.
