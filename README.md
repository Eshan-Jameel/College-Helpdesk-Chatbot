# 🎓 College Brochure Chatbot: AI Document Q&A

## ✨ Project Overview

This application is a specialized web chatbot designed to answer user questions instantly and accurately based *only* on the contents of a provided official document (the college brochure).

It is built as a miniature full-stack project, demonstrating how to integrate modern AI (Gemini) with a simple Node.js backend to extract knowledge from proprietary data.

## 🚀 Live Demo & Screenshots

> **Note:** For maximum impact, consider adding a screenshot or GIF of the chatbot running here once your site is deployed!

* **Repository URL:** `https://github.com/Eshan-Jameel/Web-Dev-Project.git`

## 🛠 Tech Stack

| Component | Technology | Role |
| :--- | :--- | :--- |
| **AI Model** | `@google/generative-ai` | Powers the natural language understanding and document querying. |
| **Backend** | **Node.js & Express** | Handles API routing, server logic, and communication with the Gemini API. |
| **Frontend** | **HTML/CSS/Vanilla JS** | Provides the user interface for the chat window. |
| **Data Source** | `college-brochure.pdf` | The foundational document used as the knowledge base for all answers. |

## 📦 Project Structure

The project is split into two primary folders:
Mini Project/ ├── chatbot-backend/ # Node.js Express Server │ ├── index.js # Backend server logic │ └── package.json # Dependencies (@google/generative-ai, express, dotenv) ├── assets/ │ └── college-brochure.pdf # Source of truth for the Chatbot └── front.html # Main front-end interface

⚙️ Installation and Local Setup

To run this project locally, you need to set up both the backend and frontend components.

### 1. Prerequisites

1.  **Node.js:** Must be installed to run the backend server.
2.  **API Key:** A valid Gemini API Key.

### 2. Backend Setup

1.  Navigate into the backend directory:
    ```bash
    cd Mini Project/chatbot-backend
    ```
2.  Install required packages:
    ```bash
    npm install
    ```
3.  **Create a `.env` file** in the `chatbot-backend` directory and add your API key:
    ```
    GEMINI_API_KEY="YOUR_API_KEY_HERE"
    ```
4.  Start the server:
    ```bash
    npm start
    ```
    The backend server should start running, typically on `http://localhost:3000`.

### 3. Frontend Access

Once the backend is running:

1.  Open the `front.html` file located in the main `Mini Project/` folder directly in your web browser.
2.  You should now be able to interact with the chatbot, which communicates with your running Node.js backend.

---