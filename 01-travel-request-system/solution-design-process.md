# Solution Design Process
## International Travel Request & Approval System

## 1. Problem Identification

International travel requests are often handled through manual processes such as emails, spreadsheets, or disconnected forms. These approaches can create several problems:

- delays in approval cycles
- lack of visibility into request status
- inconsistent data capture
- difficulty tracking approvals and decisions
- limited auditability for compliance and reporting

The goal of this solution was to design a structured, digital process that simplifies travel request submission, standardises approvals, and improves visibility for both requesters and stakeholders.

---

## 2. Solution Goal

The primary objective was to build a Power Platform solution that would:

- digitise travel request submission
- automate approval routing
- improve request tracking and transparency
- centralise travel request data
- reduce manual coordination
- support a more consistent and auditable process

---

## 3. Users and Stakeholders

The solution was designed with multiple user groups in mind:

### Primary users
- employees submitting travel requests

### Secondary users
- line managers approving requests
- finance or budget reviewers
- HR or travel coordinators
- administrators maintaining the solution

Each of these groups needed a simple and role-appropriate interaction with the system.

---

## 4. Functional Requirements

The core functional requirements identified for the system were:

- a user-friendly request submission form
- fields for destination, travel dates, purpose, and justification
- automated routing to relevant approvers
- approval and rejection capability
- request status updates for the requester
- a dashboard or tracking view for submitted requests
- centralised storage of request records
- audit trail of submission and approval decisions

---

## 5. Non-Functional Requirements

In addition to features, the solution also needed to support:

- ease of use
- secure access to request data
- scalability for more users and requests
- maintainability for future enhancements
- visibility and reporting capability
- low-code deployment within Microsoft 365 ecosystem

---

## 6. Platform Selection

The Microsoft Power Platform was selected because it provides:

- low-code app development with Power Apps
- workflow automation with Power Automate
- easy integration with Microsoft 365
- SharePoint as a practical data source
- fast iteration and rapid delivery

This made it ideal for building an internal business application quickly and effectively.

---

## 7. Solution Architecture

The solution was designed using the following components:

### Power Apps
Used to create the front-end application where users can:
- submit requests
- view request details
- track approval status

### SharePoint Online
Used as the data source to store:
- request details
- requester information
- approval status
- timestamps
- comments where applicable

### Power Automate
Used to automate:
- approval routing
- email notifications
- status updates
- approval outcomes

---

## 8. Data Design

A SharePoint list was used to store the request information.

### Suggested fields
- Request ID
- Requester Name
- Requester Email
- Department
- Destination Country
- Departure Date
- Return Date
- Purpose of Travel
- Estimated Cost
- Status
- Submitted Date
- Approver Comments
- Approval Date

This structure supports both operational use and future reporting.

---

## 9. User Experience Design

The interface was designed to be simple, clear, and easy to complete.

### Design decisions included:
- clean form layout with grouped fields
- minimal clicks for submission
- clear labels and required fields
- status visibility for users after submission
- approval screens designed for quick review and action

The goal was to reduce friction and make the process intuitive for non-technical users.

---

## 10. Workflow Design

The approval flow was designed to follow a logical sequence.

### Example workflow
1. User submits travel request in Power Apps
2. Request record is created in SharePoint
3. Power Automate triggers approval workflow
4. First approver receives notification
5. Decision is captured
6. If approved, request moves to next stage if needed
7. Final outcome is written back to SharePoint
8. User receives update by email

This design improves consistency and ensures requests are not lost in email chains.

---

## 11. Security and Access Considerations

The solution was designed with access control in mind.

### Considerations
- only authorised users should access or edit requests
- approvers should only review relevant submissions
- request data should be stored securely within Microsoft 365
- permissions should align with least-privilege principles

These considerations support governance and appropriate handling of business information.

---

## 12. Reporting and Visibility

A key improvement over manual processes was visibility.

The solution supports:
- real-time request tracking
- clear approval status
- visibility for requesters and stakeholders
- centralised reporting capability using SharePoint data
- future integration into dashboards if required

---

## 13. Business Value Delivered

The solution was designed to create measurable operational value.

### Benefits
- reduced manual effort
- faster approval turnaround
- improved process transparency
- more structured data capture
- better auditability
- improved requester experience

This turns a fragmented process into a repeatable and governed workflow.

---

## 14. Scalability and Future Enhancements

The design allows for future expansion.

### Potential enhancements
- multi-level approvals by cost threshold
- attachment upload for supporting documents
- integration with finance workflows
- dashboard reporting using Power BI
- role-based approval rules
- mobile-friendly optimisation
- automated reminders for pending approvals

---

## 15. Key Skills Demonstrated

This solution demonstrates capability in:

- Power Apps solution design
- Power Automate workflow design
- SharePoint data modelling
- business process analysis
- user experience design
- workflow optimisation
- digital transformation thinking

---

## 16. Summary

This solution was designed to modernise and streamline international travel request management by replacing manual and disconnected processes with a structured Power Platform application.

It demonstrates how low-code tools can be used to build practical, scalable, and business-focused solutions that improve efficiency, visibility, and governance.
