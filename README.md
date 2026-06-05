# 🖥️ Video Card Anatomy: What are its components?

An interactive, 3D educational platform designed to demystify the hardware and logic behind modern Graphics Processing Units (GPU).

---

## 👥 Group Members
*   **DE LEON, SOFIA YSABELA**
*   **GALVEZ, ANOUSHEH MONICK ROBENIOL**
*   **GUILLERMO, IAIN DRAEZEN SY**
*   **LEE, ASHLEY FIONA SANTOS**
*   **TIU, AVRAM NATHANIEL PAGUNTALAN**

## 🎯 Group Theme
**Understanding GPU hardware components and how they work together.** 

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
An interactive educational platform designed to help users understand the anatomy of a GPU and how its hardware components work together to deliver graphics and computational performance. The platform covers key components such as the **GPU die, VRAM, cache, memory controllers, display output ports, and power delivery circuitry.** Users can explore detailed explanations, interactive visualizations, and dynamic content that demonstrate the role of each component and how data flows through the GPU during rendering and processing tasks. The project is built using Astro for the application structure, React for interactive user interfaces, MDX for content-driven learning experiences, Supabase for backend services and PostgreSQL database management, and Drizzle ORM for type-safe database operations.

---

## 🗺️ Exhibit Navigation
The platform is organized into the following logical sections:

1.  **Rationale**: The group discusses why we chose the topic and what sparked the interest.
2.  **What is a Video Card?**: This page will discuss a basic definition of what a video card is, clarify its difference from a GPU, discuss how a GPU and a video card are related, and discuss the two types of GPUs: integrated and dedicated.
3.  **CPU vs. GPU**: Discuss how a CPU and a GPU are different internally. This section will also talk about why they have different roles.
4.  **Common Applications**: A long scrollable webpage showcasing a picture and a description for each instance of a video card being used for something (e.g., used in video processing, training AI, crypto mining, etc.).
5.  **Component Anatomy**: A webpage containing an interactive component. A 3D model of a video card that a user can interact with will be shown. The model will be able to rotate with a 360-degree view. The user can click on a component of the video card model, and it will zoom in on that component. The description container right next to the video card model will be updated to display the details on what the component is about and its role in the video card.
6.  **Simulation**: Our other interactive element will be another 3D model of a video card. This time, the component will be used to simulate the processes a video card takes to process data and render a final frame in the VRAM.

---

## 🕹️ Interactive Elements

### 1. 3D Component Explorer
*   A 3D model to be used for showcasing the different components of a video card.
*   Component descriptions will be displayed accordingly depending on the component the user clicks on the 3D model.
*   User can rotate the 3D model.
*   Paragraph description next to the 3D model. It will update depending on the currently selected component.
*   The model should automatically zoom in to the component the user wishes to know more about.

### 2. Rendering Pipeline Simulator
*  A secondary 3D model that simulates how a frame is built.
*  These are going to be MDX files wherein a user interacts with the 3D Model of the GPU on the left. When the GPU is done calculating something, the output will be shown on the right as the current progress of a frame being rendered inside the VRAM.
---

## 📖 Exhibition Content Outline

### Introduction & Rationale
*   Reason for Choosing Topic
*   Objective of the Exhibit
*   Relevance to Modern Computing

### What is a Video Graphics Card?
*   Definition of a Video Graphics Card
*   Purpose and Functions of a Video Graphics Card
*   GPU vs. Video Card: The Distinction
*   Architecture: CPU vs. GPU
*   Form Factors: Integrated vs. Dedicated

### Applications of Video Cards
*   Gaming and Entertainment
*   Scientific Research
*   Artificial Intelligence and Machine Learning
*   Healthcare
*   Finance

### Video Card Components
*   **Graphics Processing Unit (GPU)**: GPU Die, Shader Cores, Thread Block Scheduler, Tensor Cores, Cache Memory (L1, L2, and Shared Memory), Memory Bus.
*   **Memory**: Video RAM (VRAM), Memory Controllers.
*   **Power**: Voltage Requirements, Voltage Regulator Module (VRM).
*   **Communication Interface**: PCIe Connector.
*   **Output Interface**: DisplayPort, DVI, HDMI Port
*   **Video BIOS (VBIOS)**
*   **Cooling**: Cooling Systems (Fans/Heatsinks)

### The Process (Workflow)
1.  **Data Transfer**: CPU to GPU communication via PCIe.
2.  **Execution**: Processing through Shader Cores.
3.  **Storage**: Memory access via VRAM and Controllers.
4.  **Output**: Final Frame Rendering and Display.

---

## 📷 Tentative Style Guide Snapshot
![Tentative Style Guide Snapshot](CSARCH2%20Style%20Guide%20Snapshot.png)

---

## 📜 References

*   **AI applications using GPUs.** (2025, February 13). Aethir. [https://ecosystem.aethir.com/blog-posts/ai-applications-using-gpus-enhancing-computational-efficiency-and-performance](https://ecosystem.aethir.com/blog-posts/ai-applications-using-gpus-enhancing-computational-efficiency-and-performance)
