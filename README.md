WorkFlow Automation Assignment Submission
Scenario 1 — Employee Leave Approval
The employee submits a leave request. The HR system checks the leave balance using an exclusive gateway. With sufficient balance, the request goes to the manager. A second exclusive gateway routes the request to approval/update/notification or rejection notification. With insufficient balance, the system sends an insufficient-balance notification. Each outcome has its own end event.
Scenario 2 — Online Purchase Order Processing
The customer places an order and the system checks availability. An exclusive gateway separates the out-of-stock path from the available path. Available orders proceed to payment; another exclusive gateway separates payment failure from successful payment. Successful orders are confirmed, prepared, shipped, and followed by a shipping confirmation before the end event.
Scenario 3 — IT Service Request
The employee submits a support request, the help desk registers it and checks severity. An exclusive gateway routes low-severity cases to a support technician and high-severity cases to a senior technician. After investigation, another exclusive gateway determines whether the issue can be resolved internally. Internal issues are fixed; unresolved issues are escalated to an external provider. The request status is updated and the employee receives a resolution notification before the process ends.
Files
`scenario1_employee_leave_approval.bpmn`
`scenario2_online_purchase_order.bpmn`
`scenario3_it_service_request.bpmn`
These are BPMN 2.0 XML models and can be opened in BPMN-compatible modeling tools such as Camunda Modeler or other BPMN 2.0 editors. Before submission, open each file in your required tool and visually verify labels, connector routing, and readability.
