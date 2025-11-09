# SE-Project
**Google Sheet:** [Meeting Minutes](https://github.com/bilal-512/SE-Project/blob/main/meeting_minutes/googlesheet.md)
**Videos Link:**  [Videos](https://github.com/bilal-512/SE-Project/tree/main/Meeting_Videos)
# Student Productivity & Engagement Platform
## Project Overview
The **Student Productivity & Engagement Platform** unifies multiple academic systems into one centralized interface. It integrates LMS portals, administrative notifications, and student resources, allowing learners to manage all academic tasks and communications through web and mobile apps.  
The platform’s vision is to create an ecosystem that promotes academic responsibility and mental wellness through intelligent automation, collaboration, and gamification. Its target users are undergraduate and graduate students seeking centralized access to academic tracking, collaboration, and wellness tools.
## Problem Statement
Universities often use disconnected systems for courses, assignments, and announcements. Students must juggle multiple portals, leading to missed deadlines and reduced engagement. The lack of motivation tools and wellness support further contributes to stress and confusion.  

This fragmentation causes frustration for students, confusion for faculty, and management challenges for administrators. The platform addresses these issues by integrating systems, promoting engagement, and supporting student well-being.
## Core Objectives
The project aims to:
- **Unify academic systems** into a real-time dashboard with synchronized LMS data.
- **Increase engagement** through gamification (points, badges, streaks, leaderboards).
- **Enable collaboration** via study rooms, team challenges, and mentorship features.
- **Support wellness** with smart break reminders, workload tracking, and mindfulness tools.
- **Ensure accessibility** across web, iOS, and Android with consistent performance.
## System Architecture
The platform uses a **microservices architecture** with separate frontend, backend, and data layers.
- **Frontend:** React.js for web and React Native for mobile apps, using a shared UI library for consistent design.
- **Backend:** Node.js and Express.js with REST APIs, Socket.io for real-time communication, and an API gateway for load balancing.
- **Database:** MongoDB for storage, Redis for caching, and cloud backups for reliability.
- **Integration:** Supports LMS APIs, OAuth 2.0 authentication, university SSO, and external notification systems.
## Technology Stack
- **Frontend:** React.js, TypeScript, Tailwind CSS, React Query, Axios  
- **Mobile:** React Native, React Navigation, Async Storage  
- **Backend:** Node.js (v20 LTS), Express.js, TypeScript, MongoDB, Mongoose, Redis  
- **Security:** OAuth 2.0, JWT, HTTPS/TLS 1.3, MFA, OWASP standards  
- **Integrations:** Canvas, Moodle, Blackboard, Firebase, SendGrid  
- **Monitoring:** Google Analytics, Sentry, Custom dashboards  
- **DevOps:** GitHub Actions, Docker, Kubernetes, AWS/GCP/Azure  
## Development Methodology
The project follows the **Agile Scrum** framework with 2–4 week sprints.  
- **Product Owner:** Manages backlog and priorities.  
- **Scrum Master:** Facilitates meetings and removes blockers.  
- **Developers:** Build, test, and review features.  
Testing includes unit, integration, and user acceptance tests integrated with CI/CD pipelines to maintain high-quality code delivery.
## Feature Overview
### Academic Dashboard
A personalized dashboard showing deadlines, grades, and announcements in one view. It includes a timeline, color-coded priorities, unified notifications, and calendar integration with external tools.
### Gamification
Students earn points and badges for task completion, maintain streaks, and appear on leaderboards. Personalized challenges keep them motivated and engaged.
### Collaboration
Includes virtual study rooms, peer mentorship matching, file sharing, and discussion forums to promote academic cooperation and support.
### Wellness
Features intelligent break reminders, workload indicators, stress tracking, and a library of mindfulness exercises integrated with campus wellness resources.
## Team Structure
- **Bilal** – Backend Developer (API development and optimization)  
- **Waseem** – Mobile Developer (React Native app)  
- **Hadia** – UI/UX Designer & Frontend Developer  
**Client Representatives:** *Shazia* and *Maryam* – Requirement validation, user testing, and feedback collection.  
**Supporting Stakeholders:** University IT (infrastructure & security), Faculty (user insights), and Administration (strategic oversight).
## Contributing
Developers are welcome to contribute by forking the repository and creating feature branches. All contributions must follow ESLint standards, include documentation, and maintain test coverage above 80%.
### Workflow
1. Fork the repository  
2. Create a feature branch  
3. Implement and test changes  
4. Submit a pull request  
5. Address feedback and resolve conflicts  
### Pull Request Requirements
- All tests must pass  
- Include clear feature documentation  
- Address reviewer comments  
- No merge conflicts before approval  

**Status:** *In Development*
