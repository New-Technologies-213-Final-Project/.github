# MCP Integrated Local LLM Chat Application

## Overview

### About the project

- This is the final project of the "Modern Software Development Technologies" course taught in **Ho Chi Minh University of Science**. For more details about the project, please take a look at the `project_description.pdf` file in the `.github` repository.
- Learning period: 2nd semester of 2024 - 2025.
- Theory lecturer: Mr. Tran Van Quy.
- Practice instructor: Mr. Do Nguyen Kha.

### Team members

| Student id | Full name         |
| ---------- | ----------------- |
| 21120542   | Lam Hoang Quoc    |
| 21120544   | Le Minh Sang      |
| 21120581   | Le Phan Thuy Truc |
| 21120589   | Truong Anh Tuan   |

## Project structure

Due to its complexity, the project is divided into 5 layers. To avoid dependencies and conflicts when working in groups, each layer will be organized as an independent GitHub repository.

```
New Technologies 213 - Final Project/  # Github organization
├─ fe/                                 # Frontend layer - Github repository
├─ be/                                 # Backend layer - Github repository
├─ data/                               # Data used in the project - Github repository
├─ api_log/                            # Project log storage - Github repository
├─ mcp_server/                         # MCP Server layer - Github repository
└─ .github/                            # Project information - Github repository
```

## Technical Stack

- Frontend: React with Vite and Tailwind.
- Backend: Python with Uvicorn
- MCP Server: Python MCP SDK
- Database: MySQL & PostgreSQL

## Implemented Features

- **Chat Interface:** Accepts natural language questions from users.
- **Local LLM Processing:** Uses a local language model (e.g., **llama.cpp**, **Ollama**) running on a CPU (no GPU required).
- **File Content Search:** Searches through folders containing documents (**PDF**, **Word**, **PowerPoint**, **Excel**, etc.).
- **File Classification:** Automatically labels files based on content (e.g., **Group A**, **B**, **Marketing**, **HR**, etc.).
- **Metadata Upload:** Sends file metadata (**name**, **label**, **summary**) to the **MCP Cloud API**.
- **Chat-based Results:** Displays search results directly in the chat interface.
- **Offline Operation:** Entirely offline system, runs on CPU with a minimum of **8GB RAM**.
- **Vietnamese Language Support:** Supports queries in **Vietnamese** through the chat interface.
- **Multi-format File Handling:** Supports various file types (**PDF**, **Word**, **Excel**, etc.).
- **Agentic AI:** The AI can plan and execute multi-step reasoning instead of only responding to one question at a time.
- **Chain of Thought:** The AI explains its reasoning process to increase transparency and trust.
- **RLHF (Reinforcement Learning from Human Feedback):** Captures user feedback to improve future results without retraining the model.
- **Cross-document Comparison:** Able to compare content across multiple documents (e.g., comparing strategies between **2023** and **2024**).
- **Role-based Access Control:** Restricts access to sensitive data by role (e.g., **HR**, **Accounting**, **Manager**).
- **Editable Labels:** Allows users to manually correct file labels if the AI misclassifies them.
- **Report Generation:** Generates and exports reports (**PDF**, **Excel**) from extracted data.
- **Query & Metadata Logging:** Logs user queries and file metadata for internal analytics or future reuse.

## Demo

- Installation instructor: https://youtu.be/rv3ETFVHgyk?si=5yqf4pqzW23ifVj_
- Features demo: https://youtu.be/xqA2vl4Krx0

## Usage

Please check each layer's repository for more details on running the project locally.

## Preferences

- MCP Theory: https://www.youtube.com/watch?v=6rDUTy87Xxg
- Using MCP with Claude Desktop: https://www.youtube.com/watch?v=ToOEOEcmtPM&t=1395s
