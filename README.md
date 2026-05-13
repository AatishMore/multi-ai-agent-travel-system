# multi-ai-agent-travel-system
# Multi AI Agent Travel System

An intelligent multi-agent AI system built using Streamlit and LangChain that generates complete travel plans using a structured workflow.

Planner Agent → Research Agent → Writer Agent

---

# Features

- AI-powered task decomposition (Planner Agent)
- Research-based content generation (Research Agent)
- Structured travel report generation (Writer Agent)
- Interactive Streamlit UI
- Real-time progress tracking
- Preloaded destination showcase
- Multi-agent workflow orchestration

---

# Agent Workflow

User Input → Planner Agent → Research Agent → Writer Agent → Final Travel Plan

---

# Tech Stack

- Python
- Streamlit
- LangChain
- Groq LLM (LLaMA 3.3 70B)
- python-dotenv
- Streamlit Lottie
- Requests

---

# Project Structure

```
multi-ai-agent-travel-system/
│
├── app.py          # Streamlit frontend UI
├── agents.py       # Planner, Researcher, Writer agents
├── .env            # API keys 
└── README.md
```

---

# Setup Instructions

## Install Dependencies

```bash
pip install streamlit langchain langchain-groq python-dotenv streamlit-lottie requests
```

---

## Set API Key

Create a `.env` file

---

## Run the Application

```bash
streamlit run app.py
```

---

# Example Input

```
Plan a 5 day trip to Goa with budget hotels and activities
```

---

# Example Output

## Planner Agent Output
```
1. Define travel itinerary
2. Select budget accommodations
3. Plan daily activities
```

## Research Agent Output
```
Goa offers beaches, nightlife, water sports, and budget-friendly stays...
```

## Writer Agent Output
```
Day 1: Arrival and beach visit
Estimated Budget: INR 25,000 - 40,000
```

---

# Project Goal

This project demonstrates how multiple AI agents can collaborate to solve complex real-world tasks like travel planning.
