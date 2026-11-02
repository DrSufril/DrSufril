# Cow image segmentation

This paper presents an enhanced Mask R-CNN framework for separating individual cows from images. Instance-level masks can support later measurements and behaviour-analysis pipelines, but segmentation alone is not behaviour recognition.

## Read and cite the paper

**Enhanced Deep Learning Framework for Cow Image Segmentation**  
Rotimi-Williams Bello, Ahmad Sufril Azlan Mohamed, Abdullah Zawawi Talib, Daniel A. Olubummo and O. Charles Enuma  
*IAENG International Journal of Computer Science* 48(4), 1182–1191 (2021)

[Publisher issue and citation](https://www.iaeng.org/IJCS/issues_v48/issue_4/index.html) · [Publisher-hosted PDF](https://www.iaeng.org/IJCS/issues_v48/issue_4/IJCS_48_4_38.pdf) · [Download BibTeX](citation.bib)

No DOI is listed on the publisher issue page; the stable publisher URL is used instead.

## Plain-language summary

When several cows appear in one image, a system must first determine which pixels belong to each animal. The proposed framework combines Mask R-CNN with Generalized Color Fourier Descriptors to improve individual-cow segmentation.

## Method and reported result

- Instance segmentation using an enhanced Mask R-CNN framework
- Generalized Color Fourier Descriptors used to strengthen colour and shape representation
- Reported mean Average Precision: 0.93
- Intended as a computer-vision component for precision-livestock workflows

## Limits and future work

The reported mAP belongs to the study dataset and evaluation protocol; it is not a behaviour-recognition or welfare score. Performance can change with breed, lighting, background, crowding, camera view and occlusion. Future work should include external datasets, cross-farm validation, uncertainty analysis and downstream tracking tests.

## Media and reusable resources

- [Author-created visual explainer on ResearchGate](https://www.researchgate.net/publication/417272389_Author-created_visual_explainer_cow_segmentation_supporting_behaviour_analysis_2026_concept_illustration_not_experimental_results)
- [COCO dataset portal](https://cocodataset.org/#download) — a general object-detection resource, not the study dataset
- [Matterport Mask R-CNN](https://github.com/matterport/Mask_RCNN) — a general implementation reference, not claimed as the study code
- No public study-specific dataset, weights or source-code release is claimed here.

[All research pages](../README.md) · [Google Scholar profile](https://scholar.google.com/citations?user=AHj1bTgAAAAJ&hl=en) · [Discuss collaboration](mailto:sufril@usm.my)
