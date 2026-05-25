# EmPay 

Multi-tenant Human Resource & Payroll Management System built to learn real-world full-stack development, backend architecture, PostgreSQL, authentication systems, RBAC, and enterprise workflow design.

This project simulates how scalable HRMS platforms work by supporting multiple organizations under a centralized Platform Owner architecture.

---

## Features

* Multi-tenant SaaS architecture
* JWT Authentication & RBAC
* Employee management
* Attendance tracking
* Leave management workflows
* Payroll processing
* Payslip generation
* Dashboard & analytics
* PostgreSQL relational database design

---

## System Roles

* Platform Owner
* Admin
* HR Officer
* Payroll Officer
* Employee

---

## Tech Stack

| Layer          | Technology        |
| -------------- | ----------------- |
| Frontend       | React + Vite      |
| Backend        | Node.js + Express |
| Database       | PostgreSQL        |
| Authentication | JWT               |
| Styling        | Tailwind CSS      |
| Runtime        | Bun               |

---

## Architecture

```text
Platform Owner
        ↓
Companies
        ↓
Admins
        ↓
HR / Payroll Officers
        ↓
Employees
```

---

## Project Structure

```text
frontend/
backend/
docs/
database/
diagrams/
```

---

## Core Modules

* Authentication & Authorization
* Organization Management
* User & Employee Management
* Attendance Management
* Leave Management
* Payroll Management
* Dashboard & Reporting

---

## Database Design

The project uses:

* Relational database architecture
* Foreign key relationships
* Database normalization (up to 3NF)
* Multi-tenant company structure

Core entities:

* companies
* users
* roles
* departments
* attendance
* leave_requests
* payroll
* payrun
* payslips

---

## Development Goals

This project is being built to learn:

* Full-stack development
* Backend engineering
* PostgreSQL & SQL
* REST APIs
* Authentication systems
* RBAC
* Enterprise workflows
* Software engineering practices

---
 
