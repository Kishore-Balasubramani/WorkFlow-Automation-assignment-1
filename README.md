# WorkFlow Automation Assignment 1

## Overview

This repository contains BPMN 2.0 models for three business process scenarios created using **Camunda Modeler**. Each model follows the required BPMN elements and represents the complete process flow with appropriate tasks, decision points, alternative paths, and end events.

## Scenarios

### 1. Employee Leave Approval

This process models how an employee's leave request is handled through the company's HR system. The system checks the employee's leave balance before sending the request to the manager. Based on the available balance and the manager's decision, the process follows the appropriate approval, rejection, or insufficient-balance path and sends the corresponding notification.

### 2. Online Purchase Order Processing

This process models the handling of an online customer order. The system first checks product availability and then processes payment if the product is available. Depending on product availability and payment status, the process either ends with a notification or continues through order confirmation, product preparation, shipping, and shipping confirmation.

### 3. IT Service Request

This process models how an employee's IT support request is handled. The help desk registers the request and determines its severity. Low-severity issues are assigned to a support technician, while high-severity issues are assigned to a senior technician. After investigation, the issue is either resolved internally or escalated to an external service provider. Once resolved, the request status is updated and the employee receives a resolution notification.

## BPMN Elements Used

The models use the required basic BPMN building blocks, including:

* Start Events
* Tasks
* User Tasks
* Send Tasks
* Exclusive Gateways
* Sequence Flows
* End Events

## Repository Files

* `scenario1_employee_leave_approval.bpmn`
* `scenario2_online_purchase_order.bpmn`
* `scenario3_it_service_request.bpmn`
* `README.md`

## Verification

All BPMN models were created and organized for evaluation using Camunda Modeler. Before submission, the diagrams should be checked to ensure that all elements are connected correctly, gateway paths are clearly labeled, and the processes are readable and logically complete.

## Author

**Kishore B.**
