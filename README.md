# CSARCH2VirtualExhibit

Group Title: Video Card Anatomy: What are its components?

Group Members:
DE LEON, SOFIA YSABELA
GALVEZ, ANOUSHEH MONICK ROBENIOL
GUILLERMO, IAIN DRAEZEN SY
LEE, ASHLEY FIONA SANTOS
TIU, AVRAM NATHANIEL PAGUNTALAN

Group Theme:
Understanding GPU hardware components and how they work together.

Group Tech Stack:
Astro - Project structure skeleton.
React - For interactive components and UI render.
MDX - Dynamic elements.
Supabase - Manage postgresql database and write backend logic.
Drizzle - ORM for postgresql on Supabase.
React Three Fiber: For handling 3d rendering and interactions.
Drei: Library containing premade helper functions for React Three Fiber.

Project Description: *Is this correct ?
	An interactive educational platform designed to help users understand the anatomy of a GPU and how its hardware components work together to deliver graphics and computational performance. The platform covers key components such as the GPU die, VRAM, cache, memory controllers, display output ports, and power delivery circuitry. Users can explore detailed explanations, interactive visualizations, and dynamic content that demonstrate the role of each component and how data flows through the GPU during rendering and processing tasks. The project is built using Astro for the application structure, React for interactive user interfaces, MDX for content-driven learning experiences, Supabase for backend services and PostgreSQL database management, and Drizzle ORM for type-safe database operations.


Exhibit Navigation will be composed of the following pages:
Rationale: Group discusses why we chose our topic. What sparked our interest.
What is a video card: This page will discuss a basic definition of what a video card is, clarifying its difference with a GPU, discussing how a GPU and a video card are related, and discuss the two types of GPUs: integrated and dedicated.
Difference between cpu and gpu: Discuss how a GPU and  CPU are different internally. Will also talk about why they have different roles.
Common applications of video cards: A long scrollable webpage showcasing a picture and a description for each instance of a video card being used for something {e.g. used in video processing, training AI, crypto mining, etc.).
Component name: A webpage containing an interactive component. A 3d model of a video card will be shown that a user can interact with. The model will be able to rotate with a 360 view. The user can click on a component of the video card model and it will zoom in to that component. The description container right next to the video card model will be updated to display the details on what the component is about and its role in the video card.
Simulation: Our other interactive element will be another 3d model of a video card. This time, the component will

Interactive Element: (3d rendering with React Three Fiber and Drei)
A 3d model to be used for showcasing the different components of a video card.
Component descriptions will be displayed accordingly depending on the component the user clicks on the 3d model.
User can rotate the 3d model.
Paragraph description next to the 3d model. Will update depending on the currently selected component.
The model should automatically zoom in. To the component the user wishes to know more about.
Another 3d model to simulate the steps a video card does to render a frame.
These are going to be MDX files wherein when a user interacts with the GPU 3d Model on the left. When the gpu is done calculating something, the output will be shown on the right as the current progress of a frame being rendered inside vram.


Exhibition Content:
Introduction
Definition of a Video Graphics Card
Purpose and Functions of a Video Graphics Card
Difference between a GPU and Video Cards
Difference between cpu and gpu
Integrated and dedicated gpus
Importance in Modern Computing (?)
Application of video cards
Video Card Components
Graphics Processing Unit (GPU)
GPU Die (processor)
Shader cores
Thread Block Scheduler
Cache Memory
Memory Subsystems
Video RAM (VRAM)
Memory controllers
Power 
Voltage Requirements
Voltage Regulator Module (VRM)
Communication Interface
PCIE Connector
Cooling System


Process (How it works together)
Data Transfer from CPU to GPU
Processing by Shader Core
Memory Access through VRAM and Memory Controllers
Frame Rendering

