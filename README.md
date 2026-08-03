###👋 Hey there!

## 🚩My portfolio:

[🔗 Click to link](https://nghiaut.github.io/my-portfolio/)

## 🌟 About me

- 👋I'm Trọng Nghĩa, you can call me Nghĩa for short
- 📖Currently studying **Computer Science** at Ho Chi Minh University of Technology(**BKU**)
- 🚀Aiming for further career in software engineering, especially in backend development
- 🙌Enthusiastic learner and strive for new knowledge
- 🧗TOEIC 955: Strong Listening & Reading, Now Improving Writing & Speaking

## 🧰Languages & Frameworks

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

## 📊 Most Used Languages

[![Top Langs](https://vercel.app)](https://github.com/NghiaUT)

## 🚀 Featured Projects

### Fotobook — Full-stack Photo Sharing Platform

**Repo:** [NghiaUT/NUS-Final-App](https://github.com/NghiaUT/NUS-Final-App)
**Live Demo:** [nus-final-app.vercel.app](https://nus-final-app.vercel.app)

Capstone project for a software engineering internship at NUS Technology. Built from an existing Figma design as a **monorepo**, housing both backend and frontend in a single repository to keep types and build workflows consistent across both sides.

Key technical highlights:

- Used **Prisma Transactions** to guarantee data integrity during photo uploads — properly rolling back on mid-process failures (network errors, validation errors) instead of leaving orphaned records in the database
- Solved a **race condition** that occurred when a user uploaded multiple photos in quick succession, preventing duplicate or lost records
- Backend architecture uses **Redis + BullMQ** for asynchronous job queues (verification emails, image processing), decoupling heavy work from the main request/response cycle
- User authentication via **JWT**, file uploads handled with **Multer**

**Tech stack:** React 19, TypeScript, Vite, TailwindCSS, React Query — Node.js/Express, TypeScript, Prisma ORM, PostgreSQL, Redis

---

### EventPass — Event Ticketing Platform

**Repo:** [NghiaUT/EventPass_Frontend](https://github.com/NghiaUT/EventPass_Frontend)
**Live Demo:** [qldapm-front-end.vercel.app (Hot Reload)](https://qldapm-front-end.vercel.app/)

Built following a **Scrum** workflow, EventPass is an event ticketing platform that supports **check-in via dynamic QR codes** and login through **Google and Facebook**.

Key highlights of the role:

- Took on the **Business Analyst** role in the early phase — gathering requirements and mapping out the business flow for ticket booking and check-in
- Transitioned to a **Fullstack Developer** role in later sprints, building out modules and features directly from the backlog — demonstrating the ability to move fluidly between business analysis and hands-on engineering
- Applied React to build a consistent, seamless UX — particularly for the QR check-in flow, which demands fast and clear feedback for users at live events

**Tech stack:** React, Vite, TailwindCSS
