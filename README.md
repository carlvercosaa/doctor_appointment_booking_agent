# 🩺 Doctor Appointment System with Multi-Agent AI

This project is an **AI-powered Doctor Appointment Booking System** built using a **multi-agent architecture**. It simulates a smart assistant that understands natural language queries related to:

- Checking doctor availability
- Cancel appointments
- Booking appointments
- Reschedule appointments

🧩 The system uses coordinated agents to plan, execute, and validate each user query, creating an intelligent and modular assistant workflow.

---

## 🚀 Features

- 🤖 Multi-agent reasoning flow (Planner → Executor → Verifier)  
- 🧠 LangChain + LangGraph for structured task execution  
- ⚡ FastAPI backend for logic processing  
- 🖥️ Streamlit frontend for interactive interface  
- 📂 CSV + Pandas for local data management

## 💬 Example Interaction

> **User:**  
> Can you check if a dermatologist is available on 5th August at 10:00 AM?

> **Agent Response:**  
> Dr. Smith (Dermatologist) is available at 10:00 AM on 05-08-2024. Do you want to book the appointment?

## 🌱 Future Improvements

- Integration with Google Calendar or Outlook  
- User authentication and patient history tracking
- Switch to a cloud database (PostgreSQL/MongoDB)  
- Voice input via speech-to-text APIs
