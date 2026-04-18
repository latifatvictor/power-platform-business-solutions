# Solution Design Process
## Logistics & Shipping Request Automation Solution

---

## 1. Problem Identification

Shipping and logistics requests in many organisations are often managed through unstructured processes such as emails, phone calls, or spreadsheets.

This leads to several challenges:

- lack of standardisation in request submission  
- delays in processing and approvals  
- poor visibility of request status  
- miscommunication between teams  
- difficulty tracking shipments and requests  
- limited auditability and reporting capability  

The need was to design a structured system that improves coordination, tracking, and efficiency.

---

## 2. Solution Goal

The objective was to build a Power Platform solution that:

- digitises shipping request submissions  
- standardises request data collection  
- automates request routing and notifications  
- improves tracking and visibility of requests  
- reduces manual coordination between teams  

---

## 3. Users and Stakeholders

### Primary users
- employees submitting shipping requests  

### Secondary users
- logistics or operations teams  
- warehouse staff  
- managers approving requests  
- administrators managing workflows  

The solution needed to support both request submission and operational handling.

---

## 4. Functional Requirements

The system was designed to support:

- submission of shipping requests  
- capturing shipment details (items, destination, priority)  
- approval workflow (if required)  
- assignment to logistics or operations teams  
- status tracking (pending, approved, in progress, completed)  
- automated notifications for updates  
- centralised storage of all requests  

---

## 5. Non-Functional Requirements

The solution also needed to ensure:

- ease of use for all users  
- reliability and consistency  
- scalability for increased request volume  
- secure handling of request data  
- maintainability for future improvements  

---

## 6. Platform Selection

The Microsoft Power Platform was selected due to:

- rapid development with Power Apps  
- workflow automation with Power Automate  
- seamless integration with Microsoft 365  
- structured data storage using SharePoint  

---

## 7. Solution Architecture

The solution consists of:

### Power Apps
Used to create the front-end application where users can:
- submit shipping requests  
- view request status  
- track progress  

### SharePoint Online
Used to store:
- shipping request data  
- item details  
- request status  
- assigned teams  
- timestamps  

### Power Automate
Used to:
- trigger approval workflows  
- notify logistics teams  
- send updates to requesters  
- track status changes  

---

## 8. Data Design

A SharePoint list was designed to capture request data.

### Suggested fields
- Request ID  
- Requester Name  
- Department  
- Item Description  
- Quantity  
- Destination  
- Priority Level  
- Requested Date  
- Status  
- Assigned Team  
- Approval Status  
- Completion Date  

This structure supports both operational tracking and reporting.

---

## 9. User Experience Design

The application was designed to be simple and efficient.

### Key design considerations
- structured form for request submission  
- dropdowns for standardised input  
- minimal required fields  
- clear status indicators  
- easy navigation between requests  

The goal was to reduce errors and improve usability.

---

## 10. Workflow Design

### Request Submission Flow
1. User submits shipping request in Power Apps  
2. Request is stored in SharePoint  
3. Workflow is triggered via Power Automate  

---

### Approval Flow (Optional)
1. Request is sent to manager for approval  
2. Manager approves or rejects  
3. Status is updated in SharePoint  

---

### Processing Flow
1. Approved request is assigned to logistics team  
2. Logistics team processes shipment  
3. Status is updated throughout the process  

---

### Completion Flow
1. Shipment is completed  
2. Completion date is recorded  
3. User is notified  

---

## 11. Security and Access Considerations

The solution includes:

- role-based access to requests  
- secure storage within Microsoft 365  
- restricted access for sensitive data  
- alignment with organisational governance policies  

---

## 12. Reporting and Visibility

The solution enables:

- tracking of all shipping requests  
- visibility into request status  
- identification of delays or bottlenecks  
- potential reporting through dashboards  

---

## 13. Business Value Delivered

This solution provides:

- improved coordination between teams  
- reduced manual communication  
- faster processing of requests  
- increased visibility and accountability  
- better tracking and reporting  

---

## 14. Scalability and Future Enhancements

The solution can be extended with:

- integration with inventory systems  
- automated shipment tracking  
- barcode or QR code scanning  
- reporting dashboards  
- SLA tracking and alerts  
- multi-location logistics support  

---

## 15. Key Skills Demonstrated

This solution demonstrates:

- Power Apps application development  
- Power Automate workflow design  
- SharePoint data modelling  
- business process optimisation  
- logistics workflow understanding  
- automation of operational processes  

---

## 16. Summary

The Logistics & Shipping Request Automation Solution transforms an unstructured and manual process into a structured, automated, and trackable system.

It demonstrates how Power Platform can be used to improve operational efficiency, enhance visibility, and support better coordination across teams.
