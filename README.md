# 🧭 Blockchain-Based Information System for Trustworthy and Sustainable Supply Chains

This project develops a **transparent, verifiable, and trustworthy information system** that leverages **blockchain technology and open data** to strengthen **trust and sustainability** in global supply chains.  

The prototype captures and visualizes key events across the entire supply chain — from production to delivery — while ensuring the **integrity, authenticity, and immutability** of each transaction through blockchain anchoring.  

---

## 🚀 Project Overview

Modern supply chains often lack visibility and verifiable data integrity.  
This system demonstrates how **blockchain** and **open data** can enhance transparency, traceability, and sustainability by providing **a tamper-proof record** of supply chain events.  

Each event (e.g., production, transport, inspection, or delivery) is hashed and stored on a simulated blockchain to ensure trust and integrity across all stakeholders.  

---

## 🔧 Core Features

| Category | Description |
|-----------|--------------|
| 🌐 **Open Data Integration** | Combines datasets from Open Supply Hub, ESG reports, or synthetic CSV/JSON samples |
| 🔗 **Blockchain Simulation** | Implemented via Ethereum (Hardhat / Ganache) and `web3.py` |
| 🧮 **Data Modeling** | PostgreSQL or Neo4j Graph DB — Product → Batch → Facility → Event |
| ✅ **Data Validation** | Data quality checks using *Great Expectations* |
| 📊 **Interactive Dashboard** | Streamlit or Plotly Dash with Leaflet.js map visualizations |
| ♻️ **Sustainability KPIs** | Track CO₂ emissions, transport distances, traceability ratio |

---

## 🧠 System Architecture

```text
1️⃣  Data Sources
     ↓
2️⃣  Data Ingestion & Modeling (Python, Pandas)
     ↓
3️⃣  Blockchain Anchoring (Smart Contract + SHA-256 Hash)
     ↓
4️⃣  Validation & Trust Metrics (Great Expectations)
     ↓
5️⃣  Visualization (Streamlit + Leaflet)
