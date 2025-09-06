# ML-OPS-Project
# AI-Powered Recruitment Agent with LangGraph & MLOps

## 📌 Project Overview
This project implements an **AI-powered recruitment automation system** using **LangGraph** for orchestration, **OpenAI** for job description generation and communication, and **open-source NLP models** for resume parsing.  
It demonstrates how **MLOps practices** (MLflow, Docker, Kubernetes, Prometheus) can be applied to build scalable, reliable, and human-in-the-loop recruitment workflows.

---

## 🚀 Features
- ✅ **Job Description Generation** using GPT models (OpenAI API)  
- ✅ **Resume Parsing** (mock parser in v1, spaCy/HuggingFace in future versions)  
- ✅ **Candidate Shortlisting** with embedding-based similarity scoring  
- ✅ **Human-in-the-loop Checkpoints** (approval of JD, interview feedback)  
- ✅ **LangGraph Workflow Orchestration** for the end-to-end hiring pipeline  
- ✅ **MLOps Integration (Planned)**: MLflow for experiment tracking, Docker & Kubernetes for deployment, Prometheus & Grafana for monitoring  

---

## 🏗️ Tech Stack
- **LangGraph / LangChain** → Orchestration of pipeline nodes  
- **OpenAI API** → JD generation, embeddings, communication  
- **spaCy / HuggingFace** → Resume parsing (future versions)  
- **MLflow** → Experiment tracking & model registry  
- **Docker + Kubernetes** → Deployment  
- **Prometheus + Grafana** → Monitoring  
- **PostgreSQL / MongoDB** → Data storage  

---

## 📂 Project Structure
