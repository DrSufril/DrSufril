# Research and project portfolio

This directory brings together applied prototypes, historical research implementations and an attributed reference-software archive associated with my research and teaching. Each entry describes the scope supported by the recovered source and documentation.

**Repository access:** the linked source repositories and detailed guides are private. Their links require existing access. These public summaries do not change repository visibility or publish the private reports, figures, datasets or source code.

The 15 project repositories have supporting guides, source credits and labelled workflows. Where suitable original material was recovered, those private guides include historical documents, screenshots, illustrations or figures. A recovered document is distinguished from a new implementation or independently reproduced evaluation.

## Human motion and ergonomics

<a id="ergomotion-vr"></a>

### ErgoMotion VR

**Unity prototype.** Immersive REBA posture assessment with joint-angle calculation, skeleton visualization, reporting and optional AI recommendations.

The VR implementation requires scene integration and headset testing. Its IK estimates and prototype status are distinct from the desktop ErgoMotion application.

[Private source repository](https://github.com/DrSufril/ergomotion-vr) · [Private project guide](https://github.com/DrSufril/ergomotion-vr/blob/main/docs/project-overview.md)

<a id="metal-motion-analysis"></a>

### METAL Motion Analysis

**Research prototype.** Video-based markerless pose analysis with joint-angle calculations, movement estimates, annotated output and tabular exports.

Recovered source is incomplete and retains legacy assumptions. Its documentation describes missing dependencies and the limits of the archived implementation.

[Private source repository](https://github.com/DrSufril/metal-motion-analysis) · [Private project guide](https://github.com/DrSufril/metal-motion-analysis/blob/main/docs/project-overview.md)

<a id="ergomotion-legacy-python"></a>

### Legacy ErgoMotion Python

**Earlier implementation.** An earlier desktop implementation using MediaPipe, multiview triangulation and a graphical joint-analysis interface.

Preserved separately for research history. It is not the current ErgoMotion release and does not replace the active application.

[Private source repository](https://github.com/DrSufril/ergomotion-legacy-python) · [Private project guide](https://github.com/DrSufril/ergomotion-legacy-python/blob/main/docs/project-overview.md)

## Industrial vision and monitoring

<a id="matlab-image-stitching"></a>

### MATLAB Image Stitching

**Archival algorithm.** Feature-based alignment and combination of overlapping image tiles for machine-vision inspection.

The archive retains MATLAB source and a recovered workflow figure. Calibration, image naming and toolbox requirements need to be matched to a new input set.

[Private source repository](https://github.com/DrSufril/matlab-image-stitching) · [Private project guide](https://github.com/DrSufril/matlab-image-stitching/blob/main/docs/project-overview.md)

<a id="cpp-stitching-launcher"></a>

### C++ Stitching Launcher

**Integration wrapper.** A C++ application entry point that initializes and invokes a MATLAB-compiled image-stitching library.

This repository contains the integration wrapper; it is not an independent C++ implementation of the stitching algorithm.

[Private source repository](https://github.com/DrSufril/cpp-stitching-launcher) · [Private project guide](https://github.com/DrSufril/cpp-stitching-launcher/blob/main/docs/project-overview.md)

<a id="wahsp-system"></a>

### WAHSP Vehicle Interface

**Unity simulation scripts.** A simulated vehicle interface combining proximity warnings, selectable camera views, parking guides and split-screen presentation.

The recovered scripts and historical simulation frame document the prototype. A complete vehicle scene and its third-party simulation dependency are separate.

[Private source repository](https://github.com/DrSufril/wahsp-system) · [Private project guide](https://github.com/DrSufril/wahsp-system/blob/main/docs/project-overview.md)

<a id="near-miss-detection"></a>

### Near-Miss Detection

**Research and training.** YOLO-based detection, DeepSORT tracking and proximity analysis for studying traffic movement and candidate near-miss interactions.

The documented collection connects supervised research with a Mathtech teaching workflow. Its archived training plot is historical material, not a newly reproduced benchmark.

[Private source repository](https://github.com/DrSufril/near-miss-detection) · [Private project guide](https://github.com/DrSufril/near-miss-detection/blob/main/docs/project-overview.md)

<a id="ruteam-container-monitoring"></a>

### RUTEAM Container Monitoring

**Edge-vision prototype.** Container-ID OCR, person/helmet detection and tracking workflows, including a Raspberry Pi/Hailo dashboard.

The guides distinguish the recovered Pi dashboard from a broader drone architecture proposal. Hardware models and field data are separate from the source archive.

[Private source repository](https://github.com/DrSufril/ruteam-container-monitoring) · [Private project guide](https://github.com/DrSufril/ruteam-container-monitoring/blob/main/docs/project-overview.md)

<a id="pcb-aoi-ocr"></a>

### PCB AOI and OCR

**Source fragment.** Recovered PCB annotation parsing, crop preparation and Pascal VOC dataset-analysis scripts.

These recovered preparation tools do not constitute a complete trained AOI detector or OCR inference pipeline.

[Private source repository](https://github.com/DrSufril/pcb-aoi-ocr) · [Private project guide](https://github.com/DrSufril/pcb-aoi-ocr/blob/main/docs/project-overview.md)

## Medical imaging and biometrics

<a id="mri-reconstruction"></a>

### 3DMRIRendering

**Research application.** Qt/C++ and CUDA tools for reconstructing and exploring 3D surfaces from MRI/CT image stacks, with threshold controls, visualization, mesh simplification and STL export.

The imported application source and setup guide are documented; the Windows/Qt/CUDA build has not been revalidated in this archive.

[Private source repository](https://github.com/DrSufril/mri-reconstruction) · [Private project guide](https://github.com/DrSufril/mri-reconstruction/blob/main/docs/project-overview.md)

<a id="ultrasound-tendon-tracking"></a>

### Ultrasound Tendon Tracking

**Historical PhD archive.** MATLAB research into ultrasound speckle/tendon tracking, including NCC, MSE and Lucas–Kanade algorithm comparisons.

The archive preserves version history through duplicate-source mapping and historical study notes. It does not designate a final best algorithm or assert a new clinical validation.

[Private source repository](https://github.com/DrSufril/ultrasound-tendon-tracking) · [Private project guide](https://github.com/DrSufril/ultrasound-tendon-tracking/blob/main/docs/project-overview.md)

<a id="fairs-face-recognition"></a>

### FAIRS Face Recognition

**Historical MSc archive.** Java source from face-identification and verification research, with background from an MSc preparatory study of eigenface-based authentication.

Selected report pages provide objectives and a cited generic system diagram. Face samples, biometric templates and databases are excluded from the repository.

[Private source repository](https://github.com/DrSufril/fairs-face-recognition) · [Private project guide](https://github.com/DrSufril/fairs-face-recognition/blob/main/docs/project-overview.md)

## Immersive and educational systems

<a id="ceed-ceramic-simulation"></a>

### CEED Ceramic Education

**Browser learning materials.** Illustrated ceramic-making instruction, interactive 3D demonstrations and quizzes, supported by a recovered AR teaching booklet.

The browser materials and booklet are distinct from the broader proposed headset-based VR experience.

[Private source repository](https://github.com/DrSufril/ceed-ceramic-simulation) · [Private project guide](https://github.com/DrSufril/ceed-ceramic-simulation/blob/main/docs/project-overview.md)

<a id="darvih"></a>

### DARVIH

**Unity educational-game scripts.** A game-based learning project linking movement, obstacles, coins and question interactions with drug-prevention educational content.

The source archive and original question bank provide project context. Scenes, artwork and a complete runnable game build are not included.

[Private source repository](https://github.com/DrSufril/darvih) · [Private project guide](https://github.com/DrSufril/darvih/blob/main/docs/project-overview.md)

## Attributed reference software

<a id="blood-flow-analysis"></a>

### FloWave.US Reference Archive

**Third-party MIT software.** An attributed local archive of FloWave.US for MATLAB-based ultrasound blood-flow analysis.

Original software credit belongs to Crystal Coolbaugh and the upstream contributors. The original MIT license and available third-party notices are retained; this archive is not presented as an original algorithm by this account.

[Private source repository](https://github.com/DrSufril/blood-flow-analysis) · [Private project guide](https://github.com/DrSufril/blood-flow-analysis/blob/main/docs/project-overview.md)

[← Back to profile](../README.md)
