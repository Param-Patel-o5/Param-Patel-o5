### AI/ML Engineer — LLMs · RAG Pipelines · Agentic Systems · Computer Vision

B.E. Electronics & Instrumentation + Minor in Computation & Intelligence,
BITS Pilani Hyderabad ('27). I build at the layer below the framework:
agentic pipelines, temporal RAG, and LLM diagnostic tooling from scratch.

First-author paper on vendor-agnostic LiDAR conversion under review at
*Software: Practice and Experience* (Wiley, Q2).

---

**Projects**

[TempusRAG](https://github.com/Param-Patel-o5/TempusRAG-Commitment-Intelligence-Engine)
Temporal RAG pipeline over 5 years of SEC 10-K filings. Extracts
management commitments from MD&A sections, classifies each as Delivered /
Partial / Silently Abandoned across subsequent filings using a dual-LLM
pipeline (Gemini extractor + Groq judge), and rolls results into a 0-100
executive credibility score. 100% promise-detection precision/recall,
94/94 no-LLM retrieval checks passing CI.

[Agent Failure Diagnostician](https://github.com/Param-Patel-o5/agent-failure-diagnostician)
Framework-agnostic Python library (live on PyPI) that diagnoses LLM agent
failures from JSON execution traces. Three-tier detection: rule-based
checks, semantic similarity via all-MiniLM-L6-v2, and LLM-as-judge via
Gemini. 88.3% accuracy across 60 traces, 100% on 4 of 7 detectors.
Works with LangChain, LangGraph, AutoGen, and custom formats.

[LiDAR PCAP Converter](https://github.com/Param-Patel-o5/lidar-multi-convert)
Zero-config CLI and Python library for raw PCAP conversion across 4 LiDAR
vendors (Ouster, Velodyne, Hesai, Livox). Vendor identified from 6
packet-level signals with 100% accuracy across 8 real-world outdoor
datasets. Outputs LAS, LAZ, PCD, BIN (KITTI), CSV at 2.08M points/sec.

---

**Stack**
Python · C++ · SQL · PyTorch · scikit-learn · LangChain · ChromaDB ·
sentence-transformers · OpenCV · YOLOv11 · Gemini API · Groq API

**Contact**
[LinkedIn](https://www.linkedin.com/in/param-patel-212661310/) · parampatel.005@gmail.com
