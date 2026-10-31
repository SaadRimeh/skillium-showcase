<div align="center">

![Skillium — learning, structured for progress](./assets/skillium-banner.svg)

<br>

[![Live Platform](https://img.shields.io/badge/OPEN_LIVE_PLATFORM-149DD7?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-lime-eight-cb5c5ameei.vercel.app/)
[![Source](https://img.shields.io/badge/SOURCE_CODE-PRIVATE-173F69?style=for-the-badge&logo=github&logoColor=white)](#source-code)
[![Status](https://img.shields.io/badge/STATUS-ACTIVE-12B886?style=for-the-badge)](#project-status)

### Learning, structured for progress.

Skillium is a full-featured educational platform built to manage the complete academic journey—from structured curricula and sequential lessons to assessments, progress ranks, and private student–tutor meetings.

</div>

---

## Product overview

Skillium brings students, tutors, and administrators into one coordinated learning environment. The platform enforces progression rules rather than simply displaying content: exam outcomes control what a learner can access next, failed attempts trigger guided retry workflows, and every student can receive a secure private meeting link.

The experience is designed around a simple principle: **progress should be visible, earned, and actionable.**

<div align="center">

![Multi-role access](https://img.shields.io/badge/MULTI--ROLE-ACCESS-173F69?style=flat-square)
![Sequential learning](https://img.shields.io/badge/SEQUENTIAL-LEARNING-149DD7?style=flat-square)
![Assessments](https://img.shields.io/badge/SMART-ASSESSMENTS-173F69?style=flat-square)
![Retry workflow](https://img.shields.io/badge/GUIDED-RETRY-149DD7?style=flat-square)
![Private meetings](https://img.shields.io/badge/PRIVATE-MEETINGS-173F69?style=flat-square)
![REST APIs](https://img.shields.io/badge/DOCUMENTED-REST_APIs-149DD7?style=flat-square)

</div>

## The learning loop

```mermaid
flowchart LR
    A[Enroll in a track] --> B[Open available lesson]
    B --> C[Complete learning material]
    C --> D[Take assessment]
    D -->|Pass| E[Unlock next lesson]
    D -->|Needs improvement| F[Retry workflow]
    F --> B
    E --> G[Gain XP and improve rank]
    G --> H[Continue the journey]
```

## Product tour

<div align="center">

### The academy

Browse academic curricula, discover courses, meet verified tutors, and move between the core areas of the learning experience.

<img src="./assets/screenshots/academy-home.png" alt="Skillium academy home showing curricula, instructors, and courses" width="52%">

<br><br>

### Progress that students can understand

The student profile turns learning activity into a clear progression system with enrolled tracks, XP, tier status, exam history, and resumable course timelines.

<img src="./assets/screenshots/student-profile.png" alt="Skillium student profile with XP, rank, tier, and course progress" width="52%">

<br><br>

### Motivation through visible achievement

Leaderboard tiers, total points, completion counts, and global rank give learners an immediate view of where they stand and what comes next.

<img src="./assets/screenshots/leaderboard.png" alt="Skillium leaderboard showing points, rank, enrolled courses, and tier progress" width="52%">

<br><br>

### A focused launch experience

The animated launch state introduces the platform while academic curricula and courses are synchronized.

<img src="./assets/screenshots/loading-screen.png" alt="Skillium loading screen with the platform logo and synchronization progress" width="52%">

</div>

## Core capabilities

- **Multi-role authorization** — dedicated permissions and workflows for students, tutors, and administrators.
- **Structured academic content** — curricula, courses, lectures, and assessments managed through a unified system.
- **Sequential lesson access** — learning material unlocks according to completion and exam outcomes.
- **Assessment-aware progression** — successful results advance the learner; unsuccessful results activate a controlled retry path.
- **Student progress system** — XP, tiers, ranks, enrolled tracks, and completion indicators make progress easy to follow.
- **Private tutor meetings** — secure, student-specific meeting links protect one-to-one academic sessions.
- **Documented REST APIs** — designed to support web, mobile, and administrative clients.
- **Responsive experience** — product flows remain clear across mobile and larger screens.

## Platform roles

### Student

Enrolls in learning tracks, follows sequential lessons, completes assessments, monitors XP and rank, and joins private meetings.

### Tutor

Delivers academic content, manages learning material, supports students, and coordinates protected one-to-one sessions.

### Administrator

Manages users, roles, curricula, courses, assessments, progression rules, and platform-wide academic operations.

## Engineering highlights

- Designed authorization around multiple academic roles instead of a single generic user model.
- Modeled lesson availability as a progression state controlled by assessment results.
- Created retry workflows that preserve learning continuity after unsuccessful exam attempts.
- Separated platform capabilities behind documented REST endpoints for multiple client applications.
- Treated meeting access as private student data rather than a shared public resource.

## Project status

Skillium is an active portfolio project with a live demonstration available for product exploration.

[**Launch Skillium ↗**](https://portfolio-lime-eight-cb5c5ameei.vercel.app/)

## Source code

This repository is a **public product showcase**. The production source code, infrastructure configuration, credentials, and private project documentation are intentionally not included.

The screenshots and product materials in this repository are provided for portfolio presentation. All rights are reserved.

---

<div align="center">

### Built by Saad Rimeh

[![GitHub](https://img.shields.io/badge/GitHub-SaadRimeh-171B23?style=for-the-badge&logo=github)](https://github.com/SaadRimeh)
[![Portfolio](https://img.shields.io/badge/Portfolio-Explore_Work-149DD7?style=for-the-badge&logo=vercel&logoColor=white)](https://saadrimeh.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/saad-rimeh)

<sub>PRIVATE ENGINEERING // PUBLIC PRODUCT STORY</sub>

</div>
