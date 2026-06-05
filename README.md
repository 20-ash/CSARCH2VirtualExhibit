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

* ***AI applications using GPUs.*** (2025, February 13). Aethir. [https://ecosystem.aethir.com/blog-posts/ai-applications-using-gpus-enhancing-computational-efficiency-and-performance](https://ecosystem.aethir.com/blog-posts/ai-applications-using-gpus-enhancing-computational-efficiency-and-performance)
* **Bailey, R.** (2025, July 21). *GPU applications: What are the main applications for GPUs?* Atlantic.Net. [https://www.atlantic.net/gpu-server-hosting/gpu-applications-what-are-the-main-applications-for-gpus/](https://www.atlantic.net/gpu-server-hosting/gpu-applications-what-are-the-main-applications-for-gpus/)
* **Caputo, A. C.** (2014). DVS archiving and storage. In *Elsevier eBooks* (pp. 293-330). [https://doi.org/10.1016/b978-0-12-420042-5.00009-5](https://doi.org/10.1016/b978-0-12-420042-5.00009-5)
* **Caulfield, B.** (2009, December 16). *What's the difference between a CPU and a GPU?* NVIDIA Blog. [https://blogs.nvidia.com/blog/whats-the-difference-between-a-cpu-and-a-gpu/](https://blogs.nvidia.com/blog/whats-the-difference-between-a-cpu-and-a-gpu/)
* **CDW.** (2025, January 22). *CPU vs. GPU: What's the difference?* CDW Research Hub. [https://www.cdw.com/content/cdw/en/articles/hardware/cpu-vs-gpu.html](https://www.cdw.com/content/cdw/en/articles/hardware/cpu-vs-gpu.html)
* **Cho, K., & Bahn, H.** (2020). Performance analysis of thread block schedulers in GPGPU and its implications. *Applied Sciences, 10*(24), 9121. [https://doi.org/10.3390/app10249121](https://doi.org/10.3390/app10249121)
* ***CPU vs GPU: What's the difference and which one should you use?*** (n.d.). Codecademy. [https://www.codecademy.com/article/cpu-vs-gpu-whats-the-difference-and-which-one-should-you-use](https://www.codecademy.com/article/cpu-vs-gpu-whats-the-difference-and-which-one-should-you-use)
* **Difference between graphics card and video card.** (2023, March 29). GeeksforGeeks. [cite_start][https://www.geeksforgeeks.org/computer-organization-architecture/different-between-graphics-card-and-video-card/](https://www.geeksforgeeks.org/computer-organization-architecture/different-between-graphics-card-and-video-card/) [cite: 132, 133, 134]
* **Graphics card - DevX.** (2023, December 18). DevX. [cite_start][https://www.devx.com/terms/graphics-card/](https://www.devx.com/terms/graphics-card/) [cite: 135, 136]
* **Difference between graphics card and video card.** (n.d.). TutorialsPoint. [cite_start][https://www.tutorialspoint.com/article/difference-between-graphics-card-and-video-card](https://www.tutorialspoint.com/article/difference-between-graphics-card-and-video-card) [cite: 137, 138, 139]
* **Elsevier B.V.** (2026). *Video graphic card.* ScienceDirect Topics. [cite_start][https://www.sciencedirect.com/topics/computer-science/video-graphic-card](https://www.sciencedirect.com/topics/computer-science/video-graphic-card) [cite: 140, 141]
* **Fatahalian, K.** (2009). [cite_start]*From Shader Code to a TeraFLOP: How shader cores work.* SIGGRAPΗ 2009. [https://engineering.purdue.edu/~smidkiff/KKU/files/GPUIntro.pdf](https://engineering.purdue.edu/~smidkiff/KKU/files/GPUIntro.pdf) [cite: 142, 143, 144]
* **Glawion, A.** (2022, April 27). *GPU vs graphics card vs video card: Are there any differences?* CGDirector. [cite_start][https://www.cgdirector.com/gpu-vs-graphics-card-vs-video-card/](https://www.cgdirector.com/gpu-vs-graphics-card-vs-video-card/) [cite: 145, 146, 147]
* **GPU architecture explained: Structure, layers & performance.** (2025, April 16). Scale Computing. [cite_start][https://www.scalecomputing.com/resources/understanding-gpu-architecture](https://www.scalecomputing.com/resources/understanding-gpu-architecture) [cite: 148, 149, 150]
* **Ischenko, I.** (2025, October 10). *Understanding GPU architecture basics.* StarWind. [cite_start][https://www.starwindsoftware.com/blog/understanding-gpu-architecture-basics/](https://www.starwindsoftware.com/blog/understanding-gpu-architecture-basics/) [cite: 151, 152, 153]
* **Is there a difference between a GPU, a graphics card, and a video card?** (n.d.). INTROSERV. [cite_start][https://introserv.com/blog/is-there-a-difference-between-a-gpu-a-graphics-card-and-a-video-card/](https://introserv.com/blog/is-there-a-difference-between-a-gpu-a-graphics-card-and-a-video-card/) [cite: 154, 155, 156]
* **Jaylin Jones.** (2026, February 8). *GPUs: The workhorse behind modern computing.* DEV Community. [cite_start][https://dev.to/jaylinjones0/gpus-the-workhorse-behind-modern-computing-5930](https://dev.to/jaylinjones0/gpus-the-workhorse-behind-modern-computing-5930) [cite: 157, 158, 159]
* **Jotrin Electronics.** (2023, December 5). *Everything you need to know about voltage regulator module (VRM).* Jotrin Electronics. [cite_start][https://www.jotrin.com/technology/details/voltage-regulator-module?srsltid=AfmBOopLL6TAeXdkY-hD3xqY FhcqqZ5eGrPePbmk4UGaGhZ v6b0qPC](https://www.jotrin.com/technology/details/voltage-regulator-module?srsltid=AfmBOopLL6TAeXdkY-hD3xqY FhcqqZ5eGrPePbmk4UGaGhZ v6b0qPC) [cite: 160, 161, 162, 163]
* **Leo.** (2024, March 5). *Graphics card basics: Definition, functions, and evolution.* SZYUNZE. [cite_start][https://www.szyunze.com/graphics-card-basics-definition-functions-and-evolution/](https://www.szyunze.com/graphics-card-basics-definition-functions-and-evolution/) [cite: 164, 165, 166, 167]
* **Lheureux, A.** (2022). *A complete anatomy of a graphics card: Case study of the NVIDIA A100.* Paperspace Blog. [cite_start][https://blog.paperspace.com/a-complete-anatomy-of-a-graphics-card-case-study-of-the-nvidia-a100/](https://blog.paperspace.com/a-complete-anatomy-of-a-graphics-card-case-study-of-the-nvidia-a100/) [cite: 168, 169, 170, 171]
* **Mukherjee, S.** (2024, December 25). *Understanding parallel computing: GPUs vs CPUS explained simply with role of CUDA.* DigitalOcean. [cite_start][https://www.digitalocean.com/community/tutorials/parallel-computing-gpu-vs-cpu-with-cuda](https://www.digitalocean.com/community/tutorials/parallel-computing-gpu-vs-cpu-with-cuda) [cite: 172, 173, 174, 175]
* **Plumb, T.** (2025, April 21). *What are GPUs? Inside the processing power behind AI.* Network World. [cite_start][https://www.networkworld.com/article/3966130/what-are-gpus-inside-the-processing-power-behind-ai.html](https://www.networkworld.com/article/3966130/what-are-gpus-inside-the-processing-power-behind-ai.html) [cite: 176, 177, 178]
* **Rákos, D.** (2021, January 25). *Understanding GPU caches.* RasterGrid | Software Consultancy. [cite_start][https://www.rastergrid.com/blog/gpu-tech/2021/01/understanding-gpu-caches](https://www.rastergrid.com/blog/gpu-tech/2021/01/understanding-gpu-caches) [cite: 179, 180, 181]
* **Srinivasa, N.** (2024, July 22). *Exploring the functions, components, and significance of graphics cards in modern computing.* Nitish's Blog (Hashnode). [cite_start][https://nitishs.hashnode.dev/exploring-the-functions-components-and-significance-of-graphics-cards-in-modern-computing](https://nitishs.hashnode.dev/exploring-the-functions-components-and-significance-of-graphics-cards-in-modern-computing) [cite: 182, 183, 184]
* **Video card: What is a video card?** (n.d.). Lenovo Philippines. [cite_start][https://www.lenovo.com/ph/en/glossary/video-card/?orgRef=https%253A%252F%252F](https://www.lenovo.com/ph/en/glossary/video-card/?orgRef=https%253A%252F%252F) [cite: 185, 186, 187]
* **Wilson, M.** (2024, August 28). *What is VGA? Understanding video graphics array technology.* HP. [cite_start][https://www.hp.com/us-en/shop/tech-takes/what-is-vga-comprehensive-guide-video-graphics-array](https://www.hp.com/us-en/shop/tech-takes/what-is-vga-comprehensive-guide-video-graphics-array) [cite: 188, 189, 190, 191]
* **What are video cards used for, other than games?** (n.d.). INTROSERV. [cite_start][https://introserv.com/blog/what-are-video-cards-used-for-other-than-games/](https://introserv.com/blog/what-are-video-cards-used-for-other-than-games/) [cite: 192, 193]
* **What are GPUs useful for? 9 Key applications and emerging trends.** (2025, March 3). DigitalOcean. [cite_start][https://www.digitalocean.com/resources/articles/what-are-gpus-useful-for](https://www.digitalocean.com/resources/articles/what-are-gpus-useful-for) [cite: 194, 195, 196]
* **What is a GPU? Graphics processing units defined.** (n.d.). Intel. [cite_start][https://www.intel.com/content/www/us/en/products/docs/processors/what-is-a-qpu.html](https://www.intel.com/content/www/us/en/products/docs/processors/what-is-a-qpu.html) [cite: 197, 198, 199]
* **What is a video card?** (2025, February 12). Computer Hope. [cite_start][https://www.computerhope.com/jargon/v/video-card.htm](https://www.computerhope.com/jargon/v/video-card.htm) [cite: 200, 201]
* **What is a video card?** (2025, July 23). Geeksforgeeks. [cite_start][https://www.geeksforgeeks.org/computer-organization-architecture/what-is-a-video-card/](https://www.geeksforgeeks.org/computer-organization-architecture/what-is-a-video-card/) [cite: 202, 203, 204]
* **What's the difference between GPUs and CPUs?** (n.d.). [cite_start]Amazon Web Services, Inc. [https://aws.amazon.com/compare/the-difference-between-gpus-cpus/](https://aws.amazon.com/compare/the-difference-between-gpus-cpus/) [cite: 205, 206]
