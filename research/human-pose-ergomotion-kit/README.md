# Human Pose Estimation & ErgoMotion Research Kit

A guided entry point connecting published research on **2D/3D human pose estimation, markerless motion capture and ergonomic assessment** with the ErgoMotion application family and related research prototypes.

> **Scope:** The papers provide research evidence and technical context. The applications are separate implementations at different maturity levels. A link in this kit does not mean that an application reproduces, implements or validates every method in a linked paper.

## Paper visibility programme

[**Open the paper-by-paper visibility plan →**](PAPER-VISIBILITY-PLAN.md) · [Ready-to-use social post drafts](SOCIAL-POST-DRAFTS.md)

Each core paper now has a dedicated page with verified metadata, a reusable checklist, a distinct promotion angle and an integrity note. The programme supports discovery and legitimate reuse; it cannot guarantee citations.

## Start here

Choose the route that matches your goal:

| Goal | Recommended starting point | Continue with |
|---|---|---|
| Understand 2D pose-estimation methods | [2D human pose survey](../human-pose/README.md) | [Human Pose Analytics](../../showcase/human-pose.md) |
| Study monocular 3D pose for ergonomics | [3D pose and REBA review](../ergomotion/README.md) | [ErgoMotion Desktop walkthrough](../../showcase/ergomotion.md) |
| Prototype accessible landmark tracking | *Movement Estimation Using MediaPipe BlazePose* | ErgoMotion Web or legacy ErgoMotion |
| Measure torso or spinal movement | Torso-bending and spinal-joint studies below | METAL Motion Analysis |
| Explore immersive ergonomic review | 3D pose and REBA review | ErgoMotion VR |
| Review worker posture in site footage | 2D pose survey | Human Pose Analytics |

## Research-paper map

### Core pose-estimation papers

1. **A Survey on Deep Learning-Based 2D Human Pose Estimation Models**  
   Sani Salisu, Ahmad Sufril Azlan Mohamed, Mohd Hafiidz Jaafar, Ainun Syarafana Binti Pauzi and Hussain A. Younis. *Computers, Materials & Continua* 76(2), 2385–2400 (2023).  
   [Companion visibility and reuse page](papers/2d-pose-survey.md) · [Paper page and BibTeX](../human-pose/README.md) · [DOI 10.32604/cmc.2023.035904](https://doi.org/10.32604/cmc.2023.035904)

2. **Monocular 3D Human Pose Estimation for REBA Ergonomics: A Critical Review of Recent Advances**  
   *Computers, Materials & Continua* (2025).  
   [Companion visibility and reuse page](papers/3d-pose-reba-review.md) · [Paper page and BibTeX](../ergomotion/README.md) · [DOI 10.32604/cmc.2025.064250](https://doi.org/10.32604/cmc.2025.064250)

3. **Movement Estimation Using MediaPipe BlazePose**  
   *Advances in Visual Informatics* (2021).  
   [Companion visibility and reuse page](papers/blazepose-movement.md) · [DOI 10.1007/978-3-030-90235-3_49](https://doi.org/10.1007/978-3-030-90235-3_49)

4. **Torso Bending Estimation for Deep Learning 2D Markerless Motion Capture**  
   10th ASEAN Workshop on Information Science and Technology (2022).  
   [Metadata and discoverability page](papers/torso-bending.md) · [Google Scholar title search](https://scholar.google.com/scholar?q=%22Torso+Bending+Estimation+for+Deep+Learning+2D+Markerless+Motion+Capture%22)

5. **Enhancing 2D Joints Estimation in Markerless Motion Capture for Improved Tracking of Spinal Movements**  
   (2025).  
   [Thesis resource page](papers/spinal-movement-thesis.md) · [Official USM repository record](https://erepo.usm.my/handle/123456789/24285)

### Ergonomics and motion-analysis foundations

- **Implementation of Kinetic and Kinematic Variables in Ergonomic Risk Assessment Using Motion Capture Simulation: A Review** — background for selecting measurable movement variables. [Google Scholar search](https://scholar.google.com/scholar?q=%22Implementation+of+kinetic+and+kinematic+variables+in+ergonomic+risk+assessment%22)
- **Ergonomics Risk Assessment for Manual Material Handling of Warehouse Activities Involving High-Shelf and Low-Shelf Binning Processes** — applied marker-based motion analysis. [Google Scholar search](https://scholar.google.com/scholar?q=%22Ergonomics+risk+assessment+for+manual+material+handling+of+warehouse+activities%22)
- **Biomechanics Analysis of the Firefighters’ Thorax Movement on Personal Protective Equipment During Lifting Task Using Inertial Measurement Unit Motion Capture** — complementary sensor-based movement analysis. [Google Scholar search](https://scholar.google.com/scholar?q=%22Biomechanics+analysis+of+the+firefighters%27+thorax+movement%22)

## From research to applications

```text
Images or video
      ↓
Person detection and body landmarks
      ↓
2D pose ──→ posture geometry ──→ Human Pose Analytics
      │
      ├──→ markerless movement and joint-angle analysis ──→ METAL / legacy ErgoMotion
      │
      └──→ estimated or triangulated 3D pose
                    ↓
             joint angles + task context
                    ↓
              REBA review and reporting
                    ↓
        ErgoMotion Desktop / Web / VR
```

This diagram is a conceptual map, not a claim that every application uses the same model, dataset or processing pipeline.

## ErgoMotion and related applications

| Application | Documented purpose | Relationship to the research | Availability |
|---|---|---|---|
| [ErgoMotion Desktop](../../showcase/ergomotion.md) | Video-based 2D/3D movement review, joint angles, REBA scoring and exports | Practical application informed by pose-estimation and ergonomics research; not independently validated by the review paper | Public walkthrough; [private repository](https://github.com/DrSufril/Ergomotion) |
| [ErgoMotion Web](../../showcase/research-portfolio.md#ergomotion-web) | Browser prototype for pose-based REBA review | Accessible browser exploration with separate scoring and camera assumptions | Public summary; [private repository](https://github.com/DrSufril/ergomotion-web) |
| [ErgoMotion VR](../../showcase/research-portfolio.md#ergomotion-vr) | Immersive posture assessment and skeleton visualisation | Explores 3D/immersive presentation of ergonomic assessment | Public summary; [private repository](https://github.com/DrSufril/ergomotion-vr) |
| [Legacy ErgoMotion Python](../../showcase/research-portfolio.md#ergomotion-legacy-python) | Earlier MediaPipe and multi-view desktop implementation | Preserves the development path from landmark tracking to ergonomic analysis | Public summary; [private repository](https://github.com/DrSufril/ergomotion-legacy-python) |
| [METAL Motion Analysis](../../showcase/research-portfolio.md#metal-motion-analysis) | Markerless joint and movement analysis | Related to torso, spinal-movement and markerless motion-capture research | Public summary; [private repository](https://github.com/DrSufril/metal-motion-analysis) |
| [Human Pose Analytics](../../showcase/human-pose.md) | Worker detection, 17-point pose estimation and explainable posture labels | Applied 2D-pose pipeline; the survey provides background but does not validate its rules | Public walkthrough; [private repository](https://github.com/DrSufril/human-pose) |

## Reuse pathways

### For researchers

1. Start with the relevant paper and its limitations.
2. Use the canonical DOI or publisher record in your literature review.
3. Select datasets, models and evaluation measures appropriate to your population and setting.
4. Treat an application demonstration as software context, not published validation.
5. Cite the paper whose findings you actually use and identify the software version separately when applicable.

### For students

- Reproduce a small pose-estimation baseline on a public dataset.
- Compare 2D landmark stability across camera viewpoints and occlusion.
- Evaluate how pose uncertainty propagates into joint angles.
- Compare markerless measurements with a calibrated reference.
- Investigate how manual REBA task inputs change the final score.

### For industry collaborators

Potential collaboration topics include camera placement, representative workplace data, reference measurements, usability studies and independent validation. The applications are research and review-support tools; they should not be treated as autonomous workplace-safety or clinical decision systems.

## What is reusable now?

| Resource | Status |
|---|---|
| 2D pose survey | Open-access publisher article and BibTeX available |
| 3D pose/REBA review | Publisher/established article links and BibTeX available |
| Application descriptions and selected images | Public through this profile repository |
| Application source | Private; existing access or collaboration approval required |
| Workplace footage and supporting datasets | Not released through this kit |
| Trained models or weights | No study-specific public release claimed here |
| Publisher PDFs | Linked at their authorised hosts; not redistributed here |

## Limitations and responsible use

Pose estimates can be affected by occlusion, camera position, depth ambiguity, clothing, image resolution, calibration and population differences. REBA also requires contextual information—such as load, coupling and activity—that cannot always be inferred from video. Report uncertainty, keep humans in the review process and validate on the intended setting before operational use.

## Citation guidance

Use the canonical paper record when relying on a published method, result or synthesis. If you use an application, also record its name, version or commit, access date and relevant upstream models. Do not cite a paper merely because it is linked to an application; cite it only when it informed the work.

[Google Scholar profile](https://scholar.google.com/citations?user=AHj1bTgAAAAJ&hl=en) · [ORCID](https://orcid.org/0000-0002-2838-0872) · [Research visibility hub](../README.md) · [Discuss collaboration](mailto:sufril@usm.my)
