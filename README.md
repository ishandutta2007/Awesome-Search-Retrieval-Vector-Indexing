# Awesome-Search-Retrieval-Vector-Indexing

# Top Search & Retrieval Vector Indexing Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Vector Databases, Hybrid Lexical/Semantic Search Engines, Incremental Indexing Pipelines & ANN Libraries*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted search & vector platforms** and **open-source GitHub projects** for **Search & Retrieval Vector Indexing**. These tools power high-dimensional Approximate Nearest Neighbor (ANN) vector search, hybrid BM25 + dense/sparse retrieval, incremental data-to-index transformation pipelines, and sub-millisecond full-text search for RAG, AI agents, and semantic discovery.

**Examples** include cocoindex-io/cocoindex, Qdrant, Weaviate, Milvus, Chroma, Vespa, Typesense, Meilisearch, OpenSearch, LanceDB, pgvector, FAISS, USearch, Pinecone, Zilliz Cloud, Elastic Cloud, and Algolia.

**Open-source emphasis**: This list heavily expands on active open-source Rust/C++/Go vector databases, incremental indexing frameworks, hybrid search engines, Postgres vector extensions, and embedded ANN libraries — ideal for AI engineers, search architects, and developers building fast, sovereign retrieval pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Pinecone](https://pinecone.io)**  
  Fully managed serverless vector database platform engineered for low-latency similarity search, metadata filtering, sparse-dense hybrid indexes, and enterprise RAG workloads.

- **[Zilliz Cloud](https://zilliz.com)**  
  Managed cloud vector database service built by the creators of Milvus offering auto-scaling clusters, tiered storage, and GPU-accelerated indexing.

- **[Qdrant Cloud](https://qdrant.io)**  
  Managed cloud offering for the Rust-based Qdrant vector search engine featuring hybrid cloud deployment, payload filtering, and scalar/binary quantization.

- **[Weaviate Cloud](https://weaviate.io)**  
  Managed AI-native vector database service combining hybrid keyword/vector search, built-in vectorizer modules, and multi-tenant isolation.

- **[Elastic Cloud](https://elastic.co)**  
  Hosted Elasticsearch and Observability/Search platform providing BM25 full-text search, ELSER sparse retrieval, dense vector HNSW/BBQ indexing, and semantic reranking.

- **[Algolia](https://algolia.com)**  
  Cloud-hosted search-as-a-service and NeuralSearch platform delivering instant typo-tolerant keyword and semantic vector discovery for web and mobile apps.

- **[Typesense Cloud](https://typesense.org)**  
  Managed hosting service for Typesense offering globally distributed, low-latency typo-tolerant and vector search clusters.

- **[Meilisearch Cloud](https://meilisearch.com)**  
  Fully managed cloud deployment service for Meilisearch providing fast instant search, hybrid semantic retrieval, and automated scaling.

- **[Turbopuffer](https://turbopuffer.com)**  
  Serverless vector and full-text search engine built from scratch on object storage (S3/GCS) for massive-scale, low-cost multi-tenant indexing.


## Open-Source GitHub Projects

- **[CocoIndex (cocoindex-io/cocoindex)](https://github.com)**  
  Ultra-fast, open-source data transformation and incremental indexing framework for AI powered by a Rust core engine — tracking data lineage and continuously syncing source changes into vector and graph databases.

- **[Qdrant (qdrant/qdrant)](https://github.com)**  
  High-performance, open-source vector similarity search engine and database written in Rust with rich JSON payload filtering, sparse vectors, and quantization.

- **[Milvus (milvus-io/milvus)](https://github.com)**  
  Cloud-native, distributed open-source vector database engineered for billion-scale embedding storage, hybrid search, and GPU/disk-accelerated indexing (DiskANN, HNSW, IVF).

- **[Weaviate (weaviate/weaviate)](https://github.com)**  
  Open-source vector database written in Go supporting hybrid BM25F + vector search, GraphQL/gRPC APIs, and modular generative/embedding pipelines.

- **[Chroma (chroma-core/chroma)](https://github.com)**  
  Developer-friendly, open-source AI-native embedding database offering an ergonomic Python/JS API for local embedded or client-server semantic retrieval.

- **[Vespa (vespa-engine/vespa)](https://github.com)**  
  Battle-tested, open-source big data serving engine written in C++/Java combining real-time vector ANN search, lexical BM25, tensor ranking, and ML model inference at massive scale.

- **[Typesense (typesense/typesense)](https://github.com)**  
  Fast, typo-tolerant open-source search engine written in C++ supporting instant full-text search, semantic vector search, conversational RAG, and geo-search in RAM.

- **[Meilisearch (meilisearch/meilisearch)](https://github.com)**  
  Lightning-fast, hyper-relevant open-source search engine written in Rust featuring out-of-the-box typo tolerance, faceted filtering, and hybrid semantic search.

- **[OpenSearch (opensearch-project/OpenSearch)](https://github.com)**  
  Community-driven, Apache-2.0 open-source distributed search and analytics suite (forked from Elasticsearch) supporting k-NN vector search, neural sparse retrieval, and hybrid pipelines.

- **[LanceDB (lancedb/lancedb)](https://github.com)**  
  Developer-friendly, serverless open-source vector database built in Rust on top of the columnar Lance format for zero-copy multimodal and disk-based ANN retrieval.

- **[pgvector (pgvector/pgvector)](https://github.com)**  
  Open-source vector similarity search extension for PostgreSQL enabling ACID-compliant HNSW and IVFFlat vector indexing alongside relational SQL joins and full-text search.

- **[FAISS (facebookresearch/faiss)](https://github.com)**  
  Meta's foundational open-source C++/CUDA library for efficient similarity search and clustering of dense vectors across CPU and multi-GPU hardware.

- **[USearch (unum-cloud/USearch)](https://github.com)** & **[hnswlib (nmslib/hnswlib)](https://github.com)**  
  Smaller, single-header/multi-language C++/Rust/Python libraries implementing fast HNSW approximate nearest neighbor search with custom metrics and quantization.

### Additional Strong Open-Source Options

- **[sqlite-vec (asg017/sqlite-vec)](https://github.com)** — Pure-C, zero-dependency vector search SQLite extension running anywhere SQLite runs (browsers, mobile, edge, CLI).
- **[Tantivy (quickwit-oss/tantivy)](https://github.com)** & **[Quickwit (quickwit-oss/quickwit)](https://github.com)** — Rust-native full-text search engine library (inspired by Apache Lucene) and cloud-native search engine built directly on object storage.
- **[Marqo (marqo-ai/marqo)](https://github.com)** — End-to-end open-source tensor search engine combining multimodal embedding generation and vector indexing in a single API.
- **[Vald (vdaas/vald)](https://github.com)** — Highly scalable, cloud-native distributed ANN vector search engine built on Kubernetes and NGT.
- **[txtai (neuml/txtai)](https://github.com)** — All-in-one open-source embeddings database for semantic search, LLM orchestration, and language model workflows.
- **[FlashRank (PrithivirajDamodaran/FlashRank)](https://github.com)** & **[rerankers (AnswerDotAI/rerankers)](https://github.com)** — Lightweight open-source cross-encoder and ColBERT reranking libraries for boosting top-k retrieval precision.

**Frameworks for building custom systems**: Combine **CocoIndex** for continuous incremental data transformation and chunking with **Qdrant** or **pgvector** for hybrid vector/metadata storage, **Tantivy** / **Meilisearch** for lexical BM25 search, and **FlashRank** for fast second-stage reranking.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Vector indexes (HNSW, IVF, flat) can consume substantial RAM and disk IOPS at scale; evaluate scalar/binary quantization (`SQ8`, `BQ`) or disk-backed engines (`LanceDB`, `DiskANN`) for large embedding collections.
- Self-hosted vector and search databases should never be exposed directly to the public internet without API key authentication, TLS encryption, and network firewall rules.

---

**Made for AI engineers, search architects, data engineers, and open-source builders.**  
Let's make search, retrieval, and vector indexing faster, incremental, and open to everyone.
