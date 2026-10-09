# Software-Engineering-Project# NSSI Portal – Namal Society for Social Impact

## Project Summary

The NSSI Portal is a web application being developed for the Namal Society for
Social Impact (NSSI), a student society at Namal University that works for the
welfare of the university and nearby communities. Currently, the society's main
activities, such as arranging blood for people in need and recruiting teachers
and students for its educational classes, depend on phone calls, personal
contacts and manual coordination. This project aims to bring these activities
into one organised, secure and easy-to-use system.

The system supports role-based access for Patrons, Co-patrons, the Core Body
(President, Vice President and General Secretary), the Executive Body (Blood
Wing Head and Education Wing Head), General Body members, and local users.

### Main Features

**General**
- Login with role-based access
- Display of upcoming events and event pictures
- Email messaging by Patrons, Co-patrons and the Core Body
- Automatic reminder emails 10 minutes before a meeting
- Addition of General Body members by the Core Body

**Blood Donation Wing**
- Donor records, editable only by the Blood Wing Head
- Donors are removed from the available list for 3 months after donating
- Upload of medical reports of donors
- Records of donors and recipients with filters (for example, 1 month or 1 year)
- Chat feature through which local users request blood
- Blood arrangement by the Blood Wing Head

**Educational Wing**
- Teacher records added and edited by the Education Wing Head
- Online student applications for any class
- Automatic class creation by grouping students of the same class
- One educator can teach many students and classes
- Yearly history of students and teachers

### Project Status
Milestone 1: Project Proposal (Software Engineering, CSC-225)
## Tech Stack

### Frontend
- HTML5, CSS3 and JavaScript (ES6)
- React.js (with React Router)
- Tailwind CSS

### Backend
- Node.js with Express.js
- JSON Web Token (jsonwebtoken) and bcrypt for secure login and role-based access
- Nodemailer for sending emails
- node-cron for automatic reminder emails 10 minutes before meetings
- Socket.IO for real-time chat
- Multer for uploading event pictures and medical reports

### Database
- MySQL (Community Edition)
- MySQL Workbench for ER diagrams and database design

### Design and Documentation
- Figma for wireframes and the prototype
- Draw.io (diagrams.net) for UML diagrams

### Testing
- Postman for API testing
- Jest for automated tests

### Project Management and Version Control
- Git and GitHub
- GitHub Projects for the product backlog and sprint board (Scrum)
- Visual Studio Code

### Deployment (planned)
- Always-on Linux server (Namal server or a rented VPS)
- Nginx, PM2 and Let's Encrypt
- Brevo (free plan) or a similar email service



## Contributors
| Name | Roll No. | Email |
|------|----------|-------|
| Sameer Hayat |BSCS-2025-50 | bscs25f50@namal.edu.pk|
| Muhammad Umair|BSCS-2025-41 | muhammad.umaircs7@gmail.com| 


**Requirement Provider (RP):** (Uswa Asif)
**Instructor:** Asiya Batool, Department of Computer Science, Namal University
