# Simon Müller

**Software Architect | Data Scientist | Ph.D. Mathematics**

I design high-performance data systems in **Rust** and **C++** and apply statistical and machine-learning methods to industrial planning problems. My work spans DuckDB extensions, time-series forecasting engines, and GenAI infrastructure (RAG, MCP servers, foundation model inference).

[LinkedIn](https://www.linkedin.com/in/simon-m%C3%BCller/) • [Crates.io](https://crates.io/users/sipemu) • [DataZooDE](https://github.com/DataZooDE)

---

### What I Do

- **Time-Series Forecasting** -- Hierarchical, probabilistic, and intermittent-demand forecasting for supply chains, built as native DuckDB extensions.
- **Statistical Computing** -- Production-grade regression, hypothesis testing, and causal inference in Rust, exposed through DuckDB and Polars.
- **GenAI & RAG Infrastructure** -- Vector databases (HNSW/DiskANN), retrieval-augmented generation, and Model Context Protocol (MCP) servers for AI-assisted development.
- **Foundation Model Inference** -- Pure-Rust inference engines for time-series models, targeting edge and WASM deployment without Python dependencies.
- **Enterprise Data Integration** -- DuckDB extensions for SAP and API ecosystems, bridging legacy ERP systems with modern analytical workflows.
- **Inventory & Supply Chain Optimisation** -- Stochastic inventory models and demand planning applications.

### Business Impact

- **Forecast Accuracy & Speed** — anofox-forecast delivers 2,900x faster forecasting, enabling near-real-time demand planning that reduces stockouts and excess inventory.
- **Inventory & Working Capital** — Stochastic inventory models optimise safety stock levels, freeing working capital while maintaining service levels.
- **Enterprise Data Accessibility** — erpl and flapi turn locked-away SAP/ERP data into queryable, API-accessible datasets, cutting integration timelines from months to days.
- **Data Quality & Trust** — Automated anomaly detection and validation (anofox-tabular) catches data issues before they reach dashboards and decisions.
- **AI-Ready Infrastructure** — RAG pipelines and vector search (Magpie) ground LLM responses in company knowledge, reducing hallucination and making GenAI safe for enterprise use.
- **Reduced Infrastructure Cost** — Pure-Rust inference (Chronos-2) and high-performance libraries (motif-rs, oxits-rs) eliminate Python overhead, cutting cloud compute costs and enabling edge deployment.

---

### Featured Projects

#### Data Engineering & Integration

| Project | Highlight | Stack |
|:--------|:----------|:------|
| [flapi](https://github.com/DataZooDE/flapi) | DuckDB-powered API gateway with MCP server and VS Code extension | `C++`, `DuckDB` |
| [erpl](https://github.com/DataZooDE/erpl) | DuckDB extension bridging SAP systems via RFC | `C++`, `DuckDB` |
| [dbt-lineage-viewer](https://github.com/sipemu/dbt-lineage-viewer) | Fast CLI for visualising dbt model lineage | `Rust` |
| [anofox-tabular](https://github.com/DataZooDE/anofox-tabular) | Anomaly detection, validation, and data preparation in DuckDB | `C++`, `DuckDB` |

#### Time Series & Forecasting

| Project | Highlight | Stack |
|:--------|:----------|:------|
| [anofox-forecast](https://github.com/DataZooDE/anofox-forecast) | 2,900x faster than statsmodels; DuckDB community extension | `C++`, `Rust`, `DuckDB` |
| Chronos-2 | Pure-Rust re-implementation of Amazon's Chronos-2 time-series foundation model | `Rust`, `Candle` |
| [oxits-rs](https://github.com/sipemu/oxits-rs) | Time series classification and transformation library -- port of pyts | `Rust` |
| [motif-rs](https://github.com/sipemu/motif-rs) | High-performance matrix profile library; 3--63x faster than stumpy | `Rust` |

#### GenAI & RAG

| Project | Highlight | Stack |
|:--------|:----------|:------|
| Magpie | Vector DB and RAG engine with HNSW, hybrid retrieval, AST-aware chunking | `Rust` |

#### Statistical Computing & Operations Research

| Project | Highlight | Stack |
|:--------|:----------|:------|
| [polars-statistics](https://github.com/DataZooDE/polars-statistics) | High-performance statistical testing and regression for Polars | `Rust`, `Python` |
| Inventory Optimisation | Stochastic inventory models for demand planning | `Rust` |
| [fdars](https://github.com/sipemu/fdars) | FDA algorithms -- depth measures, clustering, smoothing, regression | `Rust`, `R` |

*flapi and erpl are [DataZooDE](https://github.com/DataZooDE) projects.*

### R Packages

| Package | Description |
|:--------|:-----------|
| [fdars-r](https://github.com/sipemu/fdars-r) | Functional Data Analysis R package with Rust backend |
| [eventstudy](https://github.com/sipemu/eventstudy) | Financial event study analysis |
| [case-based-reasoning](https://github.com/sipemu/case-based-reasoning) | Case-based reasoning using machine learning methods |

---

### Tech Stack

**Core:**
![Rust](https://img.shields.io/badge/-Rust-black?style=flat&logo=rust)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white)

**Data & ML:**
![DuckDB](https://img.shields.io/badge/-DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Polars](https://img.shields.io/badge/-Polars-CD792C?style=flat&logo=polars&logoColor=white)
![Apache Arrow](https://img.shields.io/badge/-Apache%20Arrow-E34F26?style=flat&logo=apache&logoColor=white)

**Infrastructure:**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-CI%2FCD-2088FF?style=flat&logo=github-actions&logoColor=white)

---

<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=sipemu&show_icons=true&theme=gotham&hide_border=true&count_private=true" height="150" />
</div>
