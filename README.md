🤖📷 Smart AI Communication Agent

Chat & Image Analyzer with Email Agent (Agentic AI using n8n + Ollama)
An AI-powered automation workflow built using n8n, Ollama, and Docker, capable of:

💬 Answering text-based questions
🖼️ Analyzing uploaded images and describing them
✉️ Sending AI-generated responses via Gmail
🌐 Interacting through API using Webhook + Postman

This project demonstrates how to build an Agentic AI system using open-source tools

🚀 Features

✅ Text-based AI chat using Ollama LLM
✅ Image analysis using vision-capable Ollama models
✅ Automatic decision routing (text vs image)
✅ Email sending using Gmail API
✅ Webhook-based API interaction
✅ Fully containerized using Docker Compose

🧠 Tech Stack

| Tool                     | Purpose                                |
| ------------------------ | -------------------------------------- |
| **n8n**                  | Workflow automation & AI orchestration |
| **Ollama**               | Local LLM + Vision model serving       |
| **Docker Desktop**       | Container management                   |
| **Docker Compose**       | Multi-container setup                  |
| **Postman**              | API testing                            |
| **Google Cloud Console** | Gmail API credentials                  |
| **Trae IDE**             | Docker & workflow development          |


Client (Postman / App)
        |
     Webhook
        |
       n8n
        |
   ┌────┴─────┐
Text Flow   Image Flow
   |             |
Ollama LLM   Ollama Vision
   └────┬─────┘
        |
   Gmail Node
        |
     User Email

⚙️ Setup Instructions

![n8n workflow](https://i.ibb.co/pvJ8rDqv/Screenshot-2026-01-14-093049.png)

---------------------- [] n8n [] -----------------------------------

![Ollama models](https://i.ibb.co/RG8nqXSp/Screenshot-2026-01-14-103152.png)

---------------------- [] Ollama [] ------------------------------

![Trae AI assistant IDE](https://i.ibb.co/bMmpwRBy/Screenshot-2026-01-13-191853.png)

------------------------- [] Trae Ai assistant IDE for future --------------------

![Docker runtime Desktop](https://i.ibb.co/spmrPW8r/Screenshot-2026-01-13-184934.png)

-------------------------- [] Docker Desktop Running the Container -------------------

![Postman Testing api](https://i.ibb.co/C5qrJ4Mm/Screenshot-2026-01-13-184818.png)

------------------------------- [] Postman Testing Api ----------------------------

This workflow i build for i showcase for i have a knowledge to how to use the ai automation tool workflow 
build ai agents.
