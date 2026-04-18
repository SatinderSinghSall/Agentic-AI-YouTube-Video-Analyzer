# AI / ML: Agentic AI

---

# 🎥 AI YouTube Video Analyzer

### Agentic AI System for Structured Video Understanding.

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![Groq](https://img.shields.io/badge/Groq-LLM-green)
![Agentic AI](https://img.shields.io/badge/Agentic-AI-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)

</p>

<p align="center">
An <b>Agentic AI-powered application</b> that analyzes YouTube videos and generates structured summaries, timestamps, and key insights using <b>LLM reasoning and tool usage</b>.
</p>

---

# 📌 Project Overview

The **AI YouTube Video Analyzer** is an **Agentic AI application** designed to transform unstructured video content into **structured, searchable knowledge**.

Using **Large Language Models (LLMs)** and **tool-based agents**, the system automatically:

- Extracts video metadata
- Segments content into meaningful sections
- Generates timestamped summaries
- Identifies key concepts and demonstrations

This project demonstrates **modern AI engineering patterns**, including:

- **Agent-based architectures**
- **Tool-augmented LLM reasoning**
- **AI-driven content analysis**
- **Interactive ML applications**

---

# 🚀 Key Features

### 🎥 Automated Video Analysis

Provide any YouTube link and receive a structured analysis of the video.

### ⏱ Intelligent Timestamp Generation

Breaks long videos into **semantic segments with summaries**.

### 🧠 LLM-powered Understanding

Uses **Groq-hosted Llama-3.3-70B** for deep contextual reasoning.

### 📚 Multi-Domain Content Support

| Content Type          | Supported |
| --------------------- | --------- |
| Programming Tutorials | ✅        |
| Academic Lectures     | ✅        |
| Tech Reviews          | ✅        |
| Creative Tutorials    | ✅        |
| Educational Videos    | ✅        |

### 🖥 Interactive Web Interface

Built with **Streamlit** for simple and intuitive usage.

---

# 🧠 System Architecture

```text
              ┌──────────────────────────┐
              │        User Input        │
              │   YouTube Video URL      │
              └─────────────┬────────────┘
                            │
                            ▼
                ┌────────────────────┐
                │   Streamlit UI     │
                │   (ui.py)          │
                └─────────┬──────────┘
                          │
                          ▼
              ┌───────────────────────────┐
              │     Agentic AI System     │
              │   (youtube_analyzer.py)   │
              └───────────┬───────────────┘
                          │
        ┌─────────────────┴─────────────────┐
        ▼                                   ▼
┌─────────────────┐              ┌──────────────────┐
│  YouTube Tools  │              │   Groq LLM       │
│ (Metadata +     │              │ Llama 3.3 70B    │
│ Video Content)  │              │ Reasoning Engine │
└────────┬────────┘              └─────────┬────────┘
         │                                  │
         └──────────────┬───────────────────┘
                        ▼
            ┌────────────────────────┐
            │ Structured Video Report│
            │ Timestamps + Insights  │
            └─────────────┬──────────┘
                          ▼
                 Displayed in UI
```

---

# 🖼 Demo

### Application Interface

<img width="900" alt="demo_ui" src="docs/demo_ui.png">

---

### Example Output

```
📚 Video Overview
Length: 18 minutes
Type: Python Tutorial

⏱ Timestamp Breakdown

[00:00 - 02:15]
Introduction to Python and environment setup.

[02:16 - 07:40]
Installing Python and configuring IDE.

[07:41 - 12:30]
Writing the first Python program.

[12:31 - 18:10]
Understanding variables and data types.
```

---

# 🎬 Demo GIF

<p align="center">
<img src="docs/demo.gif" width="800">
</p>

_(You can record this using ScreenToGif or OBS and place it inside a `/docs` folder.)_

---

# 🧰 Technology Stack

| Component              | Technology    |
| ---------------------- | ------------- |
| Programming Language   | Python        |
| UI Framework           | Streamlit     |
| LLM Provider           | Groq          |
| Model                  | Llama-3.3-70B |
| Agent Framework        | Agno          |
| Video Tools            | YouTubeTools  |
| Environment Management | python-dotenv |

---

# 📂 Project Structure

```
Video Analyzer
│
├── .gitignore
├── README.md
│
├── ui.py
│   └── Streamlit interface for user interaction
│
├── youtube_analyzer.py
│   └── Agent configuration and analysis pipeline
│
└── docs
    ├── demo_ui.png
    └── demo.gif
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/youtube-video-analyzer.git
cd youtube-video-analyzer
```

---

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Mac / Linux**

```bash
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install streamlit python-dotenv agno
```

---

## 4️⃣ Configure Environment Variables

Create `.env` file:

```
GROQ_API_KEY=your_groq_api_key
```

You can obtain the key from:

https://console.groq.com

---

# ▶️ Running the Application

Start the Streamlit server:

```bash
python -m streamlit run ui.py
```

Open in browser:

```
http://localhost:8501
```

---

# 🧪 Example Use Cases

### 📚 Educational Content

Create structured **study guides from lectures**.

### 💻 Programming Tutorials

Extract **code explanations and practical demonstrations**.

### 📱 Tech Reviews

Identify **features, benchmarks, and comparisons**.

### 🎨 Creative Tutorials

Break down **art or DIY workflows step-by-step**.

---

# 🔬 AI Engineering Concepts Demonstrated

This project demonstrates several **modern AI system design concepts**:

- Agentic AI architecture
- Tool-augmented LLM workflows
- LLM orchestration
- Structured knowledge extraction
- Interactive AI applications

These are **key skills sought by AI/ML recruiters and AI product teams**.

---

# 🔮 Future Improvements

- 🎙 Automatic speech transcription
- 📊 Knowledge graph extraction
- 📥 Export summaries as PDF
- 📚 Playlist analysis
- 🧠 Multi-agent analysis pipeline

---

# 🤝 Contributing

Contributions are welcome.

1. Fork repository
2. Create feature branch

```
git checkout -b feature/new-feature
```

3. Commit changes

```
git commit -m "Add new feature"
```

4. Push branch and create Pull Request.

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👤 Author

**Satinder Singh Sall**

AI / Machine Learning Developer
Focused on **Agentic AI, LLM Applications, and Intelligent Systems**

GitHub:
https://github.com/SatinderSinghSall

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository
🍴 Fork the project
📢 Share with others

---

# 🎥 AI YouTube Video Analyzer

---

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![LLM](https://img.shields.io/badge/LLM-Groq%20%7C%20OpenAI-green)
![Framework](https://img.shields.io/badge/Framework-Agno-orange)
![UI](https://img.shields.io/badge/UI-Streamlit-red)
![Database](https://img.shields.io/badge/Database-SQLite-lightgrey)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

---

# 🎥 AI YouTube Video Analyzer

An **AI-powered YouTube Video Analyzer** built using **Agentic AI, Groq LLM, and Streamlit**.
This tool analyzes any YouTube video and automatically generates a **structured breakdown with timestamps, summaries, and key insights**.

It is especially useful for:

- 📚 Students analyzing lectures
- 💻 Developers studying tutorials
- 📱 Tech enthusiasts reviewing product videos
- 🎨 Creators studying creative workflows

---

# 🚀 Features

✅ **Automatic Video Analysis**
Provide any YouTube video URL and the AI will analyze the content.

✅ **Smart Timestamp Generation**
Breaks the video into meaningful sections with timestamps.

✅ **Structured Content Breakdown**

- Video overview
- Topic segmentation
- Key learning points
- Practical demonstrations

✅ **Multiple Content Types Supported**

- 📚 Educational lectures
- 💻 Programming tutorials
- 📱 Tech reviews
- 🎮 Gaming videos
- 🎨 Creative content

✅ **Interactive UI with Streamlit**

---

# 🧠 Tech Stack

- **Python**
- **Streamlit** – UI framework
- **Groq LLM (Llama 3.3 70B)** – Language model
- **Agno Agent Framework** – Agentic AI system
- **YouTube Tools (Agno)** – Extracts video data
- **dotenv** – Environment variable management

---

# 📂 Project Structure

```
Video Analyzer
│
├── .gitignore
├── README.md
├── ui.py                 # Streamlit user interface
└── youtube_analyzer.py   # AI agent setup and analysis logic
```

---

# ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/youtube-video-analyzer.git
cd youtube-video-analyzer
```

---

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Mac / Linux**

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install streamlit python-dotenv agno
```

---

### 4️⃣ Setup Environment Variables

Create a **`.env`** file in the project root.

```
GROQ_API_KEY=your_groq_api_key_here
```

You can get a key from:
👉 https://console.groq.com

---

# ▶️ Running the Application

Run the Streamlit app:

```bash
python -m streamlit run ui.py
```

Then open the browser at:

```
http://localhost:8501
```

---

# 🧪 How It Works

1️⃣ User enters a **YouTube video URL**
2️⃣ The **Agentic AI system** processes the video
3️⃣ The **Groq LLM analyzes the content**
4️⃣ The system generates:

- Video overview
- Timestamp breakdown
- Topic summaries
- Key insights

---

# 📊 Example Output

```
📚 Video Overview
Length: 18 minutes
Type: Python Tutorial

⏱ Timestamp Breakdown

[00:00 - 02:15]
Introduction to Python and setup.

[02:16 - 07:40]
Installing Python and IDE configuration.

[07:41 - 12:30]
Writing the first Python program.

[12:31 - 18:10]
Understanding variables and data types.
```

---

# 🎯 Use Cases

- Learn faster from long YouTube tutorials
- Generate **study guides automatically**
- Summarize **technical talks**
- Extract **key insights from reviews**
- Create **structured notes from lectures**

---

# 🔮 Future Improvements

- 🔊 Audio transcription support
- 📊 Video summarization charts
- 🧠 Multi-video playlist analysis
- 📥 Export notes as **PDF / Markdown**
- 📑 Save timestamp summaries

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push and open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you find this project useful:

⭐ Star the repository
🍴 Fork it
🧑‍💻 Share it with others
