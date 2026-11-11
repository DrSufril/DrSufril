# Ready-to-use promotion drafts

Use one post at a time. Replace bracketed fields only with verified links or resources. Do not ask readers to cite; invite discussion, evaluation or reuse.

## 1. 2D human pose-estimation survey

**How should researchers choose a 2D human-pose model for real-world footage?**

Benchmark accuracy is only part of the decision. A useful evaluation should also consider whether the pipeline is top-down or bottom-up, its keypoint convention, computational cost, occlusion handling, image scale, crowding and domain shift.

Our open-access survey maps the major deep-learning approaches, datasets and unresolved challenges. I have added a practical model-selection checklist to help students and researchers connect the literature to new applications.

Paper: https://doi.org/10.32604/cmc.2023.035904  
Companion resource: https://github.com/DrSufril/DrSufril/blob/main/research/human-pose-ergomotion-kit/papers/2d-pose-survey.md

Which factor most often prevents a pose model from transferring successfully to real-world data?

#HumanPoseEstimation #ComputerVision #DeepLearning #OpenAccess

## 2. Monocular 3D pose for REBA ergonomics

**Can one RGB camera provide sufficiently reliable information for ergonomic screening?**

Monocular 3D pose estimation offers an accessible route from video to joint angles and REBA-related posture analysis. Important uncertainties remain: depth ambiguity, occlusion, camera viewpoint and the propagation of joint errors into risk categories.

Our critical review examines the field and identifies the need for more representative datasets and stronger validation. A new companion checklist summarises what future evaluations should report.

Paper: https://doi.org/10.32604/cmc.2025.064250  
Evaluation checklist: https://github.com/DrSufril/DrSufril/blob/main/research/human-pose-ergomotion-kit/papers/3d-pose-reba-review.md

When is monocular pose sufficient, and when is a calibrated reference system still necessary?

#Ergonomics #3DPoseEstimation #REBA #ComputerVision

## 3. MediaPipe BlazePose movement estimation

**What evidence is required before camera-based landmarks can replace instrumented motion capture for a specific movement?**

Our 2021 work investigated movement estimation using MediaPipe BlazePose. The most valuable next step for this research direction is not another demonstration—it is transparent reporting of camera settings, landmark filtering, synchronization, reference measurements and per-joint errors.

I have published a reproducibility checklist connecting this established paper to our newer 2D and 3D pose research.

Paper: https://doi.org/10.1007/978-3-030-90235-3_49  
Checklist: https://github.com/DrSufril/DrSufril/blob/main/research/human-pose-ergomotion-kit/papers/blazepose-movement.md

#MediaPipe #BlazePose #MarkerlessMotionCapture #MovementAnalysis

## 4. Torso-bending estimation

**Torso-angle estimation looks simple—until camera viewpoint, missing landmarks and out-of-plane movement are considered.**

Our AWIST contribution explored torso-bending estimation using deep-learning-based 2D markerless motion capture. Before wider promotion, we are consolidating the proceedings metadata and documenting the measurement assumptions needed for reproducible comparison.

Discoverability page: https://github.com/DrSufril/DrSufril/blob/main/research/human-pose-ergomotion-kit/papers/torso-bending.md

Researchers working with torso or trunk-angle estimation: which reference definition and validation method have you found most dependable?

#MarkerlessMotionCapture #Ergonomics #HumanMotionAnalysis

## 5. Enhanced spinal-joint estimation thesis

**Standard pose skeletons represent the limbs well, but what happens when the research question concerns spinal movement?**

A 2025 USM thesis by Ainun Syarafana Pauzi investigates enhanced 2D joint estimation for spinal tracking. The work compares OpenPose, MediaPipe BlazePose and MoveNet against IMU data, then explores additional spine keypoints and curve fitting.

Official USM repository record: https://erepo.usm.my/handle/123456789/24285  
Research-series context: https://github.com/DrSufril/DrSufril/blob/main/research/human-pose-ergomotion-kit/papers/spinal-movement-thesis.md

How much anatomical detail should a markerless skeleton contain before it can represent spinal movement meaningfully?

#HumanPoseEstimation #SpinalMovement #ComputerVision #ThesisResearch
