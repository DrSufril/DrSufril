# ErgoMotion — AI-assisted ergonomic assessment

**Markerless motion analysis · 3D pose · Joint angles · REBA**

ErgoMotion is a desktop research application for reviewing movement and ergonomic risk from recorded video or live cameras. It combines pose estimation, 3D visualisation, joint-angle measurements, and Rapid Entire Body Assessment (REBA) scoring in a frame-by-frame review interface.

![Conceptual ErgoMotion workflow](../assets/ergomotion-concept.svg)

*Conceptual workflow illustration.*

## Purpose

The project helps researchers examine how posture changes during a task, locate moments with elevated estimated ergonomic risk, and inspect the movement behind each score.

## Analysis workflow

1. **Load footage:** select one video or synchronized camera views, or connect live cameras.
2. **Estimate pose:** detect workers and reconstruct body landmarks using the selected camera mode.
3. **Review movement:** replay frames alongside a 3D skeleton, joint angles, score table, and REBA timeline.
4. **Add task context:** enter force/load, coupling, and activity information that cannot be inferred reliably from pose.
5. **Export results:** save a reviewable session, numerical measurements, annotated video, or a report.

## Camera modes

| Mode | Approach | Review considerations |
| --- | --- | --- |
| **Single camera** | Person detection and RTMW3D whole-body pose estimation; worker tracking and selection | Depth and scale are estimated. Worker height supplies a scale reference. |
| **Multiple cameras** | MediaPipe landmarks from two or three synchronized cameras, triangulated into 3D | Intrinsics, camera positions, recording resolution, and synchronization must match the footage. |

## Review and reporting features

- Colour-coded body segments and angle callouts linked to REBA component scores
- A score timeline for jumping to individual moments
- Per-worker average and peak REBA summaries and time spent in selected risk bands
- Upright-reference adjustment to assist alignment
- Session export, per-frame CSV data, 2D annotated video, and 3D skeleton video
- Optional AI-assisted PDF reporting from numerical scores and joint angles; the documented report request sends no images or video

## Technology

Python, MediaPipe, RTMW3D, person detection, multi-view triangulation, temporal smoothing, and REBA scoring.

## Evaluation and limits

The local documentation describes early single-camera benchmarks against multi-camera reference data. These are development checks rather than evidence of general clinical or workplace validation.

Occlusion, missed people, changing limb lengths, estimated depth, and camera calibration can affect measurements. Frames without sufficient body landmarks receive no REBA score. Some contextual and fine-grained ergonomic factors require manual input or cannot be measured reliably from the available pose.

**Use:** research and ergonomic review support, with human interpretation.

[← Back to profile](../README.md)
