# Solution Design Process
## Digital Visitor Management & Check-in System

---

## 1. Problem Identification

Traditional visitor management processes are often manual and inefficient, typically relying on paper logs or informal tracking methods.

This creates several challenges:

- lack of real-time visibility of visitors on-site  
- security risks due to incomplete or inaccurate records  
- difficulty tracking visitor history  
- no structured check-in and check-out process  
- limited accountability and audit capability  

The need was to design a digital solution that improves security, tracking, and overall visitor experience.

---

## 2. Solution Goal

The objective was to design a Power Platform solution that:

- digitises visitor check-in and check-out processes  
- improves security and visibility of visitors on-site  
- provides a structured and auditable visitor log  
- enhances the overall visitor experience  
- reduces manual administration  

---

## 3. Users and Stakeholders

### Primary users
- reception staff or front desk administrators  
- visitors checking in  

### Secondary users
- employees hosting visitors  
- security teams  
- administrators managing visitor data  

The solution needed to be simple for reception use while providing visibility to stakeholders.

---

## 4. Functional Requirements

The system was designed to support:

- visitor registration and check-in  
- capturing visitor details (name, company, purpose)  
- host selection or assignment  
- automated host notification  
- visitor badge or confirmation (optional)  
- check-out process  
- tracking active visitors on-site  
- maintaining historical visitor records  

---

## 5. Non-Functional Requirements

The solution also needed to ensure:

- ease of use for reception staff  
- secure storage of visitor data  
- scalability for multiple locations or offices  
- fast performance for real-time usage  
- maintainability for future enhancements  

---

## 6. Platform Selection

The Microsoft Power Platform was selected due to:

- rapid development capability with Power Apps  
- automation via Power Automate  
- integration with Microsoft 365 ecosystem  
- use of SharePoint for structured data storage  

---

## 7. Solution Architecture

The solution consists of:

### Power Apps
Used to build the front-end application for:
- visitor check-in  
- visitor check-out  
- viewing current visitors  

### SharePoint Online
Used to store:
- visitor records  
- check-in and check-out timestamps  
- host information  
- visit purpose  

### Power Automate
Used to:
- notify hosts when visitors arrive  
- send confirmation emails  
- optionally trigger alerts for overdue visitors  

---

## 8. Data Design

A SharePoint list was designed to capture visitor information.

### Suggested fields
- Visitor Name  
- Company Name  
- Contact Details  
- Host Name  
- Department  
- Purpose of Visit  
- Check-in Time  
- Check-out Time  
- Status (Checked-in / Checked-out)  
- Badge ID (optional)  

This structure ensures accurate tracking and supports reporting.

---

## 9. User Experience Design

The interface was designed to be simple and quick for front desk use.

### Key design considerations
- minimal data entry fields  
- clear check-in and check-out buttons  
- searchable visitor list  
- visual indicators for active visitors  
- clean and intuitive layout  

The goal was to allow fast processing with minimal training.

---

## 10. Workflow Design

### Visitor Check-in Flow
1. Visitor arrives at reception  
2. Reception staff enters visitor details in Power Apps  
3. Record is stored in SharePoint  
4. Power Automate sends notification to host  
5. Visitor status is set to "Checked-in"  

---

### Visitor Check-out Flow
1. Visitor leaves premises  
2. Reception staff updates record  
3. Check-out time is recorded  
4. Status is updated to "Checked-out"  

---

### Optional Enhancements
- automatic reminders for visitors not checked out  
- badge printing integration  
- pre-registration workflow  

---

## 11. Security and Access Considerations

The solution includes:

- restricted access to authorised staff  
- secure data storage within Microsoft 365  
- controlled visibility of visitor records  
- alignment with data protection principles  

This ensures proper handling of visitor information.

---

## 12. Reporting and Visibility

The system enables:

- real-time view of visitors currently on-site  
- historical tracking of visitor records  
- improved security visibility  
- potential reporting using Power BI  

---

## 13. Business Value Delivered

This solution improves operations by:

- eliminating manual visitor logs  
- improving security and compliance  
- enhancing visibility of on-site visitors  
- reducing administrative workload  
- providing structured and auditable records  

---

## 14. Scalability and Future Enhancements

The design allows future expansion such as:

- QR code or self-check-in kiosks  
- integration with security systems  
- multi-location support  
- visitor pre-registration forms  
- automated visitor badge generation  
- dashboard reporting and analytics  

---

## 15. Key Skills Demonstrated

This solution demonstrates:

- Power Apps application design  
- Power Automate workflow automation  
- SharePoint data modelling  
- user experience design  
- business process digitisation  
- security-aware solution design  

---

## 16. Summary

The Digital Visitor Management System transforms a manual and inefficient process into a structured, secure, and user-friendly solution.

It demonstrates how Power Platform tools can be used to improve operational efficiency, enhance security, and provide better visibility across business processes.
