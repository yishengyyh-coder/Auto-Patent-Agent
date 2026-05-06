# Auto-Patent-Agent
A Multi-Agent LLM framework for automating hardware engineering patent drafting.
# 🚀 Auto-Patent-Agent Framework

![Status](https://img.shields.io/badge/Status-Beta_Testing-blue)
![LLM](https://img.shields.io/badge/Powered_by-LLM_Multi--Agent-orange)

An advanced Multi-Agent framework designed to automate the extraction of core technical innovations and the drafting of engineering patents from unstructured technical disclosures.

## 🎯 Core Pain Point Solved
Engineers often spend weeks converting technical concepts into strict patent formats (Claims & Specifications). This framework uses long-chain reasoning to ensure complex hardware control logic is not lost during the drafting process.

## 🧠 Multi-Agent Architecture
This system utilizes three collaborative agents:
1. **Parser Agent**: Deep-reads unstructured docs and extracts complex hardware architecture and intervention logic.
2. **Retriever & Verify Agent**: Evaluates novelty based on extracted features and refines claim boundaries to avoid overlap with existing patents.
3. **Drafter Agent**: Generates legally compliant "Claims" and "Specifications".

## 💡 Real-world Case Study: Intelligent Car Seat Ventilation
The framework was successfully deployed to draft a patent for an intelligent car seat pulse ventilation system. 
* **Input**: Messy R&D technical disclosure.
* **Extraction Highlight**: Successfully captured highly complex control logics including **"Spatio-temporal tide synergy (时空潮汐协同)"** and **"Biomechanical irritability intervention (生物力学应激性干预)"**.
* **Result**: Reduced drafting time from 1 week to 2 days with 95%+ core technology coverage.

## 📂 Repository Structure
* `agents/`: Core logic for Parser, Retriever, and Drafter agents.
* `prompts/`: Structured prompt templates for legal compliance.
* `utils/`: Document parsing (PDF/Docx) and logging utilities.

> **Note**: Due to NDA and commercial confidentiality, the full proprietary dataset and production API keys are not included in this public repository. This repo serves as the architectural core and Proof of Concept (PoC).
