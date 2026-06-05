# 🖥️ Video Card Anatomy: What are its components?

An interactive, 3D educational platform designed to demystify the hardware and logic behind modern Graphics Processing Units.

---

## 👥 Group Members
*   **DE LEON, SOFIA YSABELA**
*   **GALVEZ, ANOUSHEH MONICK ROBENIOL**
*   **GUILLERMO, IAIN DRAEZEN SY**
*   **LEE, ASHLEY FIONA SANTOS**
*   **TIU, AVRAM NATHANIEL PAGUNTALAN**

## 🎯 Group Theme
**Understanding GPU hardware components and how they work together.** 
Our goal is to bridge the gap between "abstract hardware" and "visual performance" through immersive 3D interaction.

## 🛠️ Tech Stack
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

*   **Astro**: Project structure skeleton and optimized routing.
*   **React**: Interactive UI components and state management.
*   **MDX**: Dynamic, component-driven educational content.
*   **Supabase & Drizzle**: Managed PostgreSQL database with type-safe ORM for backend logic.
*   **React Three Fiber & Drei**: High-performance 3D rendering and helper utilities for browser-based interaction.

---

## 📝 Project Description
This interactive educational platform is designed to help users understand the anatomy of a GPU and how its hardware components work together to deliver graphics and computational performance. The platform covers key components such as the **GPU die, VRAM, cache, memory controllers, display output ports, and power delivery circuitry.** 

Users can explore detailed explanations, interactive visualizations, and dynamic content that demonstrate the role of each component and how data flows through the GPU during rendering and processing tasks. Built with a modern web stack, the project combines technical depth with a seamless, interactive user experience.

---

## 🗺️ Exhibit Navigation
The platform is organized into the following logical sections:

1.  **Rationale**: A look into why we chose this topic and what sparked our interest in hardware anatomy.
2.  **What is a Video Card?**: Definitions and clarifications. We distinguish between a "Video Card" and a "GPU," and compare Integrated vs. Dedicated solutions.
3.  **CPU vs. GPU**: An internal comparison of architecture and a breakdown of why their roles in computing differ so drastically.
4.  **Common Applications**: A scrollable gallery showcasing the GPU's role in video processing, AI training, cryptocurrency mining, and more.
5.  **Component Anatomy**: An interactive 3D explorer. Users can rotate a 360° model of a video card, click specific parts, and receive real-time detailed breakdowns.
6.  **Simulation**: A step-by-step 3D simulation of the rendering pipeline, showing how data transforms from raw input to a final frame in the VRAM.

---

## 🕹️ Interactive Elements

### 1. 3D Component Explorer
*   **360° Interaction**: Full rotation and zoom controls using `Drei`.
*   **Dynamic Highlighting**: Clicking a component (e.g., the VRM or GPU Die) triggers a focus-zoom animation.
*   **Contextual UI**: A side panel updates dynamically using React state to show descriptions based on the selected 3D mesh.

### 2. Rendering Pipeline Simulator
*   **Live Rendering Logic**: A secondary 3D model that simulates how a frame is built.
*   **MDX Integration**: Interactive text files that communicate with the 3D scene. As the user reads about "Calculations," the 3D model visualizes the output being written to the VRAM on the right side of the screen.

---

## 📖 Exhibition Content Outline

### Introduction
*   Definition of a Video Graphics Card
*   Purpose and Functions
*   GPU vs. Video Card: The Distinction
*   Architecture: CPU vs. GPU
*   Form Factors: Integrated vs. Dedicated
*   Applications in Modern Computing

### Video Card Components
*   **Processing**: GPU Die, Shader Cores, Thread Block Scheduler.
*   **Memory**: Cache Memory, VRAM, Memory Controllers.
*   **Power**: Voltage Requirements, Voltage Regulator Module (VRM).
*   **Interface & Cooling**: PCIe Connector, Cooling Systems (Fans/Heatsinks).

### The Process (Workflow)
1.  **Data Transfer**: CPU to GPU communication via PCIe.
2.  **Execution**: Processing through Shader Cores.
3.  **Storage**: Memory access via VRAM and Controllers.
4.  **Output**: Final Frame Rendering and Display.

---