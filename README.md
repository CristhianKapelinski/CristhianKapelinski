# Hi, I'm Cristhian Kapelinski 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cristhiankapelinski/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/CristhianKapelinski)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:cristhianavila.aluno@unipampa.edu.br)
[![Lattes](https://img.shields.io/badge/Lattes-005A9C?style=flat-square)](http://lattes.cnpq.br/0100277568164430)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Kapelinsky)

**Computer Science senior (GPA 9.23/10) · Python back-end engineer and applied AI/security researcher.**

I build secure, high-throughput back-end systems and do applied AI and security research: data pipelines, LLM/SLM systems, and statistical modeling for **Petrobras** (with CeMEAI/USP), **RNP**, and **ITA**, plus current **adversarial-AI security** research at **Poli-USP/LARC** (Bradesco project). 19 accepted peer-reviewed publications (10 first-author), including **BRACIS 2026** (Springer LNAI) and the **SBRC 2026 Best Artifact Award**. ICPC Silver Medalist. Most of my papers ship with a public reproducibility artifact.

![Publications](https://img.shields.io/badge/Peer__reviewed_publications-21-2ea44f?style=flat-square)
![ICPC](https://img.shields.io/badge/ICPC-Silver_Medalist-C0C0C0?style=flat-square)
![Award](https://img.shields.io/badge/SBRC_2026-Best_Artifact-FFD700?style=flat-square)

### 🚀 Current & recent work

- **Pre-Master's Research Fellow @ USP (Poli-USP/LARC), AI Security:** adversarial-AI / GenAI security in a Bradesco project, red team and blue team of LLMs (prompt injection, jailbreaks) and defenses (guardrails, input/output filters, detection).
- **R&D Fellow @ ITA (CYBERGUARD), CNPq (Apr–Jul 2026):** co-authored the SBSeg 2026 tutorial *Inteligência Artificial aplicada à Resposta a Incidentes*, contributing the case studies on ticket anonymization, incident classification, and LLM-assisted response playbooks.
- **Back-end Engineer @ Alice Humam (Petrobras, with CeMEAI/USP, 2025–2026):** built the Python/FastAPI back-end of a reliability-analysis platform: ETL pipelines and survival-analysis models translated from research R code and verified numerically equivalent, plus the HTML reporting engine and a per-route observability layer (p50/p95/p99); over 16 months, 111k+ lines and 375 merged MRs, became the team code reviewer, and co-managed the dev team (Scrum/Kanban).
- **Competitive Programming:** Silver Medal 🥈 at the 2025 ICPC Brazil Regional First Phase (team _Array de Noobs 2.0_).

### 🔬 Featured Work & Research

- **[AnonShield](https://github.com/AnonShield/anonshield): Scalable On-Premise Pseudonymization** *(First author · SBRC 2026 Best Artifact, all 4 reproducibility badges)*
  High-throughput pseudonymization for CSIRT vulnerability data. GPU-accelerated NER, streaming I/O, and LRU caching cut processing of a 550 MB dataset from over 92 hours to under 10 minutes (**738× faster**), at **94.2% F1** and **96.4% recall**, GDPR/LGPD-compliant without losing analytical utility.
- **[Decomposing Memorization Reduction in Privacy-Preserving Fine-Tuning of SLMs](https://arxiv.org/abs/2606.28479)** *(First author · BRACIS 2026, Springer)*
  First empirical study of how DP-SGD and HMAC pseudonymization compose when fine-tuning 1 to 3B language models on CSIRT data, across 96 LoRA adapters and a dual extraction attack.
- **[Not All 4-bit Quantizers Are Equal](https://github.com/CristhianKapelinski/quantizer-pii-mitigation)** *(First author · SBSeg 2026, full paper)*
  The choice of 4-bit quantizer changes how much PII a fine-tuned model leaks at deployment time, not just its speed. AWQ, GPTQ and GGUF compared across five 0.5–7B SLMs, with the calibration-corpus axis isolated by four ablations. Artifact reproduces **141/141** published values.
- **Large-Scale Docker Hub Security Measurement** *(First author · two SBSeg 2026 short papers)*
  Distributed **Go** crawler over **12M+ repositories**, an **84M-node** image dependency graph in Neo4j, and 50k+ high-exposure images scanned with six scanners into a public **170M-finding** dataset. Two artifacts: a [multi-scanner census of Linux base images](https://github.com/ChimangoScan/os-census) and a [uniform random-sample measurement](https://github.com/ChimangoScan/chimango-baseline) of the registry.
- **[ZeroLINC](https://github.com/CristhianKapelinski/zerolinc): Training-Free Incident Triage** *(First author · SBSeg 2026, tool track)*
  Classifies CSIRT/SOC incident reports into the 12 NIST SP 800-61r3-derived categories with **no training**: a k-NN instance-memory engine at **90.8%** and a zero-shot engine, behind one command and running locally. [Measurement study](https://github.com/CristhianKapelinski/zerolinc-benchmark) behind it: 293 runs.
- **[CryptoCensus](https://github.com/CristhianKapelinski/cryptocensus): Post-Quantum Readiness of Docker Hub** *(First author · WTICG/SBSeg 2026)*
  Distributed census of **11,962 images** and over **4.2 million cryptographic assets**, measuring how far the registry is from post-quantum migration.

More reproducibility artifacts: [RAGtrap](https://github.com/CristhianKapelinski/sbseg2026-ragtrap) (signed provenance with O(1) traceback for poisoned RAG corpora) · [PixGuard-Sim](https://github.com/CristhianKapelinski/sbseg2026-pixguard-sim) (deadline-aware testbed for Pix fraud detectors) · [wazuh-study](https://github.com/CristhianKapelinski/wazuh-study) (LLM-generated SIEM rules on real SSH logs) · [AdminForge](https://github.com/BagualOps/adminforge-sbseg2026) (agentless privileged-identity management for Linux fleets) · [MulitaMiner](https://github.com/AnonShield/MulitaMiner) (LLM extraction of OpenVAS reports, 93.55% F1).

### 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

**Back-end**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Data Science & ML**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![lifelines](https://img.shields.io/badge/lifelines_(survival)-2C5985?style=flat-square)

**AI · LLMs · NLP**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/Tesseract_OCR-5C3EE8?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-FF6F61?style=flat-square)
![llama.cpp](https://img.shields.io/badge/llama.cpp-444444?style=flat-square)
![Opacus](https://img.shields.io/badge/Opacus_(DP--SGD)-792EE5?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Front-end & Mobile**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)

**DevOps & Observability**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI/CD](https://img.shields.io/badge/GitLab_CI%2FCD-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Security & Crypto**

![Wazuh](https://img.shields.io/badge/Wazuh-3268C5?style=flat-square&logo=wazuh&logoColor=white)
![OpenSSH](https://img.shields.io/badge/OpenSSH-4D4D4D?style=flat-square&logo=openssh&logoColor=white)
![HMAC-SHA256](https://img.shields.io/badge/HMAC--SHA256-525252?style=flat-square)
![Ed25519](https://img.shields.io/badge/Ed25519-525252?style=flat-square)

> Also hands-on with: Loki, Alertmanager, Grafana Alloy, Uptime Kuma, GraphSAGE, WeasyPrint, sentence-transformers (e5, bge-m3), BM25, BERTScore, Qwen-VL, PaddleOCR-VL, EMV/BR Code parsing, and AI-assisted development (Claude Code, OpenAI Codex, Gemini CLI).

### 🏆 Awards & Certifications

- 🥇 **Best Artifact Award**, SBRC 2026 (best artifact of the entire conference) and **Distinguished Artifact Reviewer**, SBRC 2026
- 🥈 **Silver Medal**, ICPC/SBC Programming Marathon 2025 (Brazil Regional First Phase); 3rd place RS, Phase Zero
- 🏆 **1st Place**, SBRC 2026 Hackathon · **2nd Best Paper**, WRSeg/ERRC 2025
- 🎓 Hackers do Bem (144h, MCTI/SENAI/RNP) · ICT Residency in AI & Data Science (180h, BRISA/Softex) · CS50P (Harvard)

---

📫 **Let's connect:** [LinkedIn](https://www.linkedin.com/in/cristhiankapelinski/) · [Lattes](http://lattes.cnpq.br/0100277568164430) · [Codeforces](https://codeforces.com/profile/Kapelinsky) · [Email](mailto:cristhianavila.aluno@unipampa.edu.br)
