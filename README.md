# Simon Müller

**Systems Architect | Rust Engineer | Ph.D. Mathematician**

I specialise in **High-Performance Computing (HPC)** and **ML Infrastructure**. My focus is replacing GIL-bound Python bottlenecks with highly optimised **Rust** and **C++** kernels, leveraging SIMD, zero-copy data transfer (Apache Arrow), and in-process OLAP engines (DuckDB).

[LinkedIn](https://www.linkedin.com/in/simon-m%C3%BCller/) • [Crates.io](https://crates.io/users/sipemu)

---

### 🔬 Data Science Focus

* **Advanced Forecasting:** Large-scale Hierarchical Time Series (HTS), Probabilistic Forecasting, and Handling Intermittent Demand (Sparse Data) for Supply Chains.
* **Rigorous Statistics**: Bringing statistics and ML to production without the Python overhead.
* **Industrial AI:** Anomaly Detection in manufacturing processes, Predictive Quality, and Root Cause Analysis using Causal Inference.

---

### ⚡ Engineering Focus

* **Systems Programming:** Porting interpretability-heavy Python logic to **Rust/C++** (WASM/Native).
* **GenAI Infrastructure:** Building **Model Context Protocol (MCP)** servers and dependency-free inference engines for Foundation Models.
* **Data Engineering:** Designing zero-copy ETL pipelines using **DuckDB**, **Polars**, and **Apache Arrow**.
* **RAG & Semantic Search:** Developing **Magpie**, a High-performance vector database and RAG engine built in Rust. Implements semantic search with HNSW/DiskANN backends, hybrid retrieval combining dense vectors with BM25, and cross-encoder reranking. Features AST-aware chunking for 7 programming languages (Python, JS, Rust, Java, C#, R, TypeScript), document extraction for 57+ formats including OCR, and advanced RAG patterns (HyDE, Multi-Query, Corrective RAG). Supports multiple embedding/LLM providers (Ollama, OpenAI, Anthropic, Gemini) with deployment options including REST API, MCP server for Claude integration, and WebAssembly.
---

### 🛠 Selected R&D

#### 🦀 [Rust] Chronos-2 Inference Engine
* **Architecture:** Full re-implementation of the Chronos-2 time-series foundation model in pure Rust.
* **Objective:** Remove heavy PyTorch/Python dependencies for edge and high-throughput environments.
* **Tech:** `Candle` / `Burn`, `WASM`, `Tokio`.

#### 🚀 [Rust/C++] AnoFox Forecasting Engine
* **Performance:** Achieved **2,900x speedup** vs. `statsmodels`/`pandas` loops by moving logic to C++.
* **Design:** Hybrid architecture using **DuckDB** for parallelized data shuffling and **Rust** for vectorized statistical kernels.
* **Tech:** `Rust`, `DuckDB C-API`, `OpenMP`.

#### 🐦 [Rust] Magpie MCP Server for SQL Intelligence                                                                                                                                
* **Architecture:** Model Context Protocol server that injects database schemas, query patterns, and semantic code search into AI coding agents.                                     
* **Capability:** Enables LLMs to generate contextually-aware SQL by retrieving similar queries and schema documentation at inference time.                                          
* **Tech:** `axum`, `HNSW`, `MCP Protocol`, `WASM`.  

#### 📊 [Rust] Magpie CRAN Semantic Index                                                                                                                                            
* **Scale:** Indexed **22,771 R packages** with 1024-dim embeddings, enabling semantic search across the entire CRAN ecosystem.                                                      
* **Analysis:** HNSW-accelerated clustering (O(n log n)) discovered **41 package communities** including Time Series, Bioinformatics, and ML—with hierarchical sub-clustering revealing specialised niches (e.g., GARCH, VAR, Single-Cell RNA-seq).
* **Potential:** Enables semantic package discovery, automated Task View curation, near-duplicate detection (e.g., 0.97 similarity pairs), ecosystem health monitoring, and RAG-powered R code generation via MCP.                                                                                                           
* **Potential:** Foundation for R package recommendation, dependency analysis, and ecosystem-wide code intelligence.                                                                 
* **Tech:** `Rust`, `hnsw_rs`, `Louvain community detection`, `Ollama embeddings`.     

#### 🤖 [Rust] MCP (Model Context Protocol) Servers
* **Implementation:** Custom Rust-based servers implementing the MCP standard to inject dynamic context (DB schemas, API specs) into AI coding agents.
* **Tech:** `axum`, `serde`, `async-trait`.

---

### 📦 Open Source & Crates

| Crate / Repo | Description | Stack |
|:--- |:--- |:--- |
| **[sipemu](https://crates.io/users/sipemu)** | 4+ Utility crates for statistical computing. | `Rust` |
| **AnoFox-Statistics** | High-performance statistical extension for DuckDB. | `Rust`, `DuckDB` |
| **Polars-Statistics** | FFI bindings for high-speed statistics on Polars DataFrames. | `Python`, `Rust`, `Polars` |

---

### 💻 Tech Stack

**Core:**
![Rust](https://img.shields.io/badge/-Rust-black?style=flat&logo=rust)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white)

**Data & ML:**
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Polars](https://img.shields.io/badge/-Polars-CD792C?style=flat&logo=polars&logoColor=white)

**Infrastructure:**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-CI%2FCD-2088FF?style=flat&logo=github-actions&logoColor=white)

---

<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=sipemu&show_icons=true&theme=gotham&hide_border=true&count_private=true" height="150" />
</div>
