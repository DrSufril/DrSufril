# Cattle behaviour recognition from video

This study evaluates deep-learning detectors for recognising four observable cattle behaviours—eating, drinking, active and inactive—from ranch video. It is a practical starting point for researchers studying non-contact livestock monitoring.

## Read and cite the paper

**Behavior Recognition of Group-ranched Cattle from Video Sequences using Deep Learning**  
Rotimi-Williams Bello, Ahmad Sufril Azlan Mohamed, Abdullah Zawawi Talib, Salisu Sani and Mohd Nadhir Ab Wahab  
*Indian Journal of Animal Research* 56(4), 505–512 (2022)  
DOI: [10.18805/IJAR.B-1369](https://doi.org/10.18805/IJAR.B-1369)

[Publisher record](https://arccjournals.com/journal/indian-journal-of-animal-research/B-1369) · [Open-access copy on Zenodo](https://zenodo.org/record/5255027) · [Download BibTeX](citation.bib)

## Plain-language summary

Video can reduce the need for continuous manual observation of livestock. The study compared four deep-learning models for locating cattle and classifying visible activity. Mask R-CNN produced the strongest reported results and ran at approximately 20 frames per second in the study setup.

## Method and reported results

- Ranch video of six Keteku and Muturu cattle
- Four behaviour classes: eating, drinking, active and inactive
- Comparison of Mask R-CNN, Faster R-CNN, YOLOv3 and YOLOv4
- Reported Mask R-CNN recognition accuracies: 93.34%, 88.03%, 93.51% and 93.38%
- Reported processing speed: approximately 20 fps

## Limits and future work

The sample was small and restricted to two breeds, four behaviours and one acquisition setting. The reported performance should not be assumed to transfer to other farms, camera positions, weather, breeds or welfare decisions without independent validation. Useful follow-up work includes multi-farm testing, longer observation periods, occlusion analysis and explicit uncertainty reporting.

## Media and reusable resources

- [Author-created video explainer on ResearchGate](https://www.researchgate.net/publication/417272557_Author-created_video_explainer_-_study_overview_and_limitations_2026_produced_after_publication)
- The public paper describes the study; no project-specific dataset, trained weights or source-code release is claimed here.
- General-purpose implementations should be credited separately from this paper.

[All research pages](../README.md) · [Google Scholar profile](https://scholar.google.com/citations?user=AHj1bTgAAAAJ&hl=en) · [Discuss collaboration](mailto:sufril@usm.my)
