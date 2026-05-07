# Characterising Systematic Biases in Context-Specific Protein Interaction Networks Inferred from Single-Cell Transcriptomes

In this report, we utilise scNET (https://doi.org/10.1038/s41592-025-02627-0) as a model integrative method to establish an analytical framework for characterising systematic biases in single-cell data reconstruction and cell-type-specific PPI inference. Specifically, we aim to determine whether these biases reflect genuine biological signals or are simply methodological artefacts.

Here, we present a consistent analytical framework across three aspects:\
(1) **Preservation of biologically coherent cell clusters**, assessed via Uniform Manifold Approximation and Projection (UMAP) dimensionality reduction;\
(2) **Fidelity of cluster-specific transcriptional signatures**, via differential gene expression (DGE) analysis and pathway enrichment to evaluate the functional coherence of gene co-representation in the reconstructed space; and\
(3) **Gene-gene relationship inference**, via comparing scNET-inferred gene importance (rank) with shifts in network neighbourhoods (edge weights) following integration with transcriptomics data compared to the context-agnostic baseline network (termed as “rank-weight analysis”). 

Together, these analyses determine whether integrating scRNA-seq and PPI information produces network-informed representations that accurately reflect biologically meaningful cellular organisation.

<img width="4800" height="2700" alt="MSci F1" src="https://github.com/user-attachments/assets/6cbfe6d4-d76c-4b2d-9975-b5187aeaee4d" />

