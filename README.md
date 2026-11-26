# 🕸️ Awesome-Enterprise-Knowledge-Graphs-Automated-Ontologies

<p align="center">
  <img src="./assets/banner.svg" alt="Top Enterprise Knowledge Graphs, Graph Databases, GraphRAG &amp; Automated Ontologies" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Enterprise-Knowledge-Graphs-Automated-Ontologies/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Enterprise-Knowledge-Graphs-Automated-Ontologies?style=social" alt="GitHub_Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Enterprise-Knowledge-Graphs-Automated-Ontologies/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Enterprise-Knowledge-Graphs-Automated-Ontologies?style=social" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

# 🧠 Top Enterprise Knowledge Graphs & Automated Ontologies

**A Curated Index of SaaS/Commercial Platforms, GraphRAG Memory Engines, Open-Source Graph Databases & LLM-Driven Automated Ontology Induction Systems.**

*Keywords: Knowledge Graphs, Automated Ontology Generation, GraphRAG, Semantic Web, Neuro-Symbolic AI, Graph Databases, Cypher, SPARQL, W3C RDF/OWL, LLM Memory Engines, Vector-Graph Hybrid Search.*

**Last updated: November 2026**

---

## 📌 Executive Summary & Architecture Overview

Enterprise knowledge architectures have transitioned from static transactional storage into intelligent semantic fabrics. Today's **Enterprise Knowledge Graph (EKG)** ecosystem unites:
1. **Automated Ontology Induction & Synthesis**: Extracting concepts, taxonomies, and ontological relations directly from messy unstructured corpora using state-of-the-art LLMs (`NVIDIA/auto-ontology`, `Microsoft GraphRAG`, `DSPy`).
2. **GraphRAG & Agentic Dynamic Memory**: Real-time episodic and semantic knowledge graphs for agent orchestration (`HKUDS/LightRAG`, `Cognee`, `Graphiti`) that eradicate hallucinations and enable multi-hop reasoning.
3. **High-Performance Hybrid Graph Engines**: Native Labeled Property Graph (LPG) engines, high-speed C++/Rust embedded graph engines (`Kùzu`, `Memgraph`, `Oxigraph`), and horizontally distributed stores (`Neo4j`, `Dgraph`, `NebulaGraph`, `JanusGraph`).
4. **W3C Semantic Standards & Reasoning**: Formal RDF, OWL, and SPARQL semantic reasoners and virtual graph virtualizers (`Stardog`, `Apache Jena`, `RDFLib`, `Altair Anzo`).

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [📈 Star History](#-star-history)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global Graph Database & Enterprise Knowledge Graph market is valued at approximately **$3.8B–$4.9B+ in 2026** (projected to exceed $15B+ by 2032 at a ~22%–28% CAGR), driven by enterprise adoption of **GraphRAG**, neuro-symbolic reasoning, and automated LLM ontology induction. The market dynamics exhibit **moderate to high concentration** at the enterprise operational graph tier (led by hyperscalers like AWS Neptune and specialized category leaders like Neo4j), alongside a **highly fragmented, rapidly innovating open-source ecosystem** pioneering automated ontology induction and modular graph memory engines.

---

## ☁️ SaaS/Hosted & Commercial Platforms

*Sorted descending by company valuation / annual revenue scale.*

| Platform | Description | Company Scale (Valuation / Revenue) | Pricing (Starting Paid Tier) | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Amazon Neptune](https://amazon.com)** | Fully managed AWS graph database supporting both Labeled Property Graphs (openCypher/Gremlin) and W3C RDF/SPARQL plus Neptune Analytics. | **AWS / Amazon** (~$115B+ AWS annual run-rate; ~$2.2T parent market cap) | **$0.10 / hour** (~$73/month) for `db.t4g.medium` (plus $0.10/GB-month storage & $0.20/million I/Os) | **30-Day Free Trial** (**750 hours** of `db.t3.medium` or `db.t4g.medium`, 10M I/O requests, and 1 GB storage free for 30 days) |
| **[Cambridge Semantics (Altair Anzo)](https://altair.com)** | Enterprise knowledge graph and semantic data-fabric platform automating RDF/OWL ontology integration across structured and unstructured silos. | **Siemens / Altair** (Acquired by Altair; Siemens acquired Altair for $10.6B enterprise value; $600M+ revenue) | **~$5.00 / hour** (or ~50 Altair Units/hr subscription; starting enterprise contract licenses from $50,000/yr) | **Free Forever Developer Edition (Docker)** (Limited to **8 GB RAM** without registration or **16 GB RAM** with free developer registration; 30-day proof-of-concept enterprise trial) |
| **[Neo4j Aura](https://neo4j.com)** | Fully managed cloud native graph database and graph data science platform featuring Cypher, native vector search, and GraphRAG integrations. | **$2.0B+ Valuation** (~$200M+ ARR) | **$65.00 / month** ($0.089/hour) for AuraDB Professional (1 GB RAM, 2 GB storage instance) | **Forever Free Tier (AuraDB Free)** (Limited to **1 database, 200,000 nodes, and 400,000 relationships**; plus 14-day Pro trial) |
| **[TigerGraph Cloud](https://tigergraph.com)** | Massively parallel distributed graph database and analytics SaaS designed for deep multi-hop real-time queries and enterprise GraphRAG. | **~$500M–$800M Est. Valuation** (~$40M–$60M est. ARR; $170M+ VC funding) | **$0.24 / hour** (~$175/month) for TG.Free-to-Starter instances (2 vCPU, 8 GB RAM) | **Forever Free Tier** (1 free instance up to **50 GB storage**, 2 vCPU, 8 GB memory with GraphStudio UI; 14-day Enterprise trial with $25 free credits) |
| **[ArangoDB Oasis (ArangoGraph)](https://arangodb.com)** | Managed multi-model graph, document, and vector database cloud platform supporting AQL queries, Pregel graph analytics, and GraphRAG. | **~$100M–$150M Est. Valuation** (~$15M–$25M est. ARR; $47M+ VC funding) | **$0.25 / hour** (~$180/month) for ArangoGraph One-Shard Starter (4 GB RAM, 2 vCPU) | **14-Day Free Trial** (Full access to ArangoGraph cloud cluster with **up to $200 in free trial credits**, no credit card required) |
| **[Katana Graph (Intel / Legacy Reference)](https://intel.com)** | High-performance distributed graph processing, AI, and analytics engine built for massive-scale graph neural networks and sub-second queries. | **~$100M+ Peak Valuation** (IP & engineering talent acquired/integrated into Intel AI/labs; $28M+ funding) | **$2.80 / hour** per GPU node (legacy commercial cluster pricing; enterprise bespoke contracts from $30,000/yr) | **Free Forever Open Source (Galois Core)** (Underlying C++ distributed Galois parallel engine is free forever with no node limit; 30-day sandbox trial for enterprise suites) |
| **[Stardog Cloud](https://stardog.com)** | Enterprise knowledge graph platform uniting W3C RDF/OWL semantic reasoning, virtual graphs (data virtualization), and Voicebox LLM querying. | **~$50M–$80M Est. Valuation** (~$10M–$15M est. ARR; $35M+ VC funding) | **$5.553 / hour** on AWS Marketplace (pay-as-you-go baseline instance; standard cloud contracts from $250/mo) | **Forever Free Cloud Tier** (Free shared cloud database limited to **1,000,000 edges/triples**, up to 3 databases, and Stardog Studio; 30-day Enterprise trial) |
| **[Memgraph Cloud](https://memgraph.com)** | Ultra-fast, in-memory C++ graph database cloud compatible with Neo4j Cypher and Bolt, engineered for real-time streaming and GraphRAG. | **~$40M–$70M Est. Valuation** (~$10M–$15M est. ARR; backed by M12 & InReach) | **$50.00 / month** (~$0.069/hour) for Memgraph Cloud Basic (1 GB RAM, 5 GB storage) | **14-Day Free Trial** (Full access to 1 managed Memgraph Cloud instance with Memgraph Lab UI and streaming integrations, no credit card required) |
| **[Dgraph Cloud (Hypermode)](https://dgraph.io)** | Distributed, horizontally scalable native GraphQL and RDF-inspired graph database cloud platform built in Go for low-latency traversals. | **~$30M–$50M Est. Valuation** (Maintained by Hypermode; $26M+ prior VC funding) | **$99.00 / month** for Dedicated 1-node backend (or legacy shared compute tier at $9.99/month) | **Forever Free Tier** (Free shared GraphQL backend limited to **10,000 daily operations/requests and 1 GB data transfer**; 14-day dedicated trial) |
| **[TypeDB Cloud (formerly Grakn Core / Vaticle)](https://typedb.com)** | Strongly-typed polymorphic database and symbolic reasoning engine bridging knowledge graphs, relational models, and automated rule inference. | **~$20M–$40M Est. Valuation** (~$15M+ VC funding) | **$0.20 / hour** (~$145/month) for TypeDB Cloud Development Starter cluster | **14-Day Free Trial** (Full managed TypeDB Cloud cluster, 1 cluster limit, with TypeDB Studio console access, no credit card required) |

---

## 💻 Open-Source GitHub Projects

*Sorted descending by GitHub stargazers count.*

| Project & Repo | GitHub_Stars | Primary Focus & Domain | License / Cost | Free Tier / Self-Hosted Limit | Description |
| :--- | :---: | :--- | :--- | :--- | :--- |
| **[LightRAG](https://github.com/HKUDS/LightRAG)** (`HKUDS/LightRAG`) | [![Stars](https://img.shields.io/github/stars/HKUDS/LightRAG?style=social&color=white)](https://github.com/HKUDS/LightRAG/stargazers) | **GraphRAG & Fast Retrieval** | **MIT** ($0) | **100% Free Forever** (Unlimited local/server GraphRAG indexing & dual-level retrieval) | Simple, lightning-fast knowledge graph retrieval-augmented generation engine optimizing dual-level entity & relation representations. |
| **[DSPy](https://github.com/stanfordnlp/dspy)** (`stanfordnlp/dspy`) | [![Stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=social&color=white)](https://github.com/stanfordnlp/dspy/stargazers) | **Prompt Optimization & Semantic Extraction** | **MIT** ($0) | **100% Free Forever** (Self-hosted programmatic prompting and structured ontology mapping) | Stanford's framework for programmatically optimizing LLM prompts, modular chains, and structured relation extraction pipelines. |
| **[Microsoft GraphRAG](https://github.com/microsoft/graphrag)** (`microsoft/graphrag`) | [![Stars](https://img.shields.io/github/stars/microsoft/graphrag?style=social&color=white)](https://github.com/microsoft/graphrag/stargazers) | **Modular GraphRAG Pipeline** | **MIT** ($0) | **100% Free Forever** (Unlimited local community detection, graph clustering & global summarization) | Modular graph-based RAG pipeline transforming unstructured text into hierarchical knowledge graphs and semantic summaries. |
| **[Cognee](https://github.com/topoteretes/cognee)** (`topoteretes/cognee`) | [![Stars](https://img.shields.io/github/stars/topoteretes/cognee?style=social&color=white)](https://github.com/topoteretes/cognee/stargazers) | **AI Agent Memory & Auto-Ontologies** | **Apache-2.0** ($0) | **100% Free Forever** (Self-hosted automated schema induction, ECL pipelines & vector-graph storage) | Deterministic memory manager for AI applications and agents that extracts ontologies, constructs knowledge graphs, and performs GraphRAG. |
| **[Graphiti](https://github.com/getzep/graphiti)** (`getzep/graphiti`) | [![Stars](https://img.shields.io/github/stars/getzep/graphiti?style=social&color=white)](https://github.com/getzep/graphiti/stargazers) | **Temporal Agent Knowledge Graphs** | **Apache-2.0** ($0) | **100% Free Forever** (Unlimited temporal graph memory execution, dynamic edge invalidation & bi-temporal search) | Dynamically updating knowledge graph engine purpose-built for agent memory, tracking time-invalidated facts and episodic state changes. |
| **[Dgraph](https://github.com/dgraph-io/dgraph)** (`dgraph-io/dgraph`) | [![Stars](https://img.shields.io/github/stars/dgraph-io/dgraph?style=social&color=white)](https://github.com/dgraph-io/dgraph/stargazers) | **Distributed Native Graph Database** | **Apache-2.0** ($0) | **100% Free Forever** (No node or edge limits; cluster scaling on self-hosted infrastructure) | High-performance, distributed graph database written in Go with native GraphQL and GraphQL+- query syntax. |
| **[Neo4j Community](https://github.com/neo4j/neo4j)** (`neo4j/neo4j`) | [![Stars](https://img.shields.io/github/stars/neo4j/neo4j?style=social&color=white)](https://github.com/neo4j/neo4j/stargazers) | **Native Labeled Property Graph (LPG)** | **GPL-3.0** ($0) | **100% Free Forever** (Single-instance deployment with unlimited nodes, relationships, and Cypher queries) | The world's most widely adopted open-source native graph database, pioneering the Cypher query language and property graphs. |
| **[NVIDIA Auto-Ontology](https://github.com/NVIDIA/auto-ontology)** (`NVIDIA/auto-ontology`) | [![Stars](https://img.shields.io/github/stars/NVIDIA/auto-ontology?style=social&color=white)](https://github.com/NVIDIA/auto-ontology/stargazers) | **LLM Automated Ontology Induction** | **Apache-2.0** ($0) | **100% Free Forever** (Unlimited domain ontology synthesis, concept taxonomies, and KG induction from corpora) | NVIDIA's official automated ontology induction and knowledge graph synthesis toolkit that builds formal schemas from unstructured text. |
| **[NebulaGraph](https://github.com/vesoft-inc/nebula)** (`vesoft-inc/nebula`) | [![Stars](https://img.shields.io/github/stars/vesoft-inc/nebula?style=social&color=white)](https://github.com/vesoft-inc/nebula/stargazers) | **Massive-Scale Distributed Graph Store** | **Apache-2.0** ($0) | **100% Free Forever** (Distributed storage & compute architecture capable of tens of billions of vertices) | Distributed, horizontally scalable graph database engineered for super-large-scale datasets with millisecond-latency traversals. |
| **[JanusGraph](https://github.com/JanusGraph/janusgraph)** (`JanusGraph/janusgraph`) | [![Stars](https://img.shields.io/github/stars/JanusGraph/janusgraph?style=social&color=white)](https://github.com/JanusGraph/janusgraph/stargazers) | **Scalable Distributed Graph Engine** | **Apache-2.0** ($0) | **100% Free Forever** (Pluggable storage on Cassandra, HBase, or ScyllaDB with Apache TinkerPop Gremlin) | Distributed graph database optimized for large graphs, advanced search, and analytics across distributed storage backends. |
| **[Memgraph](https://github.com/memgraph/memgraph)** (`memgraph/memgraph`) | [![Stars](https://img.shields.io/github/stars/memgraph/memgraph?style=social&color=white)](https://github.com/memgraph/memgraph/stargazers) | **In-Memory Streaming Graph DB** | **BSL-1.1 / Apache-2.0** ($0) | **100% Free Forever** (Single instance Community edition has no memory or dataset caps) | Ultra-fast in-memory graph database built in C++ featuring complete openCypher compliance and real-time Kafka/Pulsar streaming. |
| **[TypeDB](https://github.com/typedb/typedb)** (`typedb/typedb`) | [![Stars](https://img.shields.io/github/stars/typedb/typedb?style=social&color=white)](https://github.com/typedb/typedb/stargazers) | **Polymorphic Database & Rule Inference** | **MPL-2.0** ($0) | **100% Free Forever** (Full TypeDB core database with TypeQL query engine and automated deductive reasoning) | Strongly typed polymorphic database with an expressive type system and built-in symbolic rule-based inference engine. |
| **[Kùzu](https://github.com/kuzudb/kuzu)** (`kuzudb/kuzu`) | [![Stars](https://img.shields.io/github/stars/kuzudb/kuzu?style=social&color=white)](https://github.com/kuzudb/kuzu/stargazers) | **Embedded Cypher Graph Engine (C++)** | **MIT** ($0) | **100% Free Forever** (Lightweight DuckDB-like in-process graph engine with zero external dependencies) | Embedded property graph database management system optimized for OLAP graph query workloads and seamless Python integrations. |
| **[Apache HugeGraph](https://github.com/apache/hugegraph)** (`apache/hugegraph`) | [![Stars](https://img.shields.io/github/stars/apache/hugegraph?style=social&color=white)](https://github.com/apache/hugegraph/stargazers) | **Large-Scale Graph Database System** | **Apache-2.0** ($0) | **100% Free Forever** (Scalable graph analytics, Gremlin traversal, and billions of entities support) | Apache incubator distributed graph database system supporting Apache TinkerPop 3 and efficient graph computing. |
| **[RDFLib](https://github.com/RDFLib/rdflib)** (`RDFLib/rdflib`) | [![Stars](https://img.shields.io/github/stars/RDFLib/rdflib?style=social&color=white)](https://github.com/RDFLib/rdflib/stargazers) | **Python W3C Semantic Web Toolkit** | **BSD-3-Clause** ($0) | **100% Free Forever** (Pure Python RDF parsing, SPARQL 1.1 querying, serialization, and graph manipulation) | The standard Python library for working with RDF, OWL, and SPARQL, essential for semantic engineering and ontology workflows. |
| **[Oxigraph](https://github.com/oxigraph/oxigraph)** (`oxigraph/oxigraph`) | [![Stars](https://img.shields.io/github/stars/oxigraph/oxigraph?style=social&color=white)](https://github.com/oxigraph/oxigraph/stargazers) | **High-Speed Rust Graph Database** | **Apache-2.0 / MIT** ($0) | **100% Free Forever** (Rust-native triple/quad store with SPARQL 1.1 evaluation) | Graph database and triple store written in Rust implementing the SPARQL 1.1 query language and W3C semantic graph standards. |
| **[PyKEEN](https://github.com/pykeen/pykeen)** (`pykeen/pykeen`) | [![Stars](https://img.shields.io/github/stars/pykeen/pykeen?style=social&color=white)](https://github.com/pykeen/pykeen/stargazers) | **Knowledge Graph Embeddings & Link Prediction** | **MIT** ($0) | **100% Free Forever** (Comprehensive PyTorch-based KG embedding model library with 40+ algorithms) | Python package for training and evaluating knowledge graph embeddings, link prediction, and neuro-symbolic representation learning. |
| **[Protégé](https://github.com/protegeproject/protege)** (`protegeproject/protege`) | [![Stars](https://img.shields.io/github/stars/protegeproject/protege?style=social&color=white)](https://github.com/protegeproject/protege/stargazers) | **Desktop Ontology Editor & Reasoner** | **BSD-2-Clause** ($0) | **100% Free Forever** (Comprehensive OWL 2 ontology modeling, taxonomy structuring & HermiT reasoning) | Stanford's premier open-source desktop ontology editor and knowledge acquisition system for OWL and RDF knowledge graphs. |
| **[Apache Jena](https://github.com/apache/jena)** (`apache/jena`) | [![Stars](https://img.shields.io/github/stars/apache/jena?style=social&color=white)](https://github.com/apache/jena/stargazers) | **Java W3C Semantic Web Framework** | **Apache-2.0** ($0) | **100% Free Forever** (Includes Jena TDB triple store, Fuseki SPARQL server & OWL inference reasoners) | Comprehensive Java framework for building semantic web and linked data applications, equipped with the Fuseki SPARQL server. |
| **[ROBOT](https://github.com/ontodev/robot)** (`ontodev/robot`) | [![Stars](https://img.shields.io/github/stars/ontodev/robot?style=social&color=white)](https://github.com/ontodev/robot/stargazers) | **OBO / OWL Automated Ontology CI/CD** | **BSD-3-Clause** ($0) | **100% Free Forever** (CLI tool for ontology automation, reasoning, conversion, merging & validation) | Command-line tool for automating ontology development workflows, linting, format conversion, and semantic validation. |
| **[SciGraph](https://github.com/SciGraph/SciGraph)** (`SciGraph/SciGraph`) | [![Stars](https://img.shields.io/github/stars/SciGraph/SciGraph?style=social&color=white)](https://github.com/SciGraph/SciGraph/stargazers) | **Ontology to Neo4j Graph Transformer** | **Apache-2.0** ($0) | **100% Free Forever** (Transforms OBO/OWL ontologies into queryable Neo4j labeled property graphs) | Tool for converting complex biomedical and scientific ontologies into Neo4j graph instances for rapid graph traversal and NLP lookup. |

---

## 📈 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Enterprise-Knowledge-Graphs-Automated-Ontologies&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Enterprise-Knowledge-Graphs-Automated-Ontologies&type=date&legend=top-left)

---

## 🛠️ How to Contribute

Contributions are welcome from semantic engineers, data architects, and AI researchers!

1. **Fork the Repository** to your GitHub account.
2. **Add or Update an Entry**: Ensure SaaS entries include verified, specific pricing tiers and free limits; open-source projects should have active repositories with proper licenses.
3. **Submit a Pull Request** with a concise description of your additions.

---

## 💖 Support & Sponsorship

Thank you for exploring and building with this community directory! If you find this curation helpful for your enterprise AI architecture, semantic engineering research, or GraphRAG pipelines:

- ⭐ **Star this repository** to help others discover it on GitHub.
- 🍴 **Fork and share** with your engineering and data science colleagues.
- ☕ **Sponsor & Buy a Coffee**: If you'd like to support ongoing curation and maintenance, visit the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007). Your support is immensely appreciated!

---

## ⚠️ Disclaimer

*All product names, logos, and brands are property of their respective owners. Pricing, free tier limits, and feature sets are gathered from official public documentation and cloud marketplace listings as of November 2026 and are subject to change by their respective vendors.*
