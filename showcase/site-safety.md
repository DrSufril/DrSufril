# AI Site Safety — visual inspection assistance

**AI tool integration · Worker posture · Helmet checks · Hot-work review**

AI Site Safety connects computer vision tools with a conversational review workflow. A reviewer supplies a site photo and receives annotated evidence, structured findings, and reasons for potential review flags.

![Hot-work analysis with gas-cylinder distance estimates](../assets/site-safety-hotwork.jpg)

*AI Site Safety output showing hot-work and cylinder-distance annotations. Distances and the displayed violation labels are unvalidated model estimates, not verified measurements or compliance findings.*

## Analysis tools

| Tool | What it produces |
| --- | --- |
| **Worker pose and helmet analysis** | Detected workers, posture categories, helmet status, and preliminary review flags with reasons |
| **Hot-work and gas-cylinder analysis** | Welding/cutting and cylinder detections, estimated ground separation with an uncertainty range, and a configurable review interpretation |

The documented hot-work tool compares its estimated distance with a 10-metre reference rule. This is a tool configuration, not a determination of which requirements apply to a particular workplace.

## Review workflow

1. **Supply a photo:** attach an image or select one from the working folder.
2. **Run analysis:** a tool-capable assistant invokes worker and/or hot-work analysis.
3. **Inspect evidence:** examine detection overlays, pose labels, estimated distances, and uncertainty.
4. **Verify findings:** check ambiguous detections and relevant context against the original scene.
5. **Record follow-up:** use the structured output to guide further inspection and independent measurement.

## Architecture and deployment

The project includes a **DeepSeek Harness plugin** with two callable tools: `analyze_pose` and `check_hot_work_safety`.

- **Remote GPU mode:** runs analysis on a GPU server and returns results to the reviewer.
- **Local GPU mode:** runs alongside the assistant on compatible hardware.
- **Apple silicon prototype:** uses local model inference with Apple GPU acceleration where supported; the documented setup can operate offline after installation.
- **Review outputs:** annotated images plus JSON for traceability and downstream processing.

The Mac prototype combines a local Qwen model through Ollama with the analysis tools. Processing time depends on the selected models, device, memory pressure, and image content.

## Technical focus

Worker analysis combines person detection, pose estimation, posture geometry, and helmet classification. The hot-work pipeline combines object detection and single-image scene/depth estimation to reason about approximate ground separation without a depth sensor or prior camera calibration.

## Validation and limits

The Mac documentation reports comparisons with server outputs on sample images. Agreement on those examples checks implementation consistency; it does not validate physical distance accuracy.

**All results are unvalidated estimates for human review.** Single-image perspective, occlusion, uncertain object locations, and depth errors can affect findings. Distance estimates need independent measurement before action. The system supports inspection and does not certify that a site is safe.

[← Back to profile](../README.md)
