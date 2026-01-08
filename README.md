# Simon Müller

**Systems Architect | Rust Engineer | Ph.D. Mathematician**

I specialise in **High-Performance Computing (HPC)** and **ML Infrastructure**. My focus is replacing GIL-bound Python bottlenecks with highly optimised **Rust** and **C++** kernels, leveraging SIMD, zero-copy data transfer (Apache Arrow), and in-process OLAP engines (DuckDB).

[LinkedIn](https://www.linkedin.com/in/simon-m%C3%BCller/) • [Crates.io](https://crates.io/users/sipemu)

---

### 🔬 Data Science Focus

* **Advanced Forecasting:** Large-scale Hierarchical Time Series (HTS), Probabilistic Forecasting, and Handling Intermittent Demand (Sparse Data) for Supply Chains.
* **Rigorous Statistics:** Bayesian Inference (`Stan`), Design of Experiments (DoE), Functional Data Analysis (FDA), and Partial Least Squares (PLS) for Chemometrics/Pharma.
* **Industrial AI:** Anomaly Detection in manufacturing processes, Predictive Quality, and Root Cause Analysis using Causal Inference.

---

### ⚡ Engineering Focus

* **Systems Programming:** Porting interpretability-heavy Python logic to **Rust/C++** (WASM/Native).
* **GenAI Infrastructure:** Building **Model Context Protocol (MCP)** servers and dependency-free inference engines for Foundation Models.
* **Data Engineering:** Designing zero-copy ETL pipelines using **DuckDB**, **Polars**, and **Apache Arrow**.

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
