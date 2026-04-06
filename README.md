# Virtual Cell Modelling Efforts

A public ledger of research and progress in virtual cell modelling.

## Overview

Virtual cell modelling has become a major focus in the 21st century. While earlier generations might have viewed this as the pinnacle of scientific achievement, current researchers recognize the complexities and challenges that remain. The field has seen rapid progress, particularly with the application of deep learning to learn and predict cell states.

## Timeline of Progress

### Early 2022 - 2023: Foundation Models & Transformers
The initial wave of virtual cell models applied standard transformer architectures to RNA-seq datasets to learn and predict cell states.

*   **[scGPT: toward building a foundation model for single-cell multi-omics using generative AI](https://www.nature.com/articles/s41592-024-02201-0)** (Nature Methods, 2024)
    *   *Note:* Early versions released around 2023. Used a standard transformer architecture for single-cell multi-omics.
*   **[Transfer learning enables predictions in network biology (Geneformer)](https://www.nature.com/articles/s41586-023-06139-9)** (Nature, 2023)
    *   A context-aware, attention-based deep learning model pretrained on single-cell transcriptomes.

### 2024: Benchmarking & Critique
Research began to scrutinize the performance of autoregressive models, establishing baselines that challenged the efficacy of complex AI models compared to simpler statistical methods.

*   **[Assessing the limits of zero-shot foundation models in single-cell biology](https://www.biorxiv.org/content/10.1101/2023.10.16.561085v1)** (bioRxiv, 2023/2024)
    *   Demonstrated that autoregressive models often did not outperform mean baselines (e.g., using a sum of RNA-seq counts from training data) for identifying test samples.

### 2025: Context, Perturbations & New Modalities
The field pushed towards "virtual cells" becoming mainstream, with a focus on context generalization, perturbations, and incorporating new data modalities beyond just RNA-seq.

*   **[TxPert: Leveraging Biochemical Relationships for Out-of-Distribution Transcriptomic Perturbation Prediction](https://arxiv.org/abs/2505.14919)** (arXiv, 2025)
*   **[Predicting cellular responses to perturbation across diverse contexts with State](https://arcinstitute.org/manuscripts/State)** (bioRxiv, 2025)
    *   Also available on [bioRxiv](https://www.biorxiv.org/content/10.1101/2025.06.26.661135v1).
*   **[Arc Institute Virtual Cell Challenge](https://virtualcellchallenge.org)** (Launched June 2025)
    *   A community challenge to benchmark models on predicting cell responses to perturbations, specifically focusing on context generalization in H1 human embryonic stem cells.

### Late 2025 / Early 2026: Future Directions
The next frontier involves more advanced generative approaches and large-scale community models.

*   **[Latent Diffusion Models - scDLM](https://arxiv.org/abs/2511.02986v1)**: Moving beyond transformers to diffusion-based generation of cell states.
*   **[STACK](https://www.biorxiv.org/content/10.64898/2026.01.09.698608v1.full)**: In context learning in virtual cell state modelling. 
*   **[SEDD-AIVC]( )**: a discrete diffusion modelling approach for gene expression. 

---

## Additional Resources & Releases

*   **[How to build the virtual cell with artificial intelligence: Priorities and opportunities](https://www.sciencedirect.com/science/article/pii/S0092867424013321?via%3Dihub)**
*   **[Predicting transcriptional outcomes of novel multigene perturbations with GEARS](https://www.nature.com/articles/s41587-023-01905-6)**
*   **[TranscriptFormer: A Generative Cross-Species Cell Atlas Across 1.5 Billion Years of Evolution](https://chanzuckerberg.com/blog/transcriptformer-model-overview/)**
*   **[Tahoe-100M: A Giga-Scale Single-Cell Perturbation Atlas](https://www.biorxiv.org/content/10.1101/2025.02.20.639398v3)**
*   **[Noetik's blogs on use of virtual cells](https://www.noetik.blog/p/how-do-you-use-a-virtual-cell-to-6c6)**
*   **[Xaira therapeutic's dataset release](https://www.biorxiv.org/content/10.1101/2025.06.11.659105v1)**
