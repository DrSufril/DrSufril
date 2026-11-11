# Monocular 3D Pose and REBA Review — reuse and visibility page

## Canonical record

**Monocular 3D Human Pose Estimation for REBA Ergonomics: A Critical Review of Recent Advances**  
Ahmad Mwfaq Bataineh and Ahmad Sufril Azlan Mohamed.  
*Computers, Materials & Continua* 84(1), 93–124 (2025).  
[Open-access publisher article](https://www.techscience.com/cmc/v84n1/61756) · [DOI 10.32604/cmc.2025.064250](https://doi.org/10.32604/cmc.2025.064250) · [BibTeX](../../ergomotion/citation.bib)

## Why researchers may reuse it

The review connects monocular 3D human-pose estimation with REBA-based ergonomic assessment, covering datasets, evaluation metrics, skeleton representations and the gap between pose reconstruction and trustworthy workplace assessment.

## Evaluation checklist

A study applying monocular 3D pose to ergonomics should report:

- camera view, distance, resolution and calibration assumptions;
- static and dynamic tasks;
- occlusion and out-of-plane movement;
- reference system and synchronization;
- joint-position and joint-angle errors;
- how errors propagate into REBA categories;
- manually supplied load, coupling and activity factors;
- uncertainty, missing poses and human-review procedure;
- population and workplace representativeness.

## Distinct promotion sequence

1. **Technical explainer:** RGB image → 2D joints → 3D pose → angles → REBA.
2. **Limits:** depth ambiguity, occlusion and camera-view dependence.
3. **Reusable resource:** the evaluation checklist above.
4. **Application bridge:** [ErgoMotion walkthrough](../../../showcase/ergomotion.md), clearly labelled as a separate application rather than validation evidence.

## Suggested discussion question

When can monocular 3D pose support ergonomic screening, and when is a calibrated reference system still necessary?

## Integrity note

The review synthesises literature from 2016–2024. It does not independently validate ErgoMotion or every method it discusses.
