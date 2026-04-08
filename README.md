# 🐾 Multi-Agent Zoo Guide Assistant

An intelligent **Multi-Agent AI System** designed to assist users in managing queries, tasks, and wildlife information through a unified conversational interface.  
The system leverages multiple AI agents that collaborate to retrieve, process, and present information efficiently.

---

## 📌 Overview

The Multi-Agent Zoo Guide Assistant is a cloud-based AI application that enables users to interact naturally and receive detailed, context-aware responses about animals and related information.

Unlike traditional systems, this solution uses a **multi-agent architecture**, where each agent performs a specialized task such as:
- Data retrieval
- Knowledge processing
- Response formatting

This modular design improves scalability, flexibility, and overall performance.

---

## 🎯 Problem Statement

Build a multi-agent AI system that helps users manage tasks, schedules, and information by interacting with multiple tools and data sources, implemented here as a Zoo Guide Assistant.

---

## 🚀 Key Features

- 🧠 Multi-agent architecture for intelligent task handling  
- 💬 Conversational interface for natural interaction  
- 🔍 Integration with external knowledge sources (e.g., Wikipedia)  
- 🐘 Structured wildlife data retrieval (habitat, diet, lifespan, etc.)  
- ⚡ Context-aware response generation using AI models  
- ☁️ Cloud deployment using scalable infrastructure  
- 🔗 API-based interaction via HTTP endpoints  

---

## 🏗️ System Architecture

The system follows a **multi-agent pipeline architecture**:

1. **User Input Layer**  
   - Accepts user queries via API or interface  

2. **Root Agent (Controller)**  
   - Manages the overall workflow  
   - Routes tasks to appropriate agents  

3. **Research Agent**  
   - Retrieves data from:
     - External APIs (Wikipedia)
     - Internal datasets  

4. **Processing Layer**  
   - Organizes and filters collected information  

5. **Formatter Agent**  
   - Converts raw data into human-friendly responses  

6. **Response Layer**  
   - Sends final output back to the user  

---

## 🔄 Workflow

1. User submits a query  
2. Root agent receives and analyzes the request  
3. Research agent gathers relevant data  
4. Data is processed and structured  
5. Formatter agent generates a clear response  
6. Final answer is returned to the user  

---

## 🛠️ Tech Stack

| Technology | Purpose |
|----------|--------|
| Python | Core programming language |
| FastAPI | API development |
| Google ADK | Multi-agent orchestration |
| Vertex AI (Gemini) | Generative AI responses |
| LangChain Tools | Tool integration |
| Wikipedia API | External knowledge source |
| Docker | Containerization |
| Cloud Run | Deployment |
| Google Cloud Logging | Monitoring |

---

## 📁 Project Structure
Zoo_ADK_Agent/
│── agents/ # Multi-agent logic
│── tools/ # External integrations
│── services/ # Backend services
│── main.py # Entry point
│── requirements.txt # Dependencies
│── Dockerfile # Container setup
│── README.md # Documentation
