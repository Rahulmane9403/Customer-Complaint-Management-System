# Customer-Complaint-Management-System (Salesforce Admin Project)
This project was built as part of Salesforce Admin practice using Trailhead and Developer Org.

## 🎯 Objective
Track customer complaints and resolve them using automated assignment and admin workflows.

## 📐 Data Model
- **Customer**: Name, Email, Phone, Address
- **Complaint**: Title, Description, Status, Priority, Assigned Agent, Complaint Type
- **Department**: Name, Manager
- **Agent**: Related to Department

## 🔄 Automations
| Use Case                                   | Flow Type             |
|--------------------------------------------|------------------------|
| Auto-assign complaint to agent             | Record-Triggered Flow |
| Send email on complaint creation/resolved  | Record-Triggered Flow |
| Auto-close complaint with resolution date  | Scheduled Flow        |

## 🧪 Validations
- Resolution Date required if Status = Closed
- Status can't be "In Progress" without an Assigned Agent

## 📊 Reports & Dashboards
- Complaints by Status, Priority
- Department-wise and Agent-wise performance

## 🧾 Screenshots
[Project Implementation (PDF)](./CustomerComplaintManagementsystem.pdf)

## 📜 Trailhead Profile
[[Visit My Trailhead Profile](https://www.salesforce.com/trailblazer/rmane70)]
