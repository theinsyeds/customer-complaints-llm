# 🧠 Customer Complaints Analyzer (LangChain + Ollama)

A lightweight local LLM-powered app that analyzes customer complaint emails to extract insights — such as which **product category** and **store location** have the most negative sentiment.

> ⚡ Built from scratch by [theinsyeds](https://github.com/theinsyeds) as part of NVIDIA’s **[Building LLM Applications Using Prompt Engineering](https://resources.nvidia.com/en-us-event-slides/free-courses)** course.

---

## 📂 Project Structure

```
customer-complaints-llm/
│
├── data/                       # Optional input/output files (emails, results)
├── notebook/                   # Main Jupyter notebook
│   └── customer_complaints_llm.ipynb
├── utils/                      # Custom Python helper modules (optional)
├── requirements.txt            # Full frozen environment
├── requirements-minimal.txt    # Minimal install for quick setup
├── .env                        # API keys or config (if needed)
├── .gitignore                  # Ignored files/folders
├── LICENSE                     # MIT License
└── README.md                   # This file
```

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/customer-complaints-llm.git
cd customer-complaints-llm
```

### 2. Set up a virtual environment (optional but recommended)

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

For a quick setup:

```bash
pip install -r requirements-minimal.txt
```

If you want to replicate the exact dev environment:

```bash
pip install -r requirements.txt
```

---

## 🤖 Running Ollama Locally

Make sure you’ve installed [Ollama](https://ollama.com/). Then:

```bash
ollama serve
ollama pull mistral
```

---

## 📒 Run the Notebook

```bash
jupyter notebook
```

Then open:

```
notebook/customer_complaints_llm.ipynb
```

Start running cells top to bottom — all code is explained with markdowns and step-by-step guidance.

---

## 🔍 Features

- 📩 Accepts raw customer complaint emails
- 🧠 Uses LangChain with **Ollama (Mistral model)** — fully local
- 📊 Extracts:
  - Product category with most negative sentiment
  - Location/store with most negative sentiment
- 🛠️ Designed for terminal-based workflow
- 🧾 Option to expand with file input/output, charts, tagging, etc.

---

## 💡 Potential Enhancements

- Save outputs to a CSV/JSON
- Visualize complaint categories using `matplotlib` or `plotly`
- Allow filtering by sentiment or keyword
- Turn this into a Streamlit or Gradio mini-app

---

## ✍️ Credits

Based on the **[Building LLM Applications Using Prompt Engineering](https://resources.nvidia.com/en-us-event-slides/free-courses)** course by NVIDIA — this project expands the final assessment into a fully reusable LangChain + Ollama notebook.

---

## 🎓 Certification

**Course:** [Building LLM Applications with Prompt Engineering]([https://resources.nvidia.com/en-us-event-slides/free-courses](https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+S-FX-12+V2))  
**Issued by:** NVIDIA Deep Learning Institute (DLI)  
**Credential ID:** `eF435zqHRKij0xo7MFTl3w`  
**Issued On:** June 18, 2025  
**Certificate:** [View Credential →](https://learn.nvidia.com/certificates?id=eF435zqHRKij0xo7MFTl3w)

---

## 📜 License

This project is open source under the terms of the [MIT License](./LICENSE).
