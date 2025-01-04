---
title: "Chemical Laboratory Gesture Detection"
excerpt: "An Automatic Detection System for Chemical Laboratory Operation Based on Orange Pi and RK3588"
collection: projects
---

# Project Description
Based on Orange Pi and RK3588 chip, this system uses YOLO11-seg model to recognize common laboratory equipment while detecting hand gestures through Mediapipe with multi-threading. By combining equipment positioning and gesture analysis, it achieves automatic detection of chemical experiment operations (such as pouring, titration, etc.).

<div style="text-align: center">
    <img src="/images/projects/chem-is-try/grabing_cylinder.png" alt="Gesture detection demo" width="35%" />
    <p><em>Gesture detection demo</em></p>
</div>

## Tech Stack
- YOLO11-seg model training and deployment
- Mediapipe gesture recognition
- Multi-threaded parallel processing
- Orange Pi / RK3588 embedded development

## Main Contributions
1. Responsible for model training and optimization
2. Completed multi-threaded integration of equipment recognition and gesture detection
3. Designed and implemented operation analysis logic

## Project Outcomes
- Achieved real-time detection of common chemical laboratory operations
- Accurately identifies laboratory equipment and analyzes operational correctness
- Supports detection of multiple types of experimental operations