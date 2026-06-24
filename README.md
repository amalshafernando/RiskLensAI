# RiskLensAI
An Agentic Document-Intelligence MVP for Automated Financial Risk Assessment



## 🚀 Project Overview
This project serves as a portfolio piece demonstrating end-to-end development of agentic AI systems. It solves the manual bottleneck in financial risk analysis by using an orchestrated multi-agent workflow.

## 🏗️ Architecture
The system follows a modular architecture:

Extraction Layer: Uses pdfplumber and LLMs to structure unstructured PDF data.

Deterministic Engine: Python-based logic for accurate calculation of financial ratios (Liquidity, Leverage, Profitability).

Agentic Orchestration: Managed via LangGraph to coordinate between Analyst and QA agents.

Human-in-the-loop: Analyst-led review and sign-off process before final delivery.

RAG Chat: Provides document-grounded insights for analysts.

## 🛠️ Tech Stack
Core Language: Python 3.11

Agent Framework: LangGraph

LLM: Anthropic Claude (via API)

Document Processing: pdfplumber

UI: Streamlit

Monitoring: Audit logs for human-in-the-loop approvals

## 📋 Build Plan (1-Day MVP)
Setup: Environment, GitHub repository, and API credentials.

Data Prep: Creating synthetic financial statements for testing.

Logic: Implementing the deterministic Python Ratio Engine.

Orchestration: Building the LangGraph multi-agent pipeline.

Interface: Creating the Streamlit dashboard for analysts.

Delivery: Verification and demo preparation.

## 🚀 How to Run
Clone the repository: git clone [repository-url]

Install dependencies: pip install -r requirements.txt

Set your API keys in the .env file.

Run the application: streamlit run app.py