#  CanvaSync – WebSocket-Based Collaborative Drawing Platform

CanvaSync is a collaborative, canvas-based drawing application inspired by tools like Excalidraw.  
The project focuses on smooth rendering, pan/zoom performance, and scalable frontend architecture.

Built as part of a hands-on learning journey to understand **interactive UIs, canvas optimizations, and real-time system design**.

---

##  Key Highlights

-  Smooth freehand drawing using HTML Canvas
-  Pan & zoom support (tested up to **10× zoom**)
-  Optimized canvas rendering for responsive performance
-  Clean, distraction-free dark UI
-  Scalable monorepo architecture using Turborepo

---

## 🛠️ Tech Stack

### Frontend
- Next.js
- TypeScript
- Tailwind CSS
- HTML Canvas API

### Backend (In Progress)
- Node.js
- Express.js
- WebSockets (for real-time collaboration)

### Tooling & Architecture
- Turborepo (monorepo setup)
- pnpm
- ESLint & Prettier
- Modular package-based structure

---

## 📂 Project Structure

excelidraw/
├── apps/
│ ├── web # Main drawing application (Next.js)
│ └── docs # Documentation / demo app
├── packages/
│ ├── ui # Shared UI components
│ ├── eslint # Shared linting config
│ └── tsconfig # Shared TypeScript config
├── turbo.json
└── README.md


---

## 📸 Screenshots

### Landing Page
<img width="1149" height="625" alt="Screenshot 2025-12-19 140423" src="https://github.com/user-attachments/assets/f214127d-24dd-4716-92ca-6a5bbdccb10d" />


### Drawing Canvas
<img width="826" height="800" alt="Screenshot 2025-12-19 140639" src="https://github.com/user-attachments/assets/04087fa0-cf98-4d08-99e5-22778b9c296f" />


---

## Project Status

- ✅ Drawing tools implemented
- ✅ Pan & zoom functionality
- ✅ Canvas performance optimizations
- ? Real-time collaboration — **in progress**
- ? Persistence & auth — planned

> This repository reflects an **actively evolving project**, not a one-day demo.

---

##  What I Learned

- Deep understanding of the Canvas rendering pipeline
- Handling pan/zoom transformations efficiently
- Structuring large frontend apps using monorepos
- Writing scalable, maintainable TypeScript code
- Thinking about real-time collaboration at a system level

---

##  Getting Started (Local Setup)

```bash
pnpm install
pnpm dev

Made with ❤️ by Krishna Soni
