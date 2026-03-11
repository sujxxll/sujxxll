<div align="center">

# 👋 Sujal Patil - AI/ML Engineer

[![Gmail Badge](https://img.shields.io/badge/-sujal112017@gmail.com-EA4335?style=flat-square&logo=Gmail&logoColor=white)](mailto:sujal112017@gmail.com)
[![GitHub followers](https://img.shields.io/github/followers/sujxxll?logo=GitHub&style=flat-square)](https://github.com/sujxxll)

**Transforming Data into Intelligence | Building ML Solutions That Matter**

[Portfolio](#-featured-projects) • [Skills](#-tech-stack) • [Experience](#-professional-journey)

</div>

---

## 🎯 About Me

I'm an **AI/ML Engineer** passionate about developing intelligent systems that solve real-world problems. With a strong foundation in **deep learning, NLP, and data science**, I create end-to-end machine learning solutions—from research to production deployment.

### 🌟 What Drives Me:
- 🧠 **Innovation**: Exploring cutting-edge AI/ML techniques
- 📊 **Problem-Solving**: Translating business challenges into data-driven solutions
- 🚀 **Scalability**: Building production-ready ML systems
- 🤝 **Collaboration**: Contributing to open-source AI community

---

## 🛠️ Tech Stack

### 🐍 **Languages**
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat)
![SQL](https://img.shields.io/badge/-SQL-336791?logo=postgresql&logoColor=white&style=flat)

### 🤖 **ML/DL Frameworks**
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white&style=flat)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=flat)
![Scikit-learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white&style=flat)

### **AI & LLM**
![Google Gemini](https://img.shields.io/badge/-Google%20Gemini%20API-4285F4?logo=google&logoColor=white&style=flat-square)
![MCP Protocol](https://img.shields.io/badge/-Model%20Context%20Protocol-6B4CE0?style=flat-square)
![MongoDB](https://img.shields.io/badge/-MongoDB-13AA52?logo=mongodb&logoColor=white&style=flat-square)

### 📊 **Data & Visualization**
![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white&style=flat)
![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white&style=flat)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/-Seaborn-4682B4?style=flat)

### ☁️ **Cloud & DevOps**
![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=FF9900&style=flat)
![Google Cloud](https://img.shields.io/badge/-Google%20Cloud-4285F4?logo=google-cloud&logoColor=white&style=flat)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat)
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=flat)

### 🛠️ **Tools & Platforms**
- **IDEs**: VS Code, PyCharm, Jupyter Notebook
- **Databases**: MySQL, PostgreSQL, MongoDB
- **APIs**: FastAPI
- **CI/CD**: GitHub Actions

---

## 🚀 Featured Projects

### 🏥 **[Healthcare Triage & Appointment System](https://github.com/sujxxll/Hospital-chatbot)**
*AI-powered conversational healthcare assistant with symptom assessment and appointment booking*

**Tech Stack:** Python, Google Gemini 2.5 Flash, MongoDB, Gradio  
**Key Features:**
- ✅ Multi-turn symptom assessment with state machine (9 states)
- ✅ Intelligent severity classification (Critical/Moderate/Mild)
- ✅ Automated department routing (14 healthcare departments)
- ✅ Appointment booking & persistence (MongoDB)
- ✅ Emergency detection & escalation
- ✅ Real-time triage status sidebar
- ✅ Beautiful UI with custom Gradio components

**Architecture Highlights:**
- State-based conversation flow management
- LLM-powered medical intent recognition
- Structured JSON parsing for appointments
- HIPAA-compliant design patterns

**Live Impact:** Production-ready healthcare assistant with emergency handling

---

### 📊 **[TransferDocs - Student Results Analytics Platform](https://github.com/sujxxll/TransferDocs)**
*AI-driven system for automated academic result extraction, trend analysis, and natural language querying*

**Tech Stack:** Python, Google Gemini API, MongoDB, Streamlit, FastAPI, PyPDF2, Plotly  
**Key Features:**
- ✅ **Intelligent PDF Processing:** Automated extraction of student data from academic result PDFs using Google Gemini
- ✅ **Subject-wise Breakdown:** Extracts detailed subject marks, grades, and GPA information
- ✅ **Interactive Analytics Dashboard:** 
  - Pass/Fail distribution charts
  - CGPA distribution histograms
  - Class average metrics
  - Performance statistics
- ✅ **AI Chatbot for Data Queries:** Natural language interface to query student data
  - "Who got the highest marks in Physics?"
  - "List all students who failed"
  - "How much did [Student] score?"
- ✅ **MongoDB Backend:** Efficient storage and retrieval of processed data
- ✅ **Case-insensitive searches:** Regex-based MongoDB queries for flexibility

**Technical Achievements:**
- Gemini vision API for OCR and data extraction
- Gemini NLP for converting natural language → MongoDB queries
- Real-time dashboard updates with Plotly visualization
- Secure temp file handling for user uploads
- 20-minute timeout for large PDF processing

**Real-World Use Case:** Educational institutions, result analysis, student performance tracking

---

### 📚 **[FastAPI Course Management System](https://github.com/sujxxll/fastapi)**
*RESTful API for course browsing, chapter retrieval, and community ratings*

**Tech Stack:** FastAPI, MongoDB, Python, Docker  
**Key Features:**
- ✅ **Course Listing** with sorting (by date, rating, alphabetical)
- ✅ **Domain Filtering** for subject-specific course discovery
- ✅ **Chapter-level Access** with detailed content delivery
- ✅ **Community Rating System** (1-to-5 scale on courses & chapters)
- ✅ **Aggregate Ratings:** Automatic computation of course ratings from chapter ratings
- ✅ **Error Handling:** Proper HTTP status codes (404 for missing resources)
- ✅ **Comprehensive Test Suite:** 110+ test cases covering all endpoints
- ✅ **Docker Support:** Ready for containerized deployment

**API Endpoints:**
```
GET  /courses              → List all courses with filters & sorting
GET  /courses/{id}        → Get course details
GET  /courses/{id}/{ch}   → Get specific chapter content
POST /courses/{id}/{ch}   → Rate a chapter (-1, 0, 1)
```

**Test Coverage:**
- Sorting by date, rating, alphabetical order
- Domain-based filtering
- Course/chapter existence validation
- Rating aggregation logic
- Edge case handling

**Why It Matters:** Production-grade API with comprehensive testing and monitoring

---


### 🔌 **[Hybrid MCP + REST Server](https://github.com/sujxxll/MCPProject)**
*Protocol-agnostic server implementing Model Context Protocol (MCP) with REST API fallback*

**Tech Stack:** Python, Starlette, MCP Protocol, Uvicorn, SSE  
**Key Features:**
- ✅ **Dual Protocol Support:** Both MCP and REST endpoints in single server
- ✅ **Model Context Protocol (MCP):** Industry-standard LLM integration protocol
- ✅ **Server-Sent Events (SSE):** Real-time bidirectional communication
- ✅ **Shared Business Logic:** Single codebase serves both protocols
- ✅ **Tool Discovery:** Dynamic tool listing via MCP
- ✅ **CORS Enabled:** Cross-origin support for web clients
- ✅ **Deployment Ready:** Works on Render, Heroku, AWS, etc.

**Architecture Highlights:**
- Separation of concerns: Business logic, REST handlers, MCP handlers
- SSE transport for lightweight real-time communication
- Request validation with standardized JSON schemas
- Environment-based port configuration

**Innovation:** Demonstrates protocol abstraction—switch between MCP and REST without code changes

**Real-World Use Case:** LLM applications, Claude integration, tool servers, AI agents

**Example Tools:**
```
- add(a, b) → Returns a + b
- multiply(a, b) → Returns a × b
```

**REST Endpoints:**
```
POST /tools/add              → Add two numbers
POST /tools/multiply        → Multiply two numbers
GET  /health                → Server health check
```

**MCP Endpoints:**
```
GET  /sse                   → SSE transport (MCP protocol)
POST /messages              → Message handling
```

---

## 🎓 Continuous Learning

- 📖 Regular deep dives into latest ML research papers
- 🏆 Participating in ML competitions (Kaggle)
- 📚 Contributing to open-source AI projects
- 💡 Exploring emerging architectures (Transformers, Diffusion Models, etc.)

---

## 🤝 Let's Collaborate!

I'm always interested in:
- 🎯 **Innovative ML Projects** - Building something groundbreaking
- 🔍 **Data Challenges** - Solving complex analytical problems
- 📖 **Knowledge Sharing** - Mentoring and learning together
- 🌍 **Open Source** - Contributing to the AI community
- 💼 **Research Collaboration** - Exploring new ML frontiers

---

## 📫 Get In Touch

**Reach out for collaborations, opportunities, or just to chat about AI!**

| Platform | Link |
|----------|------|
| 📧 **Email** | [sujal112017@gmail.com](mailto:sujal112017@gmail.com) |
| 💼 **LinkedIn** | [linkedin.com/in/sujal-patil](https://www.linkedin.com/in/sujal-patil) |
| 🐙 **GitHub** | [github.com/sujxxll](https://github.com/sujxxll) |

---

<div align="center">

### ⭐ If you find my projects helpful, please consider giving them a star!

**Let's build the future of AI together!**

</div>
