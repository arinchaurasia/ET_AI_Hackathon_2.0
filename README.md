# 🛡️ VentiGuard AI: AI-Powered Industrial Safety Intelligence

> **ET AI Hackathon 2026 Submission**
> **Theme:** Industrial Intelligence / Worker Safety / Geospatial Safety Analytics[cite: 1]
> **Problem Statement 1:** AI-Powered Industrial Safety Intelligence for Zero-Harm Operations[cite: 1]

## 🚨 The Problem: The Cost of Disconnected Data
India's heavy industrial sector suffers from a devastating context deficit[cite: 1, 2]. In major fatal incidents—such as the Visakhapatnam Steel Plant explosion—functioning SCADA systems and gas detectors existed, but the data was unacted upon because there was no intelligence layer connecting sensor readings to operational decisions in time[cite: 1]. 

Legacy control rooms blast over **500+ simultaneous alarms** during peak incidents[cite: 2]. Operators suffer from severe cognitive overload, resulting in a fatal **3–8 minute response delay** because raw data (`CO_LVL2: 450ppm`) tells them *what* broke, but never *how* to resolve it[cite: 2].

## 💡 The Solution: Unified Predictive Intelligence
VentiGuard AI is an **AI-powered Industrial Safety Intelligence platform** that brings together data from IoT sensors, digital permit-to-work logs, and shift records into a single predictive layer[cite: 1]. We replace raw sensor chaos with an intelligent, morphing Human-Machine Interface (HMI) that triggers preemptive interventions *before* an incident becomes fatal[cite: 1, 2].

---

## ✨ Core AI & Hackathon Features

### 🧠 Compound Risk Detection Engine
Detects compound risk conditions that no single sensor would flag alone[cite: 1]. By correlating real-time gas sensor readings with active digital work permits, VentiGuard AI identifies dangerous combinations (e.g., confined space entry during abnormal process conditions) hours before they escalate to critical levels[cite: 1].

### 🗺️ Geospatial Safety Heatmap
A real-time, interactive SVG geospatial layer mapped over the mine/plant layout[cite: 1, 2]. It dynamically visualizes risk zones as environmental conditions change, integrating hazardous area classifications and active crew locations to give safety officers total situational awareness[cite: 1, 2].

### 🚨 Autonomous Emergency Response Orchestrator
On a confirmed trigger, this agent reduces the critical first 10 minutes of chaos to under 60 seconds[cite: 1, 2]. It translates raw telemetry into plain-English **Narrative Alarms** (e.g., *"Evacuate Sector D"*), initiates automated fan overrides, and preserves sensor evidence for regulatory audits[cite: 1, 2].

### ⚖️ Regulatory Compliance Agent
Ensures that all automatically generated resolution playbooks and digital SOPs reference and comply with statutory frameworks like the **DGMS (Directorate General of Mines Safety)** and the Factory Act[cite: 1].

### 👁️ Morphing UI (Anti-Alarm Fatigue)
During a crisis, VentiGuard AI's interface physically morphs. Non-critical panels blur and recede, reducing visual noise by 80% to lock the operator's focus exclusively onto the hazard zone[cite: 2].

---

## 🛠️ Technical Architecture

Built for high-performance, real-time industrial resilience[cite: 2].

*   **Presentation Layer:** `React 18`, `Framer Motion`, `Dynamic SVG` (Powers the morphing UI and geospatial heatmap)[cite: 1, 2].
*   **Intelligence Layer:** `Node.js` Multi-Agent Engine (Translates telemetry & permit logs into predictive, plain-English SOPs)[cite: 1, 2].
*   **Real-Time Transport:** `Socket.io` & `WebSockets` (Guarantees sub-100ms end-to-end latency for 200+ concurrent sensors, with automatic millisecond reconnection)[cite: 2].
*   **Data Layer:** Time-Series DB, REST API (Persistent sensor logs, DGMS audit trails, SOP state management)[cite: 1, 2].

---

## 📈 Business Impact & Sustainability

*   **40% Energy Cost Reduction:** Powered by our **Ventilation on Demand (VoD)** framework, the AI dynamically adjusts fan speeds based on real-time occupancy and risk zones, eliminating wasteful constant-power ventilation[cite: 1, 2].
*   **3× Faster Incident Response:** Narrative-guided playbooks eliminate manual data translation and operational hesitation[cite: 2].
*   **100% Audit Trail Coverage:** Every alert, operator action, and system override is timestamped for seamless regulatory compliance and post-incident investigation[cite: 2].

---

## 💻 Local Setup & Installation

1. **Clone the repository:**
```bash
   git clone https://github.com/arinchaurasia/ventiguard-ai.git
   cd ventiguard-ai
   