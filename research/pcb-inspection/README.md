# PCB defect detection and inspection research

This study explores modifications to YOLOv8 for detecting defects on printed circuit boards, evaluating the model on HRIPCB and DeepPCB. The article includes experiments, ablations and discussion of computational trade-offs.

## Read the paper

**YOLOv8-DEE: a high-precision model for printed circuit board defect detection**  
*PeerJ Computer Science* (2024) · DOI: [10.7717/peerj-cs.2548](https://doi.org/10.7717/peerj-cs.2548)

[Read the published article](https://pmc.ncbi.nlm.nih.gov/articles/PMC11888845/) · [Download BibTeX](citation.bib)

The links lead to publisher or established full-text hosts. Please use the publisher’s citation export for the complete bibliographic record.

## How the research connects to the software

The recovered pcb-aoi-ocr repository contains annotation parsing, crop preparation and dataset-analysis scripts. It is not the YOLOv8-DEE implementation. For the published model code, use the article’s own supplement.

**Workflow:** PCB images → labelled datasets → defect detection → benchmark evaluation

## Explore and reuse

[Published model code supplement](https://doi.org/10.7717/peerj-cs.2548/supp-1) · [Recovered preparation-tool summary](../../showcase/research-portfolio.md#pcb-aoi-ocr)

Read the paper and its supplemental program files to investigate the published detector. Treat the recovered preparation scripts as a separate resource.

[Private source repository — existing access required](https://github.com/DrSufril/pcb-aoi-ocr)

## Limits

Reported benchmark results belong to the article’s experiments and are not a new evaluation of the archived scripts. Model size and inference cost remain relevant trade-offs.

Cite the linked paper when using its findings or methods. For any software actually used, also credit the relevant implementation, version and upstream contributors.

[Discuss research or collaboration](mailto:sufril@usm.my) · [All five research pages](../README.md) · [Profile](../../README.md)
