# System Analysis & Design – Portfolio Submission (DriverPass)

This repository contains portfolio artifacts from **Project One** (Business Requirements Document) and **Project Two** (System Design Document) for the DriverPass case study. Together, they demonstrate requirements elicitation, analysis, and system design skills.

---

## 📦 Portfolio Artifacts
- **Project One:** [Business Requirements Document (BRD)](./CS255/DriverPass/artifacts/CS%20255%20Business%20Requirements%20Document.docx)
- **Project Two:** [System Design Document (SDD)](./CS255/DriverPass/artifacts/CS%20255%20System%20Design%20Document.docx)

---

## 🧭 DriverPass Project – Summary
**Client:** DriverPass (a company helping students prepare for DMV driving tests)  
**Requested System:** A web-based platform where students can register, access practice tests and learning modules, schedule lessons, and track progress with notifications.

**Key Capabilities:** Scheduling, role-based access (Admin/Instructor/Student), content delivery, progress tracking, secure data management, and reporting.

---

## 📝 Reflection

**1) Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?**  
DriverPass needed an online learning and scheduling system to help students prepare for driving tests. The system had to support user accounts, lesson scheduling, practice exams, progress tracking, and communication between students and instructors.

**2) What did you do particularly well?**  
I translated stakeholder interviews into clear business and functional requirements and mapped those to a cohesive architecture. My design artifacts (use cases, context diagram, data model) aligned with the client’s objectives and user workflows.

**3) If you could revise one part, what would it be and how would you improve it?**  
I would deepen the **security & compliance** section: specify authentication flows (MFA, password policies), encryption at rest/in transit, audit logging, data retention, and privacy-by-design controls aligned with industry best practices.

**4) How did you interpret user needs and implement them? Why is that important?**  
I synthesized user goals (flexible scheduling, quick access to practice tests, visibility into progress) into features like calendar scheduling with reminders, progress dashboards, and role-based permissions. Centering user needs increases adoption and ensures the system solves real problems effectively.

**5) How do you approach designing software? What techniques/strategies will you use in the future?**  
I start with stakeholder interviews and requirements workshops, then iterate with:
- **User stories** with acceptance criteria
- **Use case diagrams** and **sequence diagrams**
- **Domain/data modeling** (ERD)
- **Prototyping** for early feedback
- **Nonfunctional requirements** (security, performance, availability, scalability)

Going forward, I’ll use more rapid prototyping and usability testing earlier in the cycle to validate assumptions.
