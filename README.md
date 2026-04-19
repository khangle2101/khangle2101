## Le Hoang Khang

AI Engineer focused on **Prompt Engineering**, **RAG pipelines**, and **LLM application development** — building evaluation-driven AI systems from design to deployment.

B.Eng. in Automation & Control Engineering Technology (HCMUTE) | GPA: 3.4/4.0

<p>
  <a href="https://github.com/khangle2101">
    <img alt="GitHub" src="https://img.shields.io/badge/GitHub-khangle2101-111?style=for-the-badge&logo=github" />
  </a>
  <a href="https://www.linkedin.com/in/khang-le-hoang-b8b0a23a9/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Khang%20Le%20Hoang-0A66C2?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="https://youtube.com/@hoangkhangle-uk6fj?si=zQQC2pu4hF5mEKQ0">
    <img alt="YouTube" src="https://img.shields.io/badge/YouTube-Demos-FF0000?style=for-the-badge&logo=youtube" />
  </a>
  <a href="mailto:khanglehoang.work@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-khanglehoang.work%40gmail.com-0B7285?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

### What I Do

- **Prompt Engineering** — Design specialized prompts (system/role, structured JSON output, temperature tuning, context grounding) and iterate based on evaluation metrics
- **RAG Pipeline Development** — Build end-to-end retrieval-augmented generation systems: semantic chunking, query rewriting, multi-query retrieval, LLM re-ranking
- **LLM Integration** — OpenAI/OpenRouter APIs, LangChain, streaming, Pydantic structured outputs, cost-aware model selection
- **Edge AI & Computer Vision** — Real-time detection on constrained hardware (Jetson Nano, TensorRT)

### Tech Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-10a37f?style=flat-square&logo=openai&logoColor=white" />
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-1c3c3c?style=flat-square" />
  <img alt="ChromaDB" src="https://img.shields.io/badge/ChromaDB-brightgreen?style=flat-square" />
  <img alt="Pydantic" src="https://img.shields.io/badge/Pydantic-e92063?style=flat-square&logo=pydantic&logoColor=white" />
  <img alt="Gradio" src="https://img.shields.io/badge/Gradio-F97316?style=flat-square" />
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img alt="TensorRT" src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img alt="SQL" src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

---

## Featured Projects

### Advanced RAG Knowledge Assistant

> Prompt Engineering | RAG | LLM APIs | Evaluation-Driven Development

- Designed **4 specialized prompts** (chunking, rewriting, re-ranking, answer generation) with per-task temperature tuning and structured JSON output
- Achieved **MRR 0.929, Accuracy 4.79/5** — a **+24.8% improvement** over a LangChain baseline
- Implemented cost-aware model selection, context grounding, streaming chat, and incremental document management
- Benchmarked with 150 test questions using MRR, nDCG, keyword coverage, and LLM-as-judge scoring

Repo: [advanced-rag-chatbot](https://github.com/khangle2101/advanced-rag-chatbot) | [Demo Video](https://www.youtube.com/watch?v=o2GRJSOT7Yo)

### AI-Powered Customer Feedback Automation

> AI Classification | REST APIs | Workflow Automation

- End-to-end automation processing customer feedback with AI-powered sentiment analysis and categorization (OpenRouter)
- Integrated Google Apps Script, n8n, Telegram Bot via REST APIs and webhooks
- < 5 seconds processing time per submission with logging, retry logic, and status tracking

Repo: [feedback-automation-ai](https://github.com/khangle2101/feedback-automation-ai)

### Real-Time Fire & Smoke Detection Drone (Edge AI)

> Computer Vision | TensorRT | Jetson Nano | MAVLink

- Two-stage cascaded detection (smoke → fire confirmation) to reduce false positives
- Jetson Nano deployment with TensorRT FP16; 10+ FPS inference
- Data fusion: detections + Pixhawk telemetry for geo-tagged alerts + autonomous LOITER

Repo: [Real-Time-Fire-Smoke-Detection-Drone](https://github.com/khangle2101/Real-Time-Fire-Smoke-Detection-Drone)

### SCARA 3-DOF Robot Arm — Color Sorting (Vision + Kinematics)

> Computer Vision | Robotics | MATLAB

- HSV segmentation + calibration (pixel → mm) for pick coordinates
- MATLAB forward/inverse kinematics, Arduino stepper control
- Includes Unknown rejection case to avoid misclassification

Repo: [SCARA-Color-Sorting](https://github.com/khangle2101/Application-of-Image-Processing-and-3-DOF-SCARA-Robotic-Arm-in-Object-Classification-Based-on-Color)
