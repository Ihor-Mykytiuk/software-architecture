# Platform for finding teams and projects

Online platform that helps people find like-minded collaborators for informal projects, pet projects, or skill-practice collaborations.

---

## Roles
- **Guest** — user who is not registered and wants to register
- **Project Creator** — user who has a idea for a project and looks for team members
- **Team Seeker** — user who is looking for a project to join
- **User** — common user who can be a **Project Creator** or **Team Seeker**
- **Admin** — platform Administrator who manages users and projects

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

- As a **Team Seeker**, I want to be able to browse a list of open projects.
- As a **Team Seeker**, I want to be able to filter projects by category, tech stack, desired role, and experience level.
- As a **Team Seeker**, I want to be able to search for projects using keywords in the title or description.
- As a **Team Seeker**, I want to be able to view project details

### 4. User Management

- As a **user**, I want to be able to edit my profile
- As a **user**, I want to be able to delete my account
- As a **user**, I want to be able to view other users profiles
- As a **user**, I want to be able to block other users
- As a **user**, I want to be able to report other users

### 5. Communication and Requests

- As a **Team Seeker**, I want to be able to send a request to join a project
- As a **Project Creator**, I want to be able to accept or reject a request to join a project
- As a **Team Seeker**, I want to be able to communicate with **Project Creator** to discuss project details
- As a **Project Creator**, I want to be able to communicate with **Team Seeker** to discuss project details.
- As a **user**, I want to be able to see chat messages in real-time
- As a **user**, I want to be able to access previous conversations linked to the project.
- As a **Project Creator**, I want to be able to view all requests to join my project
- As a **Team Seeker**, I want to be able to view all my requests to join projects
- As a **Team Seeker**, I want to be able to view status of my requests to join projects

### 6. Notifications

- As a **Project Creator**, I want to be able to receive notifications when someone applies to my project.
- As a **Team Seeker**, I want to be able to receive notifications when I am accepted or rejected.
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
