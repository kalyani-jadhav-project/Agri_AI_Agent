# 🌾 AI Agent for Smart Farming Advice

An AI-powered Smart Farming Assistant built using **IBM Cloud**, **IBM Orchestrate**, **IBM Granite Models**, and **IBM watsonx.ai** to provide farmers with personalized, real-time agricultural recommendations.

Developed as part of the **IBM SkillsBuild x Edunet Foundation - Exploring the Power of Agentic AI with IBM Granite and IBM Orchestrate** program.

---

# 📌 Problem Statement

Farmers face challenges such as:

- Low crop yield
- Unpredictable weather
- Pest and disease outbreaks
- Lack of timely expert guidance
- Market price uncertainty
- Inefficient irrigation and fertilizer usage

This project leverages **Agentic AI** to provide intelligent, personalized, and sustainable farming advice.

---

# 🎯 Objective

Develop an AI-powered Smart Farming Agent capable of:

- 🌱 Crop Advisory
- ☁ Weather & Irrigation Planning
- 🐛 Pest & Disease Detection
- 🌾 Soil Health Recommendations
- 📈 Market Price Prediction
- 📚 Agricultural Knowledge Retrieval using RAG

---

# 🚀 Features

## 🌱 Crop Advisory Agent
- Crop recommendation
- Seed selection
- Fertilizer suggestions
- Irrigation scheduling
- Harvest planning

## ☁ Weather & Irrigation Agent
- Live weather forecasting
- Rainfall prediction
- Irrigation alerts
- Climate-based recommendations

## 🐛 Pest & Disease Detection Agent
- Image-based crop disease detection
- Pest identification
- Treatment recommendations
- Preventive farming practices

## 📈 Market Insights Agent
- Market price prediction
- Demand forecasting
- Best market recommendations
- Cost optimization

## 📚 Agricultural Knowledge Agent (RAG)
- Government agricultural schemes
- Crop cultivation guidelines
- Farming best practices
- Sustainable agriculture recommendations

---

# 🏗 Architecture

```
Farmer
    │
    ▼
Web Application
    │
    ▼
IBM Orchestrate
    │
 ┌──────────────┬───────────────┬──────────────┬──────────────┐
 │              │               │              │
 ▼              ▼               ▼              ▼
Crop       Weather &       Pest Detection   Market
Agent      Irrigation      Agent            Agent
 │              │               │              │
 └──────────────┴───────────────┴──────────────┘
                │
                ▼
        IBM Granite Models
                │
                ▼
           RAG Knowledge Base
                │
                ▼
        IBM watsonx.ai
                │
                ▼
     Personalized Farming Advice
```

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| IBM Cloud | Cloud Platform |
| IBM Orchestrate | Multi-Agent Workflow |
| IBM Granite Models | AI Reasoning & Generation |
| IBM watsonx.ai | AI Model Deployment |
| Retrieval-Augmented Generation (RAG) | Knowledge Retrieval |
| FAISS / ChromaDB | Vector Database |
| Python | Backend |
| Flask / FastAPI | API Development |
| HTML, CSS, JavaScript | Frontend |
| OpenWeather API | Weather Forecast |
| Plant Disease Dataset | Disease Detection |

---

# 🤖 Agentic AI Workflow

The solution uses multiple AI agents working collaboratively.

- Crop Advisory Agent
- Weather & Irrigation Agent
- Pest & Disease Detection Agent
- Market Insights Agent
- Agricultural Knowledge Agent

IBM Orchestrate coordinates these agents to deliver accurate and personalized recommendations.

---

# 📂 Project Structure

```
Smart-Farming-Agent/
│
├── app.py
├── requirements.txt
├── .env
├── README.md
├── static/
│   ├── style.css
│   └── images/
├── templates/
│   └── index.html
├── agents/
│   ├── crop_agent.py
│   ├── weather_agent.py
│   ├── pest_agent.py
│   ├── market_agent.py
│   └── rag_agent.py
├── knowledge_base/
├── vector_db/
└── screenshots/
```

---

# 📸 Project Screenshots

- IBM Orchestrate Workflow
- Architecture Diagram
- Smart Farming Dashboard
- AI Recommendations
- Pest Detection Output
- Weather Insights
- Market Prediction

---

# 💡 Novelty

- Multi-Agent AI Architecture
- Retrieval-Augmented Generation (RAG)
- Personalized Farming Recommendations
- Image-Based Disease Detection
- Real-Time Weather Intelligence
- Government Scheme Retrieval
- Market Price Prediction
- Sustainable Farming Support

---

# 🌍 Future Scope

- IoT Sensor Integration
- Drone-based Crop Monitoring
- Satellite Image Analysis
- AI Voice Assistant
- Regional Language Support
- Blockchain Crop Traceability
- Smart Irrigation Automation
- Yield Prediction using AI

---

# 👨‍💻 Developed For

**IBM SkillsBuild x Edunet Foundation**

**Exploring the Power of Agentic AI with IBM Granite and IBM Orchestrate**

---

# 📜 Certifications

- IBM Orchestrate
- IBM Granite Models
- IBM watsonx.ai
- IBM SkillsBuild
- Edunet Foundation

---

# 🙏 Acknowledgements

- IBM SkillsBuild
- IBM Cloud
- IBM Orchestrate
- IBM Granite
- IBM watsonx.ai
- Edunet Foundation

---

# 📄 License

This project is developed for educational and hackathon purposes under the IBM SkillsBuild x Edunet Foundation program.
