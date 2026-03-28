# 🚀 Multi-View Project Tracker – Velotrack

A modern multi-view project management dashboard built with **React + TypeScript**.  
Supports **Kanban**, **List (virtualized)**, and **Timeline views**, with drag & drop, filtering, and live collaboration simulation.

---

## 🌐 Live Demo

[Check the live project here](https://bit.ly/task-tracker-sanika)

---

## 📌 Features

### 🗂️ Multi View System
- Kanban Board (drag & drop tasks between columns)  
- List View (optimized with virtualization)  
- Timeline View (Gantt-style project tracking)

### ⚡ Task Management
- Create new tasks  
- Update task status  
- Assign priority (Low, Medium, High, Critical)  
- Set due dates

### 🔍 Smart Filtering
- Filter by status, priority, or assignee  
- Instant search for tasks

### 🧑‍🤝‍🧑 Live Collaboration Simulation
- Simulated active users  
- Real-time task movement updates

### 🖱️ Drag & Drop System
- Smooth pointer-based drag interactions  
- Visual drop target highlighting  
- Drag preview cards

### 📊 Performance Optimized
- Virtualized list rendering for large datasets  
- Memoized filtering and grouping  

---

## 🖼 Screenshots / GIFs

![Kanban Board](screenshots/kanban.png)  
![Drag & Drop Tasks](screenshots/drag-drop.gif)  
![List View](screenshots/list-view.png)  
![Timeline View](screenshots/timeline.png)

> 📌 Place all screenshots/GIFs in the `screenshots/` folder in the root directory.

---

## 🛠 Tech Stack

- React (TypeScript)  
- Zustand (State Management)  
- Tailwind CSS  
- Vite / Create React App (based on setup)  
- Custom Drag & Drop logic  

---

## 📂 Project Structure

```text
multi-view-project-tracker/
├─ src/
│  ├─ components/
│  │  ├─ Kanban.tsx
│  │  ├─ TaskCard.tsx
│  │  ├─ TaskRow.tsx
│  │  └─ ListView.tsx
│  ├─ store/
│  │  └─ store.ts
│  ├─ App.tsx
│  └─ main.tsx
├─ screenshots/
├─ README.md
├─ LICENSE
└─ package.json
