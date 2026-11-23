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

## Testing

Functional testing will cover the application's CRUD operations. Security testing will assess authentication, access controls, and input handling.

Test procedures, results, and identified issues will be documented as testing is performed.

## Development Log

### 23-11-2026 — Initial Project Planning

- Defined the CyberShield application scope and planned functionality.
- Selected the proposed technology stack.
- Identified the main security controls to be implemented.
- Established the project repository and initial README documentation.
- Next development task: initialise the Django project structure.
