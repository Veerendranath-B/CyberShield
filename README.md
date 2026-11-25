# CyberShield

## Project Overview

CyberShield is a Secure Security Incident Management Portal being developed for the Secure Web Development module.

The application will allow employees to report potential security incidents such as suspicious emails, phishing attempts and unusual login activity and administrators will be able to review, categorise, update and resolve these reports.

The project will demonstrate Create, Read, Update, and Delete (CRUD) functionality alongside appropriate security controls.

## Planned Technologies

- **Backend:** Python and Django
- **Frontend:** HTML, CSS, and Bootstrap
- **Database:** SQLite
- **Authentication:** Django Authentication
- **Version Control:** Git and GitHub

## Planned Architecture

CyberShield will follow a layered architecture:

- Presentation Layer: HTML, CSS and Bootstrap for the user interface.
- Application Layer: Django for business logic, authentication,
  authorization, input validation and session management.
- Database Layer: SQLite for storing user and incident information.

Security checks will be enforced on the server side. Employees will only be permitted to access their own incident reports while administrators will have additional management privileges.

The application will follow principles of least privilege, separation of concerns and secure development.

## Development Methodology

CyberShield will follow an iterative development approach.

Development will be divided into small stages:
1. Project setup and database design.
2. User authentication and role management.
3. Implementation of CRUD functionality.
4. Security controls and access restrictions.
5. Functional and security testing.
6. Documentation and final demonstration.

Security will be considered throughout development, rather than being introduced only during testing.

## Features and Development Progress

- [x] Define the initial project scope
- [ ] Set up the Django project
- [ ] Implement user login and logout
- [ ] Allow employees to create incident reports
- [ ] Display incident lists and individual report details
- [ ] Implement incident updates with appropriate permissions
- [ ] Implement incident deletion with appropriate permissions
- [ ] Implement employee and administrator access controls
- [ ] Complete functional and security testing
- [ ] Complete installation and usage documentation

## Planned CRUD Functionality

| Operation | Planned Functionality |
|---|---|
| Create | Submit a new security incident report |
| Read | View incident reports according to the user's permissions |
| Update | Modify incident information or status according to the user's permissions |
| Delete | Remove an incident report according to the user's permissions |

## Planned Security Controls

- User authentication and session security
- Role-based access control for employees and administrators
- Ownership checks to restrict access to incident reports
- Server-side input validation
- Cross-Site Request Forgery (CSRF) protection
- Safe database access through the Django Object-Relational Mapper (ORM)
- Appropriate handling of application secrets

## Current Status

The project is in the initial planning and repository setup stage. Application development and testing are pending.

## Installation and Running Instructions

Installation requirements, configuration steps, and instructions for running the application locally will be documented during implementation.

## Testing Strategy

The application will undergo functional and security testing.

### Functional Testing
- Verify Create, Read, Update and Delete operations.
- Verify employee and administrator functionality.
- Verify database operations.

### Security Testing
- Authentication and session security testing.
- Role-based authorization and ownership testing.
- Input validation and injection protection testing.
- Static Application Security Testing (SAST) using Bandit.
- Basic security assessment using OWASP ZAP, if feasible.

Test results, screenshots, identified issues and security improvements will be documented.

## Development Log

### 23-11-2026 — Initial Project Planning

- Defined the CyberShield application scope and planned functionality.
- Selected the proposed technology stack.
- Identified the main security controls to be implemented.
- Established the project repository and initial README documentation.
- Next development task: initialise the Django project structure.
