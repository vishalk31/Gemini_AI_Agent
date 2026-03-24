# 🤖 Building AI Agents with Gemini

A hands-on project to build AI agents using the Gemini model — starting from simple API calls to MCP (Model Context Protocol) servers, and advancing to tools and agents using LangChain.

---

## 🚀 Overview

This repository walks through the evolution of AI agent development:

1. 🔹 Basic Gemini API usage
2. 🔹 Tool calling with custom APIs
3. 🔹 Building a simple MCP-style server
4. 🔹 Connecting Gemini with external tools
5. 🔹 Creating agents using LangChain

---

## 🧠 Tech Stack

* Python 🐍
* Gemini API (Google Generative AI)
* FastAPI (for MCP server)
* LangChain
* Requests

---

## 📁 Project Structure

```
.
├── mcp_server.py        # Simple MCP-style tool server
├── agent.py             # Gemini tool-calling agent
├── requirements.txt     # Dependencies
└── README.md
```

---

## ⚙️ Setup

### 1. Clone the repo

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 3. Set your Gemini API Key

```bash
export GOOGLE_API_KEY="your_api_key_here"
```

(For Windows)

```bash
set GOOGLE_API_KEY=your_api_key_here
```

---

## ▶️ Run the MCP Server

```bash
uvicorn mcp_server:app --port 8000
```

---

## 🤖 Run the Agent

```bash
python agent.py
```

---

## 🧩 Example

Input:

```
add 5 and 7
```

Output:

```
12
```

---

## 🔗 Features

* ✅ Simple MCP-style server
* ✅ Gemini-powered reasoning
* ✅ Tool calling loop
* ✅ Extendable architecture
* ✅ Beginner-friendly

---

## 🚧 Future Improvements

* Add proper MCP protocol support
* Streaming responses
* Multi-tool agents
* Memory (Redis / vector DB)
* UI interface (Streamlit / React)

---

## 📚 Learnings

* How LLMs interact with external tools
* Building your own agent loop
* Designing scalable AI systems
* Understanding MCP architecture

---

## 🙌 Contributing

Feel free to fork, improve, and submit PRs!

---

## ⭐ Support

If you found this helpful, give it a ⭐ on GitHub!
