# Automated Employee Onboarding & Offboarding System

A ServiceNow application that automates the employee onboarding and offboarding lifecycle — from request submission to approvals, departmental task assignment, notifications, and closure — reducing manual effort across HR, IT, Security, and Facilities.

## 📌 Abstract

This project automates employee onboarding and offboarding using ServiceNow's **Service Catalog**, **Flow Designer**, a custom **Employee Lifecycle** table, approvals, notifications, **SLA tracking**, and **Access Control Lists (ACLs)**. The solution reduces manual effort, improves data integrity, ensures secure access, and provides complete lifecycle tracking from request submission to closure.

## 🎯 Objectives

- Automate request submission and manager approvals
- Automatically assign tasks to relevant departments (HR, IT, Security, Facilities)
- Send notifications at each stage of the process
- Track SLAs for timely completion
- Maintain secure, role-based access to records

## 🛠️ Tech Stack

- **Platform:** ServiceNow (PDI)
- **Modules:** Flow Designer, Service Catalog, Custom Tables, UI Policies, ACLs, Notifications, SLA Configuration

## 🏗️ System Architecture

```
Employee → Service Catalog → Employee Lifecycle Table → Flow Designer
→ Manager Approval → Department Tasks → Notifications → Closure
```

## ⚙️ Implementation Details

- **Employee Lifecycle** custom table created to store and track onboarding/offboarding requests
- **Onboard/Offboard Catalog Item** built with variables:
  - Employee ID
  - Department
  - Manager
  - Joining Date
  - Exit Date
  - Assets
- **Flow Designer** configured for automatic approvals and task creation
- **Role-based ACLs** configured to secure records
- **Email notifications** and **SLA policies** configured for timely tracking

## ✅ Testing

- **Unit Testing** – verified each module independently
- **Integration Testing** – confirmed Flow Designer, approvals, and notifications work together
- **User Acceptance Testing (UAT)** – validated the end-to-end onboarding lifecycle
- **QA Testing** – verified request creation, task assignment, notifications, and closure

## 📊 Results

- Reduced manual intervention across departments
- Improved transparency and secure access control
- Automated departmental coordination
- Faster approvals and consistent lifecycle tracking

## 🔮 Future Scope

- Active Directory integration
- HRMS integration
- Integration Hub connectivity
- Reporting dashboards
- Mobile approvals

## 📄 Documentation

- **Functional Overview** – documents the request lifecycle and user roles
- **Technical Blueprint** – documents Flow Designer logic, variable mapping, and ACL implementation
- **Setup Manual** – steps to recreate the solution in a new ServiceNow instance
- **Troubleshooting** – performed using Flow Execution Details and Email Logs

## 👤 Author

**Harsha Chenna**
GitHub: [@chennaharsha2-ui](https://github.com/chennaharsha2-ui)

## 📚 References

1. ServiceNow Documentation
2. Flow Designer Documentation
3. Service Catalog Documentation
4. SkillWallet Project Guide
