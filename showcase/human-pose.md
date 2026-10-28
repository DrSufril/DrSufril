# Human Pose Analytics — explainable posture analysis

**CCTV analysis · Person detection · 2D keypoints · Human review**

Human Pose Analytics processes folders of images or videos from fixed cameras to detect people, estimate body keypoints, and assign interpretable posture labels. The project focuses on crowded shipyard and construction scenes, where workers can be small, distant, or partly occluded.

![Worker detection and body-keypoint overlay on a shipyard image](../assets/human-pose-analysis.jpg)

*Human Pose tool output showing a detected worker and estimated body keypoints. The overlay illustrates pose estimation; posture and safety interpretations require human review.*

## Analysis workflow

1. **Detect people:** combine a full-frame pass with overlapping image tiles to improve detection of small workers.
2. **Estimate pose:** run a top-down pose model on each person crop to obtain 17 body keypoints with confidence values.
3. **Describe posture:** apply geometric rules to visible joints, including trunk, knee, and thigh angles.
4. **Review evidence:** inspect skeleton overlays, angles, and the reason behind each label; correct labels in a review page.
5. **Export results:** produce structured data, annotated media, summary tables, and a static results website.

## Posture categories

| Output | Interpretation |
| --- | --- |
| **Standing** | Upright posture with sufficient leg visibility |
| **Moderate / severe bending** | Trunk and head geometry indicate different bending categories |
| **Squatting / kneeling** | Knee and leg geometry suggest deep flexion or kneeling |
| **Sitting** | Trunk and thigh geometry suggest a seated posture |
| **Unknown** | Too few reliable joints to distinguish posture |
| **Arms raised** | Separate flag; can also be unmeasurable |

Each classification includes the supporting angles and a plain-language reason. An additional helmet-check module can report helmet, no helmet, or unknown; experimental methods remain identified as such.

## Outputs and review tools

- Per-person bounding boxes, keypoints, confidence values, and posture explanations
- Annotated images or video and per-file JSON
- CSV summaries and run metadata recording settings and model versions
- Static gallery, interactive skeleton viewer, video view, and label-correction page
- Data-only reporting mode that omits source CCTV imagery
- Resumable batch processing with errors recorded per file

## Technology

YOLOX person detection, RTMPose pose estimation, ONNX Runtime, OpenCV, Python, and rule-based posture geometry. GPU processing supports batch analysis.

## Documented evaluation

On the largest documented held-out posture set (**167 usable workers**), rules-v3 achieved **0.72 accuracy**, **0.77 severe-bend recall**, and **0.66 squat/kneel recall**. Both recall values were below the project's 0.80 target.

An experimental gradient-boosted classifier was withdrawn after a larger held-out evaluation showed poorer results; the geometric rules remain the documented default.

## Limitations

These are **research-baseline posture labels, unvalidated for safety decisions**. Perspective, occlusion, crowded scenes, and missing joints affect the interpretation of 2D geometry. The evaluation figures describe specific datasets and do not establish performance at another site.

[Read the related paper and download its citation](../research/human-pose/README.md)

[← Back to profile](../README.md)
