# 🚀 Project APEX

> **From Prompt to Publish.**

Project APEX is an AI-powered, prompt-driven automation platform designed to simplify and automate the YouTube Shorts creation workflow. It combines intelligent video editing, advanced voice processing, workflow orchestration, and local Large Language Models (LLMs) using Ollama to create a fully automated content creation pipeline.

The project follows a modular microservice architecture, allowing each component to work independently while communicating through a centralized workflow engine.

---

# 🌟 Vision

To build a fully local, AI-powered automation platform that enables creators to transform ideas into professional-quality YouTube Shorts using natural language prompts.

---

# 🎯 Goals

- Prompt-driven content creation
- Automated video editing
- Intelligent voice processing
- Workflow orchestration
- Local AI using Ollama
- Docker-based deployment
- Modular architecture
- Open-source development
- Extensible plugin system

---

# 🏗 Planned Architecture

```
                 Browser
                    │
                    ▼
           React Frontend
                    │
                    ▼
           FastAPI Backend
                    │
     ┌──────────────┼──────────────┐
     ▼              ▼              ▼
 Workflow      Video Engine   Voice Engine
    Engine
     │              │              │
     └──────────────┼──────────────┘
                    ▼
             Shared Workspace
                    │
                    ▼
                Ollama AI
```

---

# 📂 Project Structure

```
project-apex/

backend/
frontend/
workflow_engine/
video_engine/
voice_engine/
shared/
docker/
docs/
tests/
scripts/

README.md
LICENSE
.gitignore
docker-compose.yml
```

---

# 🛠 Technology Stack

## Backend

- FastAPI
- Python

## Frontend

- React
- TypeScript
- Tailwind CSS

## AI

- Ollama
- Qwen
- Llama
- Gemma

## Video Processing

- FFmpeg
- OpenCV
- MoviePy
- PySceneDetect

## Audio Processing

- Whisper
- Piper
- Demucs

## Infrastructure

- Docker
- Docker Compose
- Git
- GitHub

---

# 📅 Roadmap

- [x] Repository Initialization
- [ ] Development Environment
- [ ] Docker Infrastructure
- [ ] Backend API
- [ ] Frontend Dashboard
- [ ] Ollama Integration
- [ ] Workflow Engine
- [ ] Video Editing Engine
- [ ] Voice Processing Engine
- [ ] Plugin System
- [ ] Automated Pipeline
- [ ] Deployment

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Piyush Arora**

---

> 🚧 Project APEX is currently under active development.
