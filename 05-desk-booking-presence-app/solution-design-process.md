# Solution Design Process
## Hybrid Workplace Desk Booking & Presence Management App

---

## 1. Problem Identification

With the shift to hybrid working models, organisations face challenges in managing office space efficiently.

Common issues include:

- lack of visibility into who is in the office  
- inefficient desk allocation  
- overcrowding or underutilisation of office space  
- difficulty coordinating team presence  
- reliance on informal booking methods (emails, spreadsheets)  

This creates inefficiencies and reduces the effectiveness of hybrid working.

---

## 2. Solution Goal

The goal was to design a Power Platform solution that:

- enables employees to book desks in advance  
- provides visibility into office presence  
- improves utilisation of workspace resources  
- supports planning for hybrid working  
- reduces manual coordination  

---

## 3. Users and Stakeholders

### Primary users
- employees booking desks  
- team members planning office attendance  

### Secondary users
- facilities or workplace management teams  
- managers overseeing team presence  
- administrators managing desk allocation  

The solution needed to be intuitive and accessible for all users.

---

## 4. Functional Requirements

The system was designed to support:

- desk booking by date and location  
- viewing available desks  
- tracking office presence  
- booking confirmation and updates  
- cancellation or modification of bookings  
- visibility of who is in the office  
- optional team-based presence view  

---

## 5. Non-Functional Requirements

The solution also needed to ensure:

- ease of use and accessibility  
- real-time availability updates  
- scalability for larger teams  
- secure access to booking data  
- maintainability and flexibility  

---

## 6. Platform Selection

The Microsoft Power Platform was selected because it allows:

- rapid app development with Power Apps  
- automation with Power Automate  
- integration with Microsoft 365 tools  
- use of SharePoint as a flexible data source  

---

## 7. Solution Architecture

The solution is built using:

### Power Apps
Used to create the user interface for:
- desk booking  
- viewing availability  
- tracking presence  

### SharePoint Online
Used to store:
- desk inventory  
- booking records  
- user details  
- booking dates and times  

### Power Automate
Used to:
- send booking confirmations  
- notify users of changes  
- manage reminders or cancellations  

---

## 8. Data Design

A structured SharePoint list was created to manage bookings.

### Suggested fields
- User Name  
- User Email  
- Desk ID  
- Location  
- Booking Date  
- Booking Time (optional)  
- Status (Booked / Cancelled)  
- Created Date  
- Notes (optional)  

An additional list can be used to manage desk inventory.

---

## 9. User Experience Design

The app was designed to be simple, clear, and responsive.

### Key design considerations
- calendar-based booking interface  
- visual display of available and booked desks  
- easy selection of date and location  
- minimal clicks to complete booking  
- clear confirmation messages  

The goal was to provide a seamless experience for users.

---

## 10. Workflow Design

### Desk Booking Flow
1. User selects date and location  
2. Available desks are displayed  
3. User selects a desk and submits booking  
4. Booking is stored in SharePoint  
5. Confirmation notification is sent  

---

### Cancellation Flow
1. User views existing booking  
2. User cancels booking  
3. Record is updated in SharePoint  
4. Availability is refreshed  

---

### Presence Tracking Flow
1. Booked users are displayed for selected date  
2. Managers or teams can view who is in the office  

---

## 11. Security and Access Considerations

The solution includes:

- controlled access for authorised users  
- secure storage within Microsoft 365  
- visibility limited to relevant users  
- alignment with organisational data policies  

---

## 12. Reporting and Visibility

The solution enables:

- real-time view of desk bookings  
- visibility into office occupancy  
- tracking usage patterns  
- potential reporting through Power BI  

---

## 13. Business Value Delivered

This solution provides:

- improved workspace utilisation  
- better planning for hybrid teams  
- reduced overcrowding or unused desks  
- increased visibility of employee presence  
- more efficient use of office resources  

---

## 14. Scalability and Future Enhancements

The solution can be extended with:

- floor plan visualisation  
- integration with Teams or Outlook  
- QR code desk check-in  
- automated no-show detection  
- advanced reporting dashboards  
- multi-location support  

---

## 15. Key Skills Demonstrated

This solution demonstrates:

- Power Apps interface design  
- Power Automate workflow automation  
- SharePoint data modelling  
- modern workplace solution design  
- user experience optimisation  
- business process transformation  

---

## 16. Summary

The Hybrid Desk Booking & Presence App addresses a key challenge in modern workplaces by providing a structured, efficient, and user-friendly way to manage desk bookings and track office presence.

It demonstrates how Power Platform solutions can support hybrid working strategies and improve operational efficiency.
