# Awesome-Enterprise-Knowledge-Graphs-Automated-Ontologies

<p align="center">

  <img src="./assets/banner.svg" alt="Top Enterprise Knowledge Graphs & Automated Ontologies" width="100%" />

</p>



<p align="center">

  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>

  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>

  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>

  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>

</p>



# 🕸️ Top Enterprise Knowledge Graphs & Automated Ontologies



**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  

*Focused on Graph Databases (LPG & RDF/OWL), LLM-Driven Automated Ontology Induction, GraphRAG Memory Engines & Semantic Reasoning*  

**Last updated: November 2026**



This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Enterprise Knowledge Graphs & Automated Ontologies**. These tools power native Labeled Property Graph (LPG) and W3C RDF/SPARQL/OWL triple stores, LLM-powered automated ontology generation (`NVIDIA/auto-ontology`, `GraphRAG`), GraphRAG enterprise memory engines (`Graphiti`, `Cognee`, `LightRAG`), and embedded graph analytics for enterprise AI architects, semantic engineers, and data scientists.



**Examples** include Amazon Neptune (AWS), Neo4j Aura, TigerGraph Cloud, Cambridge Semantics (Altair Anzo), ArangoDB Oasis (ArangoGraph), Memgraph Cloud, Stardog Cloud, Katana Graph, Dgraph Cloud, and TypeDB / Grakn Core (Vaticle) (the category leaders).



**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for automated ontology induction (`NVIDIA/auto-ontology`, `GraphRAG`, `Graphiti`, `Cognee`, `LightRAG`), open-source graph databases (`Neo4j Community`, `Memgraph`, `Kùzu`, `Dgraph`, `Apache Jena`, `Oxigraph`, `NebulaGraph`, `JanusGraph`, `TypeDB`), and ontology/OWL toolkits (`Protégé`, `ROBOT`, `RDFLib`, `PyKEEN`) — ideal for AI teams building grounded, hallucination-resistant enterprise knowledge systems without proprietary lock-in.



🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)

- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)

- [💻 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#️-how-to-contribute)

- [⚠️ Disclaimer](#️-disclaimer)

- [💖 Support & Thank You](#-support--thank-you)



## 📊 Sector Overview & Market Dynamics

The global Graph Database & Enterprise Knowledge Graph market is valued at approximately **$3.8B–$4.9B+ in 2026** (projected to exceed $15B+ by 2032 at a ~22%–28% CAGR), driven by high enterprise demand for **GraphRAG**, neuro-symbolic reasoning, and automated LLM ontology generation. The market dynamics exhibit **moderate to high concentration** at the enterprise operational graph tier (led by hyperscalers like AWS Neptune and specialized category leaders like Neo4j), alongside a **highly fragmented, rapidly innovating open-source ecosystem** pioneering automated ontology induction and modular graph memory engines.

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



## 💻 Open-Source GitHub Projects



| Project | License / Hosting Cost | Free Tier / Self-Hosted Limit | Description |

| :--- | :--- | :--- | :--- |

| **[NVIDIA Auto-Ontology (`NVIDIA/auto-ontology`)](https://github.com)** | **Open-Source** ($0 local/GPU pipeline; BYO NVIDIA NIM or LLM endpoints) | **100% Free forever** (Unlimited automated ontology induction, entity/relation schema synthesis, and KG construction from text) | NVIDIA's open-source automated ontology generation toolkit that induces structured domain ontologies and knowledge graphs directly from unstructured documents. |
