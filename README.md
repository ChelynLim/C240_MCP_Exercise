# C240 MCP Exercise – AI Essentials & Innovations

This repository contains **Lesson 23–24: Model Context Protocol (MCP)** from the *C240 - AI Essentials & Innovations* module at Republic Polytechnic.

---

## 📚 Overview

In this exercise, we simulate the creation of a **Minimal Python MCP Server** with three working tools, guided by the lesson slides and worksheet.

Due to GitHub Copilot Chat quota limits and unavailable `mcp[cli]` install, MCP functionality was replicated using standard Python decorators and tool simulation.

---

## 📁 Folder Structure
MCP-Lesson23-24/
├── my_mcp_server.py # MCP-like server script with all tools
├── basic_list_dir.py # Standalone script to list files in a directory
├── adv_list_dir.py # Advanced directory listing tool
├── .vscode/
│ └── mcp.json # MCP VS Code config (simulated)
└── README.md

---

## 🧪 How to Run the Exercise Locally

### ✅ Requirements

- Python 3.8+
- pip
- Internet connection (for `get_weather` tool)
- VS Code (optional)

---

### 🔧 Step-by-Step Instructions

#### 1. Clone this repo (or download the zip)
```bash
git clone https://github.com/<your-username>/MCP-Lesson23-24.git
cd MCP-Lesson23-24

Install required packages
-- pip install requests

Run the MCP-like server
-- python my_mcp_server.py

Author:
Chelyn
School of Infocomm
Republic Polytechnic
