# Solution Design Process
## Smart Parking Allocation & Management System

---

## 1. Problem Identification

In many organisations, parking space allocation is often managed manually or informally, leading to inefficiencies such as:

- lack of visibility into parking availability  
- disputes over parking allocation  
- underutilisation or overbooking of spaces  
- reliance on emails or spreadsheets  
- difficulty tracking usage patterns  

This creates operational challenges and a poor user experience.

---

## 2. Solution Goal

The goal was to design a Power Platform solution that:

- digitises parking space requests  
- provides visibility into available parking slots  
- automates allocation and approval processes  
- improves fairness and efficiency in parking usage  
- reduces manual coordination  

---

## 3. Users and Stakeholders

### Primary users
- employees requesting parking spaces  

### Secondary users
- facilities or workplace management teams  
- administrators managing parking allocation  
- security teams (optional visibility)  

The solution needed to be easy for users while providing control to administrators.

---

## 4. Functional Requirements

The system was designed to support:

- parking space request submission  
- viewing available parking slots  
- booking for specific dates  
- approval workflow (if required)  
- tracking active bookings  
- cancellation or modification of bookings  
- centralised record of parking usage  

---

## 5. Non-Functional Requirements

The solution also needed to ensure:

- ease of use  
- real-time updates on availability  
- scalability for multiple users  
- secure handling of booking data  
- maintainability and flexibility  

---

## 6. Platform Selection

The Microsoft Power Platform was selected because it provides:

- low-code development with Power Apps  
- workflow automation with Power Automate  
- seamless integration with Microsoft 365  
- SharePoint as a structured data source  

---

## 7. Solution Architecture

The solution consists of:

### Power Apps
Used to build the front-end application where users can:
- request parking spaces  
- view availability  
- manage bookings  

### SharePoint Online
Used to store:
- parking space inventory  
- booking records  
- user information  
- booking dates and status  

### Power Automate
Used to:
- trigger approval workflows  
- send booking confirmations  
- notify users of changes  

---

## 8. Data Design

Two SharePoint lists can be used:

### Parking Inventory List
- Parking Slot ID  
- Location  
- Availability Status  

### Booking List
- User Name  
- User Email  
- Parking Slot ID  
- Booking Date  
- Status (Booked / Cancelled)  
- Created Date  

This structure supports both booking and availability tracking.

---

## 9. User Experience Design

The interface was designed to be simple and intuitive.

### Key design considerations
- clear display of available and booked slots  
- easy date selection  
- minimal steps to complete booking  
- ability to view and manage existing bookings  
- clear feedback messages  

The goal was to ensure quick and efficient booking.

---

## 10. Workflow Design

### Booking Flow
1. User selects a date  
2. Available parking slots are displayed  
3. User selects a slot and submits request  
4. Booking is stored in SharePoint  
5. Confirmation notification is sent  

---

### Approval Flow (Optional)
1. Request is sent to administrator  
2. Approval or rejection is recorded  
3. Status is updated  

---

### Cancellation Flow
1. User cancels booking  
2. Slot becomes available again  
3. System updates booking status  

---

## 11. Security and Access Considerations

The solution includes:

- controlled access to authorised users  
- secure data storage within Microsoft 365  
- role-based access for administrators  
- alignment with organisational governance policies  

---

## 12. Reporting and Visibility

The solution enables:

- real-time view of parking availability  
- tracking of bookings  
- visibility of usage patterns  
- potential reporting through dashboards  

---

## 13. Business Value Delivered

This solution provides:

- improved utilisation of parking spaces  
- reduced conflicts and manual coordination  
- increased transparency in allocation  
- better user experience  
- structured and auditable records  

---

## 14. Scalability and Future Enhancements

The solution can be extended with:

- integration with access control systems  
- automated allocation based on priority rules  
- QR code or badge-based parking access  
- mobile-friendly enhancements  
- reporting dashboards  
- multi-location support  

---

## 15. Key Skills Demonstrated

This solution demonstrates:

- Power Apps application design  
- Power Automate workflow automation  
- SharePoint data modelling  
- resource allocation logic  
- user experience optimisation  
- business process digitisation  

---

## 16. Summary

The Smart Parking Allocation & Management System transforms a manual and inefficient process into a structured, automated, and user-friendly solution.

It demonstrates how Power Platform can be used to optimise resource allocation, improve efficiency, and enhance user experience in workplace environments.
