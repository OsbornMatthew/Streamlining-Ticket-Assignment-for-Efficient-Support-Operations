# Streamlining Ticket Assignment for Efficient Support Operations

This project aims to automate the ticket assignment process in ServiceNow for ABC Corporation's support team. By leveraging ServiceNow’s Flow Designer, ACLs, and custom tables, the solution reduces manual intervention, minimizes delays in support resolution, and improves overall efficiency.

---

## 🚀 Objective

To implement an automated system in ServiceNow that:
- Automatically assigns tickets to the appropriate support team based on the issue type.
- Ensures secure and structured access to ticket data using roles and ACLs.
- Enhances response time and resource utilization in IT support operations.

---

## 🔧 Features

- Creation of users, groups, and roles in ServiceNow
- Custom table setup (`Operations Related`) for ticket management
- Predefined issue categories:  
  - Unable to login  
  - 404 error  
  - Regarding Certificates  
  - Regarding User Expired
- Flow Designer-based automation for ticket assignment
- Role-based access control using ACL
- Dashboard to visualize ticket distribution and team performance

---

## 📂 Project Structure

- `/docs` – Documentation (Design, Planning, Performance Testing)
- `/screenshots` – Screenshots for each phase of the project
- `/flows` – JSON or visual exports of Flow Designer logic (if exported)
- `README.md` – This file

---

## 🧪 Testing & Validation

- Tested using sample ticket entries with varied issue types
- Verified correct flow execution and ticket routing
- Role elevation tested using `security_admin` to apply ACLs
- Performance evaluated by number of auto-assigned tickets and dashboard analytics

---

## 🛠 Tools & Technologies

- **Platform:** ServiceNow
- **Modules Used:** Flow Designer, Form Design, ACL, Security Admin
- **Roles:** Platform_Role, Certificate_Role, Admin
- **Tables:** Custom table – `Operations Related`

---

## 📊 Performance Metrics

- Average assignment time reduced significantly
- Tickets auto-assigned to correct teams with no manual routing
- User roles and permissions enforced strictly through ACLs

---

## 📅 Timeline Overview

| Phase | Description |
|-------|-------------|
| Ideation | Problem Identification and Goal Setting |
| Requirement Analysis | Finalized user, role, and workflow requirements |
| Planning | Sprints structured into 3-day cycles |
| Design | Implemented tables, roles, ACLs, and Flow Designer logic |
| Testing | Verified flows, access control, and assignment accuracy |

---

## 🤝 Contributors

- Team ID : LTVIP2025TMID29823
 
Team Size : 4

Team Leader : Osborn Matthew A I

Team member : Sidesh A S

Team member : Retheesh R

Team member : Regin Kumar
