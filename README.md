<div align="center">
  <h1>Param Patel</h1>
  <p><strong>AI & Platform Systems Engineer · BITS Pilani, Hyderabad ('27)</strong></p>
  <p><i>I build the plumbing underneath AI applications—making agents debuggable, RAG systems accurate, and data pipelines fast.</i></p>

  <p>
    <a href="https://param-dev.vercel.app/">
      <img src="https://img.shields.io/badge/Portfolio-param--dev.vercel.app-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
    </a>
    <a href="https://www.linkedin.com/in/param-patel-o5/">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:parampatel.005@gmail.com">
      <img src="https://img.shields.io/badge/Email-parampatel.005%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://pypi.org/">
      <img src="https://img.shields.io/badge/PyPI-2_Published_Packages-3775A9?style=for-the-badge&logo=pypi&logoColor=white" alt="PyPI" />
    </a>
  </p>
</div>

---

### ⚡ Quick Snapshot

<pre>
<b>Role Target</b>   : AI Engineer / Applied AI & Platform Systems Engineer
<b>Education</b>     : B.E. Electronics & Instrumentation + Minor in Computation & Intelligence @ BITS Pilani ('27)
<b>Core Focus</b>    : Agentic Reliability · Hybrid RAG Engines · High-Throughput C++/Python Systems
<b>Philosophy</b>    : "Anyone can chain an LLM prompt. Real engineering starts when the agent loops, the API rate-limits, or latency spikes."
<b>Off-Screen</b>    : High-altitude Himalayan trekking & Desi Dand conditioning
</pre>

---

### 🛠️ Production Systems & Open-Source Libraries

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🕵️‍♂️ <a href="https://github.com/Param-Patel-o5">Agent Failure Diagnostician</a></h3>
      <p><strong>Open-Source Python Library (Published on PyPI)</strong></p>
      <p>Multi-agent workflows fail silently in production. I built a plug-and-play debugging library that inspects execution traces from <strong>LangChain, LangGraph, and AutoGen</strong> to pinpoint why an agent looped, hallucinated, or dropped state.</p>
      <ul>
        <li><strong>Zero-Cost First Pass:</strong> Catches 60% of trace failures using fast deterministic rules ($0 API cost) before calling an LLM judge.</li>
        <li><strong>Accuracy:</strong> <strong>88.3% diagnostic accuracy</strong> across 7 failure detectors and 60 benchmark traces.</li>
        <li><strong>Framework-Agnostic:</strong> Custom Pydantic trace ingestion that avoids vendor lock-in.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>📊 <a href="https://github.com/Param-Patel-o5">TempusRAG</a></h3>
      <p><strong>Temporal Financial AI Search over SEC 10-K Filings</strong></p>
      <p>Standard RAG hallucinates when comparing financial figures across multiple years. TempusRAG audits 5 years of SEC 10-K filings to track whether executives actually delivered on multi-billion-dollar promises.</p>
      <ul>
        <li><strong>Hybrid Search:</strong> Combines keyword search (BM25) and vector embeddings (ChromaDB) via Reciprocal Rank Fusion (<strong>0.8744 MRR</strong>).</li>
        <li><strong>Zero Cross-Year Leakage:</strong> Strict fiscal-year metadata isolation + dual-stage LLM verification.</li>
        <li><strong>Battle-Tested:</strong> <strong>94/94 deterministic CI checks</strong> with multi-account API quota failover.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/Param-Patel-o5">High-Speed LiDAR PCAP Converter</a></h3>
      <p><strong>C++ / Python Offline Sensor Pipeline (First-Author Paper)</strong></p>
      <p>Researchers waste hours converting gigabytes of recorded 3D LiDAR packets. I built a zero-config C++ and Python converter for offline recorded PCAP files across 4 hardware vendors (Ouster, Velodyne, Hesai, Livox).</p>
      <ul>
        <li><strong>Throughput:</strong> Processes <strong>2.08 million points/sec</strong> on standard consumer hardware into LAS, LAZ, PCD, and BIN formats.</li>
        <li><strong>Zero-Config Detection:</strong> 100% vendor auto-identification accuracy across 8 outdoor datasets.</li>
        <li><strong>Publication:</strong> First-author systems manuscript under review at <i>Software: Practice and Experience</i>.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>⚖️ <a href="https://github.com/Param-Patel-o5">FairTrace & JobHunt OS</a></h3>
      <p><strong>Applied ML & Autonomous LangGraph Pipelines</strong></p>
      <p>End-to-end systems built to solve real operational bottlenecks:</p>
      <ul>
        <li><strong>FairTrace (Fintech ML):</strong> Dual-lane credit-risk ML pipeline achieving <strong>0.741 Test AUC</strong> while enforcing strict regulatory fairness compliance.</li>
        <li><strong>JobHunt OS (LangGraph):</strong> Autonomous multi-agent outreach engine that scrapes 4 OSINT channels, rotates multi-account Gemini API pools with 503 failover, discovers BITS Pilani alumni, and powers a Streamlit triage tracker.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🧰 Technical Arsenal

<div align="center">

| Layer | Technologies & Frameworks |
| :--- | :--- |
| **Languages & Core** | ![Python](https://img.shields.io/badge/Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![PyTest](https://img.shields.io/badge/PyTest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) |
| **Agents & LLM Ops** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![AutoGen](https://img.shields.io/badge/AutoGen-0078D4?style=flat-square) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square) |
| **Search, ML & Vision** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square) ![Sentence-Transformers](https://img.shields.io/badge/Sentence_Transformers-FFD21E?style=flat-square) ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![YOLOv11](https://img.shields.io/badge/YOLOv11-00FFFF?style=flat-square) |
| **Data & Shipping** | ![SQLite](
