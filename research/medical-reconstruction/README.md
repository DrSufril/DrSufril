# 3D medical-image reconstruction and mesh processing

This study investigates how smoothing and mesh-simplification parameters affect surface reconstruction from high-resolution medical images. It examines reconstruction accuracy, execution time and mesh complexity in bioceramic bone-defect imaging.

## Read the paper

**Effects of Different Parameter Settings for 3D Data Smoothing and Mesh Simplification on Near Real-Time 3D Reconstruction of High Resolution Bioceramic Bone Void Filling Medical Images**  
*Sensors* (2021) · DOI: [10.3390/s21237955](https://doi.org/10.3390/s21237955)

[Read the published article](https://pmc.ncbi.nlm.nih.gov/articles/PMC8659505/) · [Download BibTeX](citation.bib)

The links lead to publisher or established full-text hosts. Please use the publisher’s citation export for the complete bibliographic record.

## How the research connects to the software

The research archive includes a recovered Qt/C++/CUDA visualization application with documented upstream attribution. The paper concerns high-resolution micro-CT reconstruction; the application’s MRI/CT naming does not establish it as the exact experimental code used in the article.

**Workflow:** Medical image stack → smoothing → surface reconstruction → mesh simplification → visualization

## Explore and reuse

[3DMRIRendering application archive summary](../../showcase/research-portfolio.md#mri-reconstruction)

Use the paper to understand the parameter study and the accuracy–speed–mesh trade-off. The private guide describes the recovered application and its build requirements.

[Private source repository — existing access required](https://github.com/DrSufril/mri-reconstruction)

## Limits

The recovered Windows/Qt/CUDA build has not been revalidated. The archive is a research resource and does not establish clinical performance.

Cite the linked paper when using its findings or methods. For any software actually used, also credit the relevant implementation, version and upstream contributors.

[Discuss research or collaboration](mailto:sufril@usm.my) · [All five research pages](../README.md) · [Profile](../../README.md)
