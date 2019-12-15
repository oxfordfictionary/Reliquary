# Architecture

Abstract:
- `Corpus Providers`
  - Sources for Large-Scale Corpus'
  - Sources for localized Corpus'
- `Natural Language Processing (NPL) Manager`
  - Parsing/Segmentation Strategy
  - Feature Extraction (TF-IDF, SynNet, etc)
  - Domain-Oriented Model for corpus(')
- `Machine Learning (ML) Manager`
  - Transformation & Preperation
  - Supervised/Unsupervised Algorithms
  - Model Extraction & Storage
- `Presentation` (Web Site, Terminal, etc)

Logical:
- Cloud Container Orchestrator (GCloud, Docker Swarm, etc)
- Distributed Jobs (Dispy, Spark, etc)
- GFX Accelerated Job Nodes
- Cloud Storage Service (Mongo Altas, Firestore, etc)
- Artifact Storage (S3, GCloud Storage, Azure Storage, etc)
