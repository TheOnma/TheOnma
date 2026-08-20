# Precious Adekwu

> **AI Systems Engineer & Security Researcher**  
> Building deterministic AI agent architectures and formal blockchain security systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/)
[![X/Twitter](https://img.shields.io/badge/X-@onma__eth-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/onmathetitan)
[![Email](https://img.shields.io/badge/Email-Contact_Me-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:preciousadekwu1@gmail.com)
---

### ⚡ Focus

I design systems at the intersection of **AI agents that have to be right** and **smart contracts that have to be safe**.

- **[Jurisa](https://jurisa.co/)** — Founder (AI engineering & operations orchestration)
- **Alma Labs** — Co-Founder (Blockchain security research & autonomous verification)
- **Uniswap Foundation Incubator** — Alum, Cohort 7

---

### 🛠️ Featured Systems

#### 🧠 AI Systems & Autonomous Agents

* **[Smart Contract Audit Agent](https://github.com/TheOnma/smart-contract-audit-agent)**   
  *Automated vulnerability discovery via hybrid RAG, property-based fuzzing, and formal verification.*
  * **Milestone:** Placed **29/773 (top 4%)** in a live Cantina contest; independently surfaced a verified Medium-severity vulnerability in Revert Finance production code.
  * **Benchmarks:** `1.0 Recall@10` and `0.95` end-to-end detection rate across 20 confirmed production vulnerabilities.
  * `Python` · `Halmos` · `Foundry` · `Certora` · `Formal Verification`

* **[Research Agent](https://github.com/TheOnma/lexica-research-agent)** 
  *Local-first autonomous literature retrieval & multi-step synthesis.*
  * Hybrid dense + BM25 retrieval fused via **Reciprocal Rank Fusion (RRF)**, HyDE query expansion, and a CRAG-style corrective judge.
  * Features a closed **SimRAG-style self-eval loop** to iteratively evaluate and optimize hit rates.
  * `Python` · `LangGraph` · `FastAPI` · `ChromaDB` · `Claude API`

* **Argos Scribe** *(by Jurisa · Closed Source / Enterprise)*  
  *Polymorphic Proposal-Ops engine automating B2B SOW generation from discovery call transcripts and raw RFPs.*
  * Built on a 7-stage deterministic LangGraph architecture featuring bounded self-critique loops, dynamic service tier mapping, strict in-scope/out-of-scope bounding, and Pydantic structured output validation.
  * `Python` · `LangGraph` · `FastAPI` · `Supabase (PostgreSQL/RLS)` · `Claude API` · `Next.js`
 
* **[Ask Your Documents](https://github.com/TheOnma/ask-your-documents)**  
  *Production-ready local document intelligence platform with verifiable source citations.*
  * Hybrid retrieval engine combining ChromaDB dense vectors and BM25 via RRF, featuring HyDE expansion, strict confidence thresholding against hallucinations, and automated multi-format ingestion (PDF/DOCX/TXT).
  * `Python` · `FastAPI` · `ChromaDB` · `BM25` · `React` · `Tailwind CSS` · `OpenAI API`
 
---

#### ⛓️ Blockchain & Cryptographic Infrastructure

* **[AsyncSwap](https://github.com/TheOnma/async-swap-hook)** *(Uniswap Foundation Incubator, Cohort 7)*  
  *Production DEX protocol mitigating sandwich attacks via non-custodial asynchronous execution and permissionless settlement networks.*  
  `Solidity` · `Foundry` · `Invariant Testing`

* **[Secret Market](https://github.com/TheOnma/secret-market-fhevm)** *(Recognized by Zama as Developer Contributor)*  
  *Privacy-preserving prediction market built on Fully Homomorphic Encryption.*  
  `FHEVM` · `Solidity`

* **[TrackFlow](https://github.com/TheOnma/TrackFlow-App-Sp1)** 
  *Decentralized verifiable task orchestration system.*  
  `SP1 zkVM` · `Rust`

---

### 🏆 Validated Track Record

* 🥈 **Top 4% (29/773)** — Cantina Revert Finance StableSwap Hooks Audit Contest (automated finding).
* 🦄 **Uniswap Foundation Incubator** — Selected for Cohort 7.
* 🛡️ **Zama Developer Contributor** — Official contributor recognition for FHEVM implementation.

---

### 🧰 Technical Stack

- **AI & Orchestration:** LangGraph · RAG Pipelines · CRAG · HyDE · ChromaDB · Evaluation Loops
- **Languages:** Python · TypeScript · Solidity · Rust · SQL
- **Security & Testing:** Halmos · Certora · Foundry · Property Fuzzing · Invariant Testing · SP1 zkVM
- **Backend & Infra:** FastAPI · Next.js · PostgreSQL · AWS

  <i>Currently building agent systems that require deterministic correctness — open to mission-critical engineering teams.</i>
</p>
