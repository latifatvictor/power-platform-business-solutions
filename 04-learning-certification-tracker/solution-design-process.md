# Solution Design Process
## IT Learning & Certification Tracking Platform

---

## 1. Problem Identification

In many organisations, tracking employee learning progress and certifications is often handled manually using spreadsheets or informal methods.

This leads to several challenges:

- lack of visibility into employee development  
- difficulty tracking certification progress  
- inconsistent data across teams  
- missed renewal or expiry of certifications  
- limited insight for managers on team capability  

This creates inefficiencies and limits the ability to plan and support workforce development.

---

## 2. Solution Goal

The goal was to design a Power Platform solution that:

- centralises tracking of learning and certifications  
- provides visibility into employee progress  
- supports managers in monitoring team development  
- improves tracking of certification status and expiry  
- reduces reliance on manual spreadsheets  

---

## 3. Users and Stakeholders

### Primary users
- employees tracking their learning progress  

### Secondary users
- team managers reviewing development  
- IT leadership tracking capability  
- administrators maintaining the platform  

The solution needed to support both individual and organisational perspectives.

---

## 4. Functional Requirements

The system was designed to support:

- recording of certifications and courses  
- tracking certification status (in progress, completed, expired)  
- capturing certification expiry dates  
- viewing individual learning progress  
- manager visibility into team development  
- updating and maintaining records  
- centralised storage of learning data  

---

## 5. Non-Functional Requirements

The solution also needed to ensure:

- ease of use for all users  
- scalability for growing teams  
- secure handling of employee data  
- maintainability for updates and enhancements  
- reliability and consistency  

---

## 6. Platform Selection

The Microsoft Power Platform was selected due to:

- low-code application development with Power Apps  
- automation and notifications with Power Automate  
- integration with Microsoft 365  
- SharePoint as a structured data source  

---

## 7. Solution Architecture

The solution consists of:

### Power Apps
Used to create the front-end application where users can:
- add and update certifications  
- view their learning records  
- track progress  

### SharePoint Online
Used to store:
- certification records  
- user information  
- status and expiry data  

### Power Automate
Used to:
- send reminders for certification expiry  
- notify users or managers of updates  
- automate status changes where required  

---

## 8. Data Design

A SharePoint list was used to store certification data.

### Suggested fields
- Employee Name  
- Employee Email  
- Department  
- Certification Name  
- Certification Provider  
- Status (In Progress / Completed / Expired)  
- Start Date  
- Completion Date  
- Expiry Date  
- Notes  

This structure supports both tracking and reporting.

---

## 9. User Experience Design

The application was designed to be simple and intuitive.

### Key design considerations
- easy data entry for certifications  
- clear status indicators  
- filtering and searching capabilities  
- clean layout for viewing records  
- minimal complexity for users  

The goal was to encourage adoption and regular updates.

---

## 10. Workflow Design

### Record Creation Flow
1. User adds a certification record  
2. Record is stored in SharePoint  
3. Status is set (e.g. in progress or completed)  

---

### Update Flow
1. User updates certification progress  
2. Changes are saved to SharePoint  
3. Status is updated accordingly  

---

### Reminder Flow
1. Power Automate checks expiry dates  
2. Reminder notifications are sent  
3. Users are prompted to renew certifications  

---

## 11. Security and Access Considerations

The solution includes:

- controlled access to user records  
- secure storage within Microsoft 365  
- role-based visibility for managers  
- alignment with organisational data policies  

---

## 12. Reporting and Visibility

The solution enables:

- visibility into individual learning progress  
- tracking of certification completion  
- identification of expiring certifications  
- potential reporting through dashboards  

---

## 13. Business Value Delivered

This solution provides:

- improved visibility of employee development  
- better tracking of certifications  
- reduced manual administration  
- proactive management of certification expiry  
- support for workforce planning  

---

## 14. Scalability and Future Enhancements

The solution can be extended with:

- integration with learning platforms  
- automated certification validation  
- reporting dashboards using Power BI  
- role-based skill tracking  
- learning recommendations  
- integration with HR systems  

---

## 15. Key Skills Demonstrated

This solution demonstrates:

- Power Apps application design  
- Power Automate workflow automation  
- SharePoint data modelling  
- data tracking and reporting  
- user experience design  
- business process improvement  

---

## 16. Summary

The IT Learning & Certification Tracking Platform transforms a manual and fragmented process into a structured and efficient system.

It demonstrates how Power Platform can be used to support employee development, improve visibility, and enhance organisational capability.
