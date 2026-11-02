# 2D human pose estimation and worker posture analysis

This open-access survey maps deep-learning approaches for locating human body joints in images. It covers body representations, estimation pipelines, datasets, model components and unresolved research challenges.

## Read and cite the paper

**A Survey on Deep Learning-Based 2D Human Pose Estimation Models**  
Sani Salisu, Ahmad Sufril Azlan Mohamed, Mohd Hafiidz Jaafar, Ainun Syarafana Binti Pauzi and Hussain A. Younis  
*Computers, Materials & Continua* 76(2), 2385–2400 (2023)  
DOI: [10.32604/cmc.2023.035904](https://doi.org/10.32604/cmc.2023.035904)

[Open-access publisher article](https://www.techscience.com/cmc/v76n2/53975) · [Download BibTeX](citation.bib)

The article is published under the Creative Commons Attribution 4.0 licence shown on the publisher page.

## Plain-language summary

Human-pose systems estimate the locations of joints such as shoulders, elbows, hips and knees. The survey explains how deep-learning models represent the body, process images and report keypoints, helping researchers select methods and datasets for new applications.

## Survey scope

- Human-body modelling and the main pose-estimation stages
- Top-down and bottom-up 2D pose pipelines
- Core components of deep-learning pose systems
- Common keypoint formats and datasets
- Comparison of influential approaches and research directions

## Connection to the software

The survey provides background for the later Human Pose Analytics application. That application uses existing person-detection and pose models with posture rules; the survey does not validate those later rules.

**Workflow:** image or video → person detection → 2D keypoints → posture geometry → reviewable output

[Methods, demonstration image and documented evaluation](../../showcase/human-pose.md) · [Private source repository—existing access required](https://github.com/DrSufril/human-pose)

## Limits and future work

A survey synthesises published work rather than validating every model in a shared experiment. Benchmark results may not transfer to workplace footage, disabled populations, unusual viewpoints or occlusion. Future work identified by the paper includes broader datasets and more capable multi-training approaches. Site-specific validation remains necessary before using posture outputs for operational safety decisions.

## Reusable resources

The publisher provides open-access HTML/PDF and citation export. No new dataset or trained model was released with this survey. Implementations and datasets discussed in the article retain their own licences and citation requirements.

[All research pages](../README.md) · [Promotion schedule](../PROMOTION-SCHEDULE.md) · [Discuss collaboration](mailto:sufril@usm.my)
