# Real-Time Collaborative Drawing Canvas

## Overview
The Real-Time Collaborative Drawing Canvas is a web-based application I developed that allows multiple users to draw and collaborate together on a shared canvas in real time. It provides an intuitive interface with essential drawing tools and smooth synchronization, making it ideal for brainstorming sessions, online teaching, and team discussions. The goal was to create a lightweight yet interactive platform where people can connect from anywhere and work on a common whiteboard seamlessly.

## Problem Statement 
Existing online whiteboard tools often have limitations such as restricted customization, delayed synchronization during heavy usage, and lack of flexible room management or access control. To overcome these issues, my project focuses on building a real-time collaborative whiteboard that emphasizes performance, customization, and user control, while ensuring a smooth and responsive multi-user drawing experience.

## Objectives
- Build a real-time collaborative whiteboard where multiple users can draw simultaneously.
- Support freehand drawing using the HTML5 Canvas API.
- Include custom color selection, brush size adjustment, and shape tools.
- Implement undo/redo functionality and clear canvas options.
- Manage multiple sessions using real-time room creation and joining.
- Add role-based access control (RBAC) for user permissions.
- Allow users to save or export their canvas as an image.

## Technologies Used
- **HTML5 Canvas** – For implementing the drawing surface and rendering strokes.
- **WebSocket (Socket.IO)** – For real-time synchronization between users.
- **Node.js & Express** – Backend framework for managing rooms and socket communication.
- **CSS3 & JavaScript (Frontend)** – For UI design and handling user interactions.

## Scope of the project
The application supports real-time drawing, shape creation, and text annotations, allowing multiple users to collaborate within shared rooms. It uses a client-server model, where each client’s actions are transmitted through WebSocket events to ensure immediate updates across all participants.
Additionally, the platform includes secure user authentication and role-based access control for managing who can edit or view the canvas. Future improvements will focus on advanced tools and enhanced performance for large-scale sessions.

## How to Run the Project Locally
 Step 1: Clone the Repository
 git clone https://github.com/missohani/Real-Time-Collaborative-Drawing-Canvas-.git

 Step 2: Go to the Project Directory->
 cd project_root

 Step 3: Install Dependencies->
 npm install, 
 npm start

 Step 5: Open the App
Go to your browser and open:
 http://localhost:8080


## Features

- Real-time collaborative drawing for multiple users
- Custom brush size and color options
- Clear canvas for everyone instantly
- Fast and smooth updates using WebSocket
- Simple to run locally — no extra setup needed