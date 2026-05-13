# Task Manager 🚀

A streamlined, web-based Task Manager application developed as part of the "AI-Assisted Development and Git Mastery" assignment. This project demonstrates the synergy between human guidance and Generative AI collaboration.

## 🎯 Objective
The primary goal of this project was to build a functional software tool while mastering the **Git Command Line Interface (CLI)** and professional version control workflows, including branching, merging, and remote repository management.

## 🛠️ Features
- **Task Creation:** Add tasks instantly via the input field or by pressing the "Enter" key.
- **Dynamic Deletion:** Remove completed tasks from the list with a single click.
- **Responsive Design:** A clean, modern UI that works across different screen sizes.
- **AI Collaboration:** Logic and error handling were refined using Gemini AI.

## 🔍 Internal Code Structure (index.html)

The `index.html` file is organized into three main layers to ensure clean code practices:

### 1. The Structure (HTML5)
Located within the `<body>` tag, this section defines the visual elements:
- A **Container Div**: Acts as the main wrapper for the application.
- **Input Header**: Contains the `<h2>` title and the text input field.
- **Dynamic List**: An empty `<ul>` (unordered list) with the ID `taskList`, which serves as a placeholder for tasks added via JavaScript.

### 2. The Presentation (CSS3)
Embedded within the `<style>` tags in the `<head>`, the styling focuses on:
- **Flexbox Layout**: Used on the `body` to center the application both horizontally and vertically.
- **Visual Feedback**: Includes `:hover` states for buttons to improve User Experience (UX).
- **UI Components**: Modern styling for cards, input fields, and specialized colors for "Delete" actions (red) and "Add" actions (green).

### 3. The Logic (JavaScript)
Located at the bottom within `<script>` tags, the logic handles the interactivity:
- **`addTask()` Function**: 
    - Captures the input value using `document.getElementById`.
    - Performs validation to prevent empty tasks.
    - Creates new HTML elements on the fly (`document.createElement`).
    - Injects a delete button into each task for real-time removal.
- **Event Listeners**: A specific listener is attached to the input field to detect the **"Enter"** key, providing a seamless workflow.

## 📂 Project Structure
The project follows a lightweight, single-page application (SPA) architecture:

```text
.
├── index.html          # Core logic, structure, and styling
└── README.md           # Project documentation and Git journey summary
