# Pose-Guided Text-to-Image Diffusion Analysis

## Overview
This project evaluates the robustness and utility of pose-guided text-to-image diffusion models (specifically ControlNet/Stable-Pose architectures) compared to text-only baselines (Stable Diffusion v1.5).

## Objectives
1. **Benchmark** pose-guided vs. text-only models.
2. **Evaluate** using a multi-metric framework (FID, CLIP Score, Pose Fidelity).
3. **Test Robustness** on complex scenarios (side views, occlusions).

## Methodology
- **Datasets:** LAION-Human (subset), Human-Art.
- **Models:** Stable Diffusion v1.5, ControlNet v1.1 (OpenPose).
- **Metrics:** AP (Pose Accuracy), FID/KID (Realism), CLIP (Text Alignment).