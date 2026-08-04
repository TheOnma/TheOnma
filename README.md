# Hi! My name is Precious Adekwu

I build AI systems for environments where being wrong is expensive!

I'm an AI engineer and smart contract security researcher based in Nigeria, working across LLM agent systems and blockchain security. Co-founder at **Alma Labs** (blockchain security research), founder of **Jurisa** (AI engineering consultancy), and an alum of the **Uniswap Foundation Incubator, Cohort 7**.

[LinkedIn](https:linkedin.com/in/precious-adekwu/) &nbsp;|&nbsp; [X / Twitter @onma_eth](https://x.com/onma_eth) &nbsp;|&nbsp; preciousadekwu1@gmail.com

---

## What I build

I split my time between two things that turn out to share a lot of infrastructure: AI agents that have to be right, and smart contracts that have to be safe.

### AI Systems

**[Research Agent](https://github.com/TheOnma/research-agent)**
A local RAG system with hybrid retrieval (dense embeddings plus BM25, merged with Reciprocal Rank Fusion) and HyDE query expansion. Every answer is grounded and cited; below a relevance threshold it refuses to answer rather than guess. Extended with paper discovery across arXiv and Semantic Scholar, producing citation grounded literature summaries with an evaluation harness for retrieval and citation accuracy.
`Python` `FastAPI` `ChromaDB` `React` `Claude` `OpenAI Embeddings`

**[Smart Contract Audit Agent](https://github.com/TheOnma/smart-contract-audit-agent)**
An AI assisted auditing system combining RAG retrieval, formal verification, property based fuzzing, and adversarial reasoning. Independently surfaced a validated Medium severity vulnerability in Revert Finance's production code during a live public audit competition, an externally verified result, not a demo.
`Python` `Halmos` `Medusa` `Foundry` `RAG`

**RemoteLlama**
A full stack job board for remote AI roles, built solo end to end: self serve employer posting with a Zod validated flow, LemonSqueezy payments with HMAC verified webhooks, and an automated scraping pipeline using the OpenAI API to parse and categorize postings.
`Next.js` `TypeScript` `PostgreSQL` `Supabase` `OpenAI API`

### Blockchain

**AsyncSwap** (built during the Uniswap Foundation Incubator, Cohort 7)
A production decentralized trading protocol that mitigates sandwich attacks through asynchronous execution: a non custodial delayed execution mechanism with a permissionless settlement network, backed by extensive invariant testing.
`Solidity` `Foundry`

**Secret Market**
A privacy preserving prediction market built on Zama's FHEVM. Recognized as a Developer Contributor by Zama.
`FHEVM` `Solidity`

**TrackFlow**
A decentralized task orchestration platform powered by Succinct's SP1 zkVM.
`SP1 zkVM` `Rust`

---

## Track record

- Ranked 29 out of 773 (top 4%) in the Revert Finance StableSwap Hooks audit contest
- Selected for the Uniswap Foundation Incubator, Cohort 7
- Recognized as a Developer Contributor by Zama for Secret Market
- Validated Medium severity finding in Revert Finance's production code, produced by an AI system I built

## Stack

`Python` `TypeScript` `Solidity` `Rust` `LangGraph` `FastAPI` `Next.js` `PostgreSQL` `AWS` `RAG / Vector Search` `Formal Verification` `Fuzzing`

---

*Currently building AI agent systems where reliability is the actual feature, and looking for the next environment where that's the job.*
