# Web application for finding teams and projects

Online web application that helps people find like-minded collaborators for informal projects, pet projects, or skill-practice collaborations.

---

## Roles
- **Guest** — user who is not registered and wants to register
- **Project Creator** — user who has a idea for a project and looks for team members
- **Project Seeker** — user who is looking for a project to join
- **User** — common user who can be a **Project Creator** or **Project Seeker**
- **Admin** — system Administrator who manages users and projects

---

## Functional Requirements (User Stories)

### 1. Registration and Authentication

- As a **guest**, I want to be able to register using my email and password.
- As a **user**, I want to be able to log in with valid credentials.
- As a **user**, I want to be able to stay authenticated 
- As a **user**, I want to be able to reset my password via email

### 2. Project Creation and Management

- As a **Project Creator**, I want to be able to create a project I search for team members
- As a **Project Creator**, I want to be able to edit my project
- As a **Project Creator**, I want to be able to delete my project
- As a **Project Creator**, I want to be able to view all projects
- As a **Project Creator**, I want to be able to view my projects
- As a **Project Creator**, I want to be able to view my project details

### 3. Team Seeking and Management

- As a **Project Seeker**, I want to be able to browse a list of open projects.
- As a **Project Seeker**, I want to be able to filter projects by category, tech stack, desired role, and experience level.
- As a **Project Seeker**, I want to be able to search for projects using keywords in the title or description.
- As a **Project Seeker**, I want to be able to view project details

### 4. User Management

- As a **user**, I want to be able to edit my profile
- As a **user**, I want to be able to delete my account
- As a **user**, I want to be able to view other users profiles
- As a **user**, I want to be able to block other users
- As a **user**, I want to be able to report other users

### 5. Communication and Requests

- As a **Project Seeker**, I want to be able to send a request to join a project
- As a **Project Creator**, I want to be able to accept or reject a request to join a project
- As a **Project Seeker**, I want to be able to communicate with **Project Creator** to discuss project details
- As a **Project Creator**, I want to be able to communicate with **Project Seeker** to discuss project details.
- As a **user**, I want to be able to see chat messages in real-time
- As a **user**, I want to be able to access previous conversations linked to the project.
- As a **Project Creator**, I want to be able to view all requests to join my project
- As a **Project Seeker**, I want to be able to view all my requests to join projects
- As a **Project Seeker**, I want to be able to view status of my requests to join projects

### 6. Notifications

- As a **Project Creator**, I want to be able to receive notifications when someone applies to my project.
- As a **Project Seeker**, I want to be able to receive notifications when I am accepted or rejected.
- As a **user**, I want to be able to receive notifications about new messages in chats.

### 7. Admin Management

- As an **admin**, I want to be able to view all users
- As an **admin**, I want to be able to view all projects
- As an **admin**, I want to be able to view all requests to join projects
- As an **admin**, I want to be able to view all chat messages
- As an **admin**, I want to be able to view all reports about inappropriate projects.
- As an **admin**, I want to be able to view all reports about inappropriate users.
- As an **admin**, I want to be able to block users who violate rules.
- As an **admin**, I want to be able to delete or hide inappropriate projects.

## Quality Requirements (Grouped by Quality Attributes)

### 1. Usability

- The system should have an intuitive user interface accessible to non-technical users.
- Registration and onboarding should take no longer than 2 minutes for a new user.


### 2. Security

- The system must protect against common web attacks (XSS, CSRF, SQL injection).
- Passwords must be stored securely using hashing algorithms.
- The system must implement secure user authentication using JWT tokens.

### 3. Performance
- System should load the main dashboard within 1.5 seconds
- Search and filtering operations should return results within 2 seconds.


### 4. Reliability

- The system should be available 95% of the time.
- Chat, requests, and data operations must never result in data loss.

### 5. Maintainability

- The codebase should follow clean architecture principles.
- System should include clean API documentation.

### 6. Portability

- The system must be a web-based application accessible via browsers.
- The frontend must be compatible with recent versions of major browsers.
