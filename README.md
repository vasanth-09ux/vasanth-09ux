# Hi there, I'm Vasanth 

**Software Engineering Student | AWS Certified Solutions Architect – Associate | Cloud & AI/ML**  
*Integrated M.Tech in Software Engineering @ Vellore Institute of Technology (VIT), Chennai (2022–2027)*

[![GitHub Profile](https://img.shields.io/badge/GitHub-vasanth--09ux-181717?logo=github)](https://github.com/vasanth-09ux)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vasanth%20Vijayaraghavan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vasanth-vijayaraghavan/)
[![AWS Certified](https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect%20--%20Associate-FF9900?logo=amazon-aws&logoColor=white)](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
[![Degree](https://img.shields.io/badge/Degree-Integrated%20M.Tech%20Software%20Engineering-blue)](https://chennai.vit.ac.in/)

---

## 📌 About Me

I am a software engineering postgraduate specializing in **Cloud Architecture**, **Applied Machine Learning**, and **Generative AI Systems**. My focus centers on building reliable, resource-efficient AI pipelines and scalable cloud infrastructure—ranging from optimizing Large Language Model inference under constrained consumer hardware to processing satellite remote sensing imagery.

- 🎓 **Education:** Integrated M.Tech in Software Engineering, Vellore Institute of Technology (VIT), Chennai (Expected graduation: 2027).
- ☁️ **Cloud Certification:** AWS Certified Solutions Architect – Associate.
- 🔬 **Core Interests:** Cloud Systems Architecture, Retrieval-Augmented Generation (RAG), LLM Inference Efficiency, Geospatial Remote Sensing, Distributed Backend Engineering.
- 💼 **Engineering Focus:** Architecting reproducible, benchmarked, production-conscious software solutions with empirical validation.

---

## 🚀 Featured Engineering Projects

### 🧠 [Adaptive-RAG: Embedding-Informed Retrieval-Augmented Generation (EI-ARAG)](https://github.com/vasanth-09ux/adaptive-rag-ei-arag)
*PyTorch | Hugging Face Transformers | FAISS | Qwen2.5-1.5B | Hardware-Constrained ML*

An empirical characterization and practical framework for dynamic retrieval routing executed on a consumer 4GB GPU (NVIDIA GTX 1650).
- **Core Mechanism:** Intercepts early internal transformer hidden states (**Layer 1**) to dynamically route queries through a lightweight 49,250-parameter CPU MLP classifier ($<1\text{ ms}$ inference).
- **Benchmarked Impact:** Delivers **64.00% accuracy** with a **76.11% latency reduction** ($6,595.58\text{ ms}$ saved per query) compared to standard Always-RAG, routing 93% of queries parametrically.
- **Routing Reliability:** Among the 7 queries routed to retrieval, the system achieved **5 accuracy improvements, 2 neutral outcomes, and 0 regressions**.
- **Key Empirical Discovery:** Formally established that dense vector retrieval ($22.85\text{ ms}$, 0.26% of Always-RAG latency) is not the RAG bottleneck—autoregressive prompt context processing accounts for $>95\%$ of total execution duration.
- **Artifacts:** Includes interactive desktop GUI chat, routing explainability inspector, and evaluation dashboard.

---

### 🛰️ [Automated Harmful Algal Bloom (HAB) Detection via Satellite Remote Sensing](https://github.com/vasanth-09ux/algal-bloom-detection)
*Google Earth Engine | Copernicus Sentinel-2 MSI | Geemap | Rasterio | Scikit-Learn | SciPy*

An unsupervised geospatial machine learning pipeline for exploratory mapping and anomaly delineation of potential algal blooms across coastal and inland water bodies.
- **Multispectral Ingestion:** Direct integration with Google Earth Engine (`COPERNICUS/S2_SR_HARMONIZED`) for cloud-filtered Sentinel-2 Level-2A surface reflectance data.
- **Spectral Pipeline:** Automated water body extraction using **NDWI** with $3\times3$ binary morphological opening/closing, followed by **NDVI** and physics-based **Floating Algae Index (FAI)** with SWIR-1 baseline interpolation.
- **Unsupervised Anomaly Mapping:** Implements multi-spectral **K-Means clustering ($k=4$)** and an empirical bloom likelihood scoring heuristic that ranks clusters based on NIR scattering, Green/Blue ratio, and FAI response.
- **Spatial Diagnostics:** Produces a 6-panel spatial diagnostic visualization distinguishing potential bloom anomalies from clean water and terrestrial land.

---

## 🛠️ Technical Skills

| Domain | Verified Technologies & Frameworks |
| :--- | :--- |
| **Programming Languages** | Python, C++, Java, SQL, Bash / Shell |
| **Cloud & DevOps** | Amazon Web Services (AWS - Solutions Architect Associate), Docker, Linux / Unix, Git |
| **Machine Learning & Deep Learning** | PyTorch, Hugging Face Transformers, Scikit-Learn, NumPy, SciPy |
| **Vector Search & Retrieval** | FAISS, BGE Embeddings, Dense Passage Retrieval (DPR), RAG Pipelines |
| **Geospatial & Remote Sensing** | Google Earth Engine (GEE API), geemap, Rasterio, GDAL, GeoTIFF processing |
| **Software Architecture** | Clean Architecture, Modular API Design, Hardware Resource Profiling, Desktop GUIs |

---

## 📊 Engineering & Design Philosophy

- **Measurement Over Hype:** Every system metric is benchmarked, profiled, and reported with exact standard deviations, hardware constraints, and failure modes.
- **Resource Consciousness:** Designing architectures that maximize performance on cost-effective, constrained hardware before scaling horizontally.
- **Zero-Credential Hygiene:** Clean repository isolation with zero hardcoded API keys, environment parameterization, and strict data leakage controls.

---

## 📬 Connect With Me

- **GitHub:** [@vasanth-09ux](https://github.com/vasanth-09ux)
- **LinkedIn:** [linkedin.com/in/vasanth-vijayaraghavan](https://www.linkedin.com/in/vasanth-vijayaraghavan/)
