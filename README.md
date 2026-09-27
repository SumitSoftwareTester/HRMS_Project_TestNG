# HRMS Automation Testing Project

![Java](https://img.shields.io/badge/Java-Programming-orange)
![Selenium](https://img.shields.io/badge/Selenium-WebDriver-green)
![TestNG](https://img.shields.io/badge/TestNG-Testing-red)
![Maven](https://img.shields.io/badge/Maven-Build-blue)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-black)
![Git](https://img.shields.io/badge/Git-Version_Control-orange)

## 📌 Project Overview

This project is a **Web Automation Testing Framework for an HRMS (Human Resource Management System)** application.

The framework is developed using **Java, Selenium WebDriver, TestNG, Maven, Jenkins, and Log4j**.

The objective of this project is to automate functional and regression test scenarios for an HRMS application and validate the expected behavior of different functionalities.

---

# 🏢 Application Under Test

**Application:** OrangeHRM  
**Version:** OrangeHRM 2.5

OrangeHRM is a Human Resource Management System that provides functionality for managing employees, leave, time and attendance, recruitment, benefits, user access, and other HR-related operations.

---

# 📋 Application Modules

The HRMS application includes the following major modules:

### Admin
- User Management
- User Groups
- Company Information
- Locations
- Organization Structure
- Job Specifications
- Pay Grades
- Employment Status
- Qualifications
- Skills
- Languages
- Memberships
- Nationality
- Email Notifications
- Project Information
- Data Import / Export
- Custom Fields

### PIM – Personal Information Management
- Employee List
- Add Employee
- Personal Details
- Contact Details
- Emergency Contacts
- Dependants
- Immigration
- Photograph
- Job Information
- Salary
- Tax Exemptions
- Direct Deposit
- Report-To
- Work Experience
- Education
- Skills
- Languages
- License
- Memberships
- Attachments
- Custom Information

### Leave Management
- Leave Summary
- Employee Leave Summary
- Personal Leave Summary
- Define Days Off
- Weekends
- Holidays
- Leave Types
- Assign Leave
- Apply Leave
- Leave List
- My Leave

### Time Management
- Timesheets
- Enter Timesheet
- Submit Timesheet
- Approve Timesheet
- Attendance
- Punch In / Punch Out
- Employee Reports
- My Reports
- Project Reports
- Work Shifts

### Benefits
- Health Savings Plan
- Payroll Schedule
- Pay Period

### Recruitment
- Job Vacancies
- Apply for Vacancy
- Applicants
- Reject Applicant
- Schedule Interview
- Offer Job
- Mark Offer Declined
- Seek Approval
- Event History

### ESS – Employee Self Service

Employee self-service functionality is available based on the permissions assigned to the employee.

---

# 🎯 Automation Testing Scope

The automation framework focuses on validating the functional behavior of selected HRMS functionalities.

The automation work includes areas such as:

- Login functionality
- Employee management
- Employee information
- Attendance-related functionality
- Leave management
- Payroll-related functionality
- Role-based access
- Functional validation
- Regression validation

> **Note:** The application contains multiple HRMS modules. The presence of a module in the application overview does not mean that every functionality within that module has been automated in this project.

---

# 🧪 Testing Types

The project includes the following testing approaches:

- Functional Testing
- Regression Testing
- UI Testing
- Integration Testing
- End-to-End Testing
- Positive Testing
- Negative Testing

---

# 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Java | Programming Language |
| Selenium WebDriver | Web UI Automation |
| TestNG | Test Execution and Test Management |
| Maven | Build and Dependency Management |
| Jenkins | Continuous Integration |
| Log4j | Logging |
| Git | Version Control |
| GitHub | Source Code Management |
| Eclipse | Development IDE |

---

# 🏗️ Automation Framework

The project uses a **Selenium WebDriver + Java + TestNG automation framework**.

The framework incorporates:

- Selenium WebDriver
- Java
- TestNG
- Maven
- TestNG Test Suites
- Data-Driven Testing
- Keyword-Driven Testing
- Hybrid Automation Approach
- Log4j Logging
- Jenkins Integration

---

# 🔄 Automation Execution Flow

```text
Test Scenario
      ↓
Test Case
      ↓
TestNG Test Class
      ↓
Selenium WebDriver
      ↓
HRMS Application
      ↓
Validation / Assertion
      ↓
TestNG Execution
      ↓
Logs & Test Results
---

# ▶️ How to Run the Project

1. Clone the repository.
2. Import the project into **Eclipse** as an existing Maven project.
3. Update Maven dependencies:
   **Right Click Project → Maven → Update Project**
4. Configure the **ChromeDriver** path.
5. Right-click the **TestNG test/suite**.
6. Select **Run As → TestNG Suite**.
7. Selenium will launch Chrome and execute the test cases.
8. Check the **`test-output`** folder for TestNG execution results.

---
