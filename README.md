# coffee-sales-kpi-agents
Multi-Agent KPI Automation for Coffee Sales Insights

# 📊 Multi-Agent KPI Automation for Coffee Sales Insights

## 🔹 Overview
This project demonstrates how autonomous agents can automate KPI analysis for enterprise datasets.  
Using a **coffee sales dataset**, we built a **multi-agent pipeline** that loads data, computes KPIs, generates LLM-powered summaries, and visualizes results — all with observability, memory, and deployment support.

---

## 🧩 Problem Statement
In enterprise settings, transforming raw sales data into actionable insights is often slow, manual, and error-prone. Analysts spend hours cleaning data, calculating KPIs, and generating reports — a process that’s repetitive, fragile, and hard to scale.  
Our dataset, based on coffee sales transactions, reflects this challenge: it contains valuable information, but extracting insights manually would be inefficient and inconsistent.

---

## 🤖 Why Agents?
Agents are the right solution because they bring:
- **Autonomy** → Each agent specializes in a task.  
- **Scalability** → Supports sequential, parallel, and loop execution.  
- **Traceability** → Observability (logs, metrics) and memory persistence.  
- **Flexibility** → Easy to extend with new tools or datasets.  

---

## 🏗️ What We Created
We designed a **multi-agent system** with four core agents:

- **Agent 1: Data Loader** → Loads and prepares the dataset.  
- **Agent 2: KPI Analyzer** → Computes metrics like total sales, missing values, top categories.  
- **Agent 3: LLM Summary Generator** → Uses Gemini to generate human-readable summaries.  
- **Agent 4: Chart Generator** → Visualizes KPIs with bar charts and line graphs.  

Agents communicate using an **A2A protocol**, and the pipeline supports **sequential, parallel, and loop execution**.  
We added **observability (logging, metrics)** and **memory (state persistence)** to make the system reliable and production-ready.

---

## 🎥 Demo
The pipeline runs end-to-end in three modes:
- **Sequential mode** → Agents pass outputs step-by-step.  
- **Parallel mode** → KPI analysis and charting run simultaneously.  
- **Loop mode** → KPI analysis re-runs until missing values are resolved.  

Outputs include:
- KPIs (e.g., total sales, missing values)  
- LLM summaries (Gemini-powered)  
- Visual charts (bar/line graphs)  
- Logs and memory snapshots  


<img width="1344" height="768" alt="thumbnail" src="https://github.com/user-attachments/assets/fb5b81cb-b407-4348-860b-1532863f7a67" />


---

## 🛠️ The Build
**Technologies & Tools:**
- Python (Kaggle Notebook)  
- Pandas, NumPy → Data processing  
- Matplotlib, Plotly → Chart generation  
- Gemini API → LLM summaries  
- Custom tools → Data loader, KPI analyzer, chart generator  
- Memory store → Persist KPIs and summaries  
- Logging & metrics → Observability  
- A2A protocol → Agent-to-agent communication  
- Deployment pipeline → Run in production-like mode  

---

## 📂 Project Structure
