# MeetWise: Advanced Technical Interview Platform

![MeetWise Banner]() <!-- Optional: Add a banner image here -->

## 📌 Overview

**MeetWise** is a modern technical interview platform designed to streamline remote interviews through seamless integration of real-time video conferencing and collaborative code editing. Built with cutting-edge web technologies like **Next.js**, **Convex**, **Clerk**, **Stream**, and **Monaco Editor**, MeetWise offers a robust, secure, and user-friendly experience for both interviewers and candidates.

---

## 🚀 Features

- ✅ Real-time video conferencing (Stream.io)
- ✅ Collaborative code editor (Monaco Editor)
- ✅ Role-based access control (Clerk)
- ✅ Interview scheduling & management
- ✅ Live code evaluation & assessment tools
- ✅ Secure authentication with MFA support
- ✅ Responsive UI with light/dark mode (TailwindCSS)
- ✅ Real-time data sync using Convex

---

## 📽 Live Demo 
  🔗 [MeetWise live demo](https://interviewplatform-two.vercel.app/)
---

## 🧠 Motivation

The project was inspired by the increasing demand for efficient **remote technical assessments** in today's hybrid work environments. Traditional setups often result in fragmented workflows. MeetWise bridges the gap by offering an integrated platform focused on code collaboration, video communication, and interview assessment.

---

## 🎯 Objectives

1. Seamless integration of code editor and video call.
2. Real-time collaboration and assessment tools.
3. Scalable and secure backend.
4. Intuitive UI for all user roles.
5. Role-based workflows (Interviewer/Candidate/Admin).
6. Feature-rich experience with minimal setup.

---

## 🏗 Architecture

MeetWise follows a **serverless, modular architecture**:

```
Frontend       → Next.js + TailwindCSS  
Auth           → Clerk  
Database       → Convex (Realtime DB)  
Video API      → Stream.io (WebRTC)  
Code Editor    → Monaco Editor  
```

---

## 📷 Screenshots

> _Add your UI screenshots here or link to a `/screenshots` folder_

- Interview Dashboard  
- Real-time Code Collaboration  
- Video Conferencing Interface  
- Interview Scheduling UI  

---

## 🧪 Testing Strategy

- ✅ **Unit Tests**: Jest & React Testing Library
- ✅ **Integration Tests**: Feature-level testing
- ✅ **System Tests**: End-to-end user flows
- ✅ **Performance Tests**: Load & latency simulation
- ✅ **CI/CD**: GitHub Actions for automated builds & tests

---

## 📈 Performance Metrics

- Sub-second UI response time  
- Stable video streams at standard bandwidth  
- Real-time collaboration latency: < 150ms  
- Supports concurrent sessions with efficient resource handling  

---

## 🔧 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/chotushikari/MeetWise.git
cd MeetWise

# Install dependencies
npm install

# Add your environment variables (Clerk, Convex, Stream)
cp .env.example .env.local
# Fill in required keys

# Run locally
npm run dev
```

---

## 👥 Team & Contributions

| Name                | Role                             | Key Contributions                            |
|---------------------|----------------------------------|-----------------------------------------------|
| Ashish Pal          | Video Integration                | System architecture, video calls, auth        |
| Minaz Hussain       | Real-time Collaboration Lead     | Code editor sync, Convex integration          |
| Piyush Takrani      | Frontend Developer               | UI components, Tailwind styling, responsiveness|
| Saksham Singhania   | Code Editor Developer            | Monaco Editor features, file operations       |
| Jenny Prasad        | Backend & Testing                | APIs, database, testing, CI/CD, documentation |

---

## 🛠 Tech Stack

- **Frontend**: Next.js, React, TypeScript, TailwindCSS, shadcn/ui  
- **Backend**: Convex (serverless DB), Clerk (Auth)  
- **Realtime**: WebSockets, Convex  
- **Video API**: Stream (WebRTC)  
- **Editor**: Monaco Editor  
- **CI/CD**: GitHub Actions  

---

## 🌱 Future Work

- 🔁 Enhanced interview analytics
- 🔐 Improved security & compliance (GDPR)
- 🧠 AI-assisted code evaluation
- 📱 Mobile support & offline mode
- 📊 Interview insights dashboard
- 🌐 HR & calendar integrations

---

## 📚 References & Docs

- [Next.js Docs](https://nextjs.org/docs)
- [React Docs](https://react.dev)
- [TypeScript Docs](https://www.typescriptlang.org/docs)
- [Clerk Docs](https://clerk.com/docs)
- [Convex Docs](https://docs.convex.dev)
- [Stream.io Docs](https://getstream.io/docs)
- [Monaco Editor Docs](https://microsoft.github.io/monaco-editor)
- [TailwindCSS Docs](https://tailwindcss.com/docs)

---

## 🔗 Repository

[👉 GitHub Repository](https://github.com/chotushikari/MeetWise.git)

---

## 📄 License

> _Add license type here (e.g., MIT, Apache 2.0) if applicable_

---

## 🙌 Acknowledgements

Thanks to our mentor **Dr. Juhi Jain** and all contributors, open-source tools, and documentation communities that supported this project.

---

> **MeetWise**: A platform built for future-ready technical interviews 🌐💻🎥
