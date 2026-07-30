# HRM-System
# 🏢 HRMS Frontend

A modern **Human Resource Management System (HRMS)** frontend built with **React, Vite, and Tailwind CSS**. This project aims to provide a complete HR management solution with modules for employee management, recruitment, payroll, projects, reports, and administration.

---

# 🚀 Tech Stack

* React
* Vite
* Tailwind CSS
* React Router DOM
* Axios
* React Icons
* JavaScript (ES6+)

---

# 📂 Project Modules
<br>

## 📊 Dashboard

### Features

* Overview Cards

  * Total Employees
  * Present Today
  * On Leave
  * Total Projects
  * Open Jobs
  * Monthly Payroll
* Attendance Chart
* Employee Growth Chart
* Recent Employees
* Recent Activities
* Upcoming Birthdays
* Recent Announcements

---

## 👥 Employee Management

### Employee

* Employee List
* Add Employee
* Edit Employee
* Delete Employee
* Employee Profile
* Employee Documents
* Emergency Contacts
* Bank Details

### Attendance

* Daily Attendance
* Monthly Attendance
* Check In / Check Out

### Leave

* Apply Leave
* Leave Approval
* Leave History

### Department

* Add Department
* Edit Department

### Designation

* Add Designation
* Assign Employees

---

## 🎯 Recruitment

### Jobs

* Create Job
* Job Listing

### Candidates

* Add Candidate
* Resume Upload
* Candidate Details

### Interview

* Schedule Interview
* Interview Status

### Hiring Pipeline

* Applied
* Screening
* Interview
* Selected
* Rejected

---

## 💰 Payroll

### Salary

* Employee Salary Structure

### Payslip

* Monthly Payslip
* Download PDF

### Bonuses

* Add Bonus

### Deductions

* Tax
* PF
* Other Deductions

---

## 📁 Project Management

### Projects

* Create Project
* Project Details
* Deadline
* Budget

### Tasks

* Create Task
* Assign Employee
* Due Date
* Priority

### Team Members

* Assign Members
* Progress Tracking

### Kanban Board

* Todo
* In Progress
* Review
* Completed

---

## ⚙️ Administration

### Roles

* Admin
* HR
* Manager
* Employee

### Permissions

* CRUD Permissions

### Users

* Manage Accounts

### Settings

* Company Details
* Theme
* Notifications

---

## 📈 Reports

* Employee Report
* Attendance Report
* Leave Report
* Recruitment Report
* Payroll Report
* Project Report

---

# 📁 Folder Structure

```text
HRMS
│
├── client
│   ├── components
│   ├── layouts
│   ├── pages
│   │   ├── Dashboard
│   │   ├── Employees
│   │   ├── Recruitment
│   │   ├── Payroll
│   │   ├── Projects
│   │   ├── Reports
│   │   ├── Admin
│   │   └── Auth
```

---

# 📂 Shared Folder Structure

```text
client
│
├── components
│   ├── ui
│   ├── common
│   ├── charts
│   ├── tables
│   └── forms
│
├── layouts
│   ├── MainLayout
│   ├── AuthLayout
│   └── DashboardLayout
│
├── pages
│   ├── Auth
│   ├── Dashboard
│   ├── Employees
│   ├── Recruitment
│   ├── Payroll
│   ├── Projects
│   ├── Reports
│   └── Admin
```

---

# 👨‍💻 Team Responsibilities

## 👨‍💻 Shivek

### Responsibility

* Dashboard
* Shared Components
* Final Integration

### Pages

* Dashboard
* Dashboard Analytics
* Profile
* Notifications

### Components

* Sidebar
* Navbar
* Cards
* Charts
* Tables
* Widgets
* Breadcrumb

### Additional Responsibilities

* API Integration
* Dashboard Charts
* Final Testing
* Merge Pull Requests
* Deployment

---

## 👨‍💻 Himanshu

### Employee Management

### Pages

* Employee List
* Add Employee
* Edit Employee
* Employee Profile
* Departments
* Designations
* Attendance
* Leaves

### Components

* Employee Card
* Employee Form
* Attendance Table
* Leave Form
* Department Modal

---

## 👨‍💻 Vishal

### Recruitment

* Jobs
* Create Job
* Candidates
* Candidate Details
* Interview Schedule
* Hiring Pipeline

### Payroll

* Salary
* Payslips
* Bonuses
* Deductions

### Components

* Job Card
* Candidate Card
* Salary Table
* Payslip Card
* Interview Timeline

---

## 👨‍💻 Arish

### Project Management

* Projects
* Project Details
* Tasks
* Kanban Board
* Team Members

### Reports

* Attendance Report
* Payroll Report
* Employee Report
* Project Report

### Administration

* Users
* Roles
* Permissions
* Settings

### Components

* Kanban Card
* Task Card
* Role Table
* Report Charts
* Settings Form

---

# 🌿 Git Branch Strategy

| Member   | Branch                      |
| -------- | --------------------------- |
| Shivek   | `dashboard-ui`              |
| Himanshu | `employees-ui`              |
| Vishal   | `recruitment-payroll-ui`    |
| Arish    | `projects-admin-reports-ui` |

---

# 🛠️ Getting Started

Clone the repository:

```bash
git clone https://github.com/shivek-yadav/HRM-System.git
```

Move into the project:

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build the project:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```


## 👨‍💻 Developers

| Name                | Role                               | GitHub                                     |
| ------------------- | ---------------------------------- | ------------------------------------------ |
| **Shivek Yadav**    | Team Lead, Dashboard & Integration | https://github.com/shivek-yadav            |
| **Himanshu Tiwari** | Employee Management                | https://github.com/tiwarihimanshu2427-boop |
| **Vishal Kumar**    | Recruitment & Payroll              | https://github.com/vishal-kumar-000        |
| **Arish Kumar**     | Projects, Reports & Administration | https://github.com/arishkumar1             |




## ❤️ Thank You

Thank you for visiting our HRMS project repository!

We appreciate your time and interest in exploring our work. This project was built as a collaborative learning experience to develop a modern Human Resource Management System using contemporary web technologies.

Your feedback, suggestions, and contributions are always welcome. If you find this project useful, please consider giving it a ⭐ on GitHub—it motivates us to continue learning and building better projects.

Happy Coding! 🚀
