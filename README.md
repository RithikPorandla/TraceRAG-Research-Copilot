# TraceRAG Copilot
### A Multi-Agent, Citation-Grounded Deep Research System

---

## Overview

**TraceRAG Copilot** is a multi-agent deep research system designed to perform **traceable, source-grounded web research** and generate structured, verifiable reports. Instead of returning a list of links, TraceRAG Copilot decomposes complex queries, retrieves evidence from across the web, verifies claims against sources, and synthesizes results into citation-backed outputs.

The system emphasizes **reliability, transparency, and reproducibility**, making it suitable for analytical, academic, compliance, and technical research workflows.

---

## Why TraceRAG Copilot?

Large language models can generate convincing answers, but often lack transparency around where information comes from. TraceRAG Copilot addresses this limitation by enforcing a **trace-first research workflow**, ensuring that every synthesized insight is backed by explicit source material.

TraceRAG Copilot is built for:
- Deep research requiring trustworthy citations
- Analysts and engineers conducting exploratory investigations
- Use cases where auditability and source verification matter

---

## Key Features

### 🔍 Multi-Agent Research Pipeline

TraceRAG Copilot orchestrates multiple specialized agents, each responsible for a distinct research task:

1. **Planning Agent**  
   Breaks down the user query into focused sub-questions and search strategies.

2. **Retrieval Agent**  
   Performs deep web searches and content acquisition via an MCP-powered web layer.

3. **Extraction Agent**  
   Cleans, chunks, and extracts relevant facts from retrieved content.

4. **Verification Agent**  
   Cross-validates claims against source text to reduce unsupported statements.

5. **Synthesis Agent**  
   Produces a structured research report with embedded citations.

---

### 📎 Source Traceability

- Every research output is linked to its original source
- Citations include URLs and extracted snippets
- Unsupported or weakly sourced claims are filtered or flagged

This design helps minimize hallucinations and improves trust in generated results.

---

### 🧠 Local LLM Execution

TraceRAG Copilot uses **Ollama** to run large language models locally, enabling:
- Reduced dependency on cloud LLM APIs
- Lower operational costs
- Improved privacy and control over inference

---


## Tech Stack

- **Model Context Protocol (MCP)** – structured web data access  
- **CrewAI** – multi-agent orchestration  
- **Brightdata Web MCP Server** – deep web retrieval  
- **Ollama** – local LLM inference  
- **Streamlit** – interactive user interface  




