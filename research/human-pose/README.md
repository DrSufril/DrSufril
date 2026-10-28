# 2D human pose estimation and worker posture analysis

This survey introduces deep-learning approaches to locating human body joints in images. It covers body representations, estimation pipelines, datasets and challenges for researchers choosing a 2D pose approach.

## Read the paper

**A Survey on Deep Learning-Based 2D Human Pose Estimation Models**  
*Computers, Materials & Continua* (2023) · DOI: [10.32604/cmc.2023.035904](https://doi.org/10.32604/cmc.2023.035904)

[Read the published article](https://www.techscience.com/cmc/v76n2/53975/html) · [Download BibTeX](citation.bib)

The links lead to publisher or established full-text hosts. Please use the publisher’s citation export for the complete bibliographic record.

## How the research connects to the software

The survey provides background for the later Human Pose Analytics application. The application uses existing detection and pose models with posture rules; the survey does not validate those later rules.

**Workflow:** Images or video → person detection → 2D keypoints → posture geometry → reviewable outputs

## Explore and reuse

[Methods, demonstration image and documented evaluation](../../showcase/human-pose.md)

Use the survey as a starting point for comparing pose estimation approaches. The walkthrough shows how keypoints become reviewable posture descriptions.

[Private source repository — existing access required](https://github.com/DrSufril/human-pose)

## Limits

The documented posture baseline remains unvalidated for safety decisions. Site-specific testing is needed before interpreting outputs operationally.

Cite the linked paper when using its findings or methods. For any software actually used, also credit the relevant implementation, version and upstream contributors.

[Discuss research or collaboration](mailto:sufril@usm.my) · [All five research pages](../README.md) · [Profile](../../README.md)
