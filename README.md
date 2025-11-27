# ☕ coffee-sales-kpi-agents  
**Multi-Agent KPI Automation for Coffee Sales Insights**

---

## 📊 Overview
In fast-paced enterprise environments, transforming raw sales data into actionable insights is often slow, manual, and error-prone. This project tackles that challenge by building a **multi-agent system** that automates KPI analysis using a real-world **coffee sales dataset**.

Our pipeline:
- Loads and prepares the dataset  
- Computes key performance indicators (KPIs)  
- Generates human-readable summaries using **Gemini**  
- Visualizes results with charts  
- Supports **observability**, **memory**, and **deployment readiness**

---

## 🧩 Problem Statement
Traditional KPI workflows are repetitive, fragile, and hard to scale. Analysts spend hours cleaning data, calculating metrics, and preparing reports — delaying decisions and reducing agility.

Our dataset, based on coffee sales transactions, reflects this challenge. Extracting insights manually would be inefficient and inconsistent. We solve this with a modular, agent-driven system that automates the entire process.

---

## 🤖 Why Agents?
Agents bring modularity, autonomy, and scalability to enterprise data workflows. Here's why they work:

- 🧠 **Autonomy** → Each agent handles a specialized task  
- ⚙️ **Scalability** → Supports sequential, parallel, and loop execution  
- 📈 **Traceability** → Logs, metrics, and memory snapshots  
- 🔌 **Flexibility** → Easy to extend with new tools or datasets  

---

## 🏗️ What We Created
We built a **multi-agent pipeline** with four core agents:

| Agent | Role | Icon |
|-------|------|------|
| 🟧 **Agent 1: Data Loader** | Loads and prepares the dataset | 📊 |
| 🟩 **Agent 2: KPI Analyzer** | Computes metrics like total sales, missing values, top categories | 🧠 |
| 🟪 **Agent 3: LLM Summary Generator** | Uses Gemini to generate human-readable summaries | 📄 |
| 🟥 **Agent 4: Chart Generator** | Visualizes KPIs with bar charts and line graphs | 📈 |

Agents communicate using an **A2A protocol**, and the system supports **sequential**, **parallel**, and **loop** execution. We added **observability** and **memory persistence** to make the system reliable and production-ready.

---

## 🎥 Demo Modes
The pipeline runs end-to-end in three modes:

- 🔁 **Sequential Mode** → Agents pass outputs step-by-step  
- ⚡ **Parallel Mode** → KPI analysis and charting run simultaneously  
- 🔄 **Loop Mode** → KPI analysis re-runs until missing values are resolved  

Each run produces:
- ✅ KPI metrics  
- ✅ Gemini-powered summaries  
- ✅ Visual charts  
- ✅ Logs and memory snapshots

---

## 🧠 Architecture Diagram

<img width="1000" height="1000" alt="Architecture diagram" src="https://github.com/user-attachments/assets/18c4f73d-0547-400f-ba15-701882874612" />

---

## 🛠️ Technologies & Tools

| Category | Tools |
|---------|-------|
| Language | Python (Kaggle Notebook) |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Plotly |
| LLM Integration | Gemini API |
| Custom Tools | Data Loader, KPI Analyzer, Chart Generator |
| Observability | Logging, Metrics |
| Memory | State Persistence |
| Communication | A2A Protocol |
| Deployment | Production-ready pipeline |

---

## 🔐 Security Note
All API keys (e.g., Google AI Studio) are securely managed using **Kaggle Secrets**.  
No keys are hardcoded in the notebook or repository. Access is handled via environment variables like `os.environ["GOOGLE_API_KEY"]`.


---

## 🔮 If I Had More Time
- Add **OpenAPI tools** for external data access  
- Implement **context compaction** for memory optimization  
- Deploy to **Cloud Run or Docker** for real-time use  
- Extend to support **multiple datasets** and **custom KPI definitions**

---
## 📓 Kaggle Notebook
The full notebook is available on Kaggle:  
[Enterprise Agent for KPI Automation (Capstone)](https://www.kaggle.com/code/sukhmansingh333/enterprice-agent-for-kpi-automation-capstone)
---

## 👨‍💻 Author
**Sukhman Singh**  
Final-year MCA student at GNA University (Graduating 2026)  
Focused on full-stack, data science, and AI projects  
