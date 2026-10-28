# ErgoMotion and 3D ergonomic assessment

This review examines monocular 3D pose methods and their use in REBA ergonomic assessment. It gives readers a route into the methods, challenges and research questions behind camera-based posture analysis.

## Read the paper

**Monocular 3D Human Pose Estimation for REBA Ergonomics: A Critical Review of Recent Advances**  
*Computers, Materials & Continua* (2025) · DOI: [10.32604/cmc.2025.064250](https://doi.org/10.32604/cmc.2025.064250)

[Read the published article](https://www.sciopen.com/article/10.32604/cmc.2025.064250) · [Download BibTeX](citation.bib)

The links lead to publisher or established full-text hosts. Please use the publisher’s citation export for the complete bibliographic record.

## How the research connects to the software

The paper is a review providing research context for ErgoMotion. It is not a publication validating the current desktop application or a claim that the application reproduces every reviewed method.

**Workflow:** Video → pose estimation → joint angles → REBA with task-context inputs → human review

## Explore and reuse

[Application walkthrough and existing demonstration images](../../showcase/ergomotion.md)

Start with the review to select pose methods and evaluation criteria. The application walkthrough explains camera modes, review tools and measurement limits.

[Private source repository — existing access required](https://github.com/DrSufril/Ergomotion)

## Limits

Camera calibration, occlusion and estimated depth affect measurements. REBA also needs task information that pose alone cannot supply.

Cite the linked paper when using its findings or methods. For any software actually used, also credit the relevant implementation, version and upstream contributors.

[Discuss research or collaboration](mailto:sufril@usm.my) · [All five research pages](../README.md) · [Profile](../../README.md)
