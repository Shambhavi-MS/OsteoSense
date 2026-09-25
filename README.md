# OSTEOSENSE

### AI-Assisted Early Osteoarthritis Risk-Marker Screening
OSTEOSENSE is an AI-assisted screening platform designed to identify early osteoarthritis risk markers by combining movement, gait, posture, pain, mobility and sensor-based data. It aims to support preliminary screening and severity indication in PHCs and rural/community healthcare settings, particularly across the North Eastern Region.

## Problem Statement
Osteoarthritis (OA) is a progressive joint disorder that can cause pain, stiffness, reduced mobility and changes in movement patterns. Early risk markers may be difficult to identify in community and primary healthcare settings, particularly where access to specialised diagnostic facilities is limited.
OSTEOSENSE addresses this gap by providing an accessible, sensor-assisted and AI-supported preliminary screening approach that can help identify individuals who may require further clinical evaluation.

## Proposed Solution
OSTEOSENSE combines wearable sensor-based movement assessment with patient-reported symptoms and mobility information. The collected data is processed to extract relevant movement and gait features, which are analysed using AI/ML techniques to generate a preliminary osteoarthritis risk indication.
The system is intended to support healthcare workers during community-level screening by providing a simple digital workflow and screening report for further clinical evaluation.

## System Overview
The OSTEOSENSE workflow follows:
Patient Assessment  
↓  
Symptom & Pain Input  
↓  
Sensor-Based Movement and Gait Data Collection  
↓  
Data Preprocessing & Feature Extraction  
↓  
AI/ML Analysis  
↓  
Preliminary OA Risk & Severity Indication  
↓  
Digital Screening Report  
↓  
Suggestion for Further Clinical Evaluation (if at risk of OA)

## Hardware
OSTEOSENSE uses a modular wearable sensing approach designed to capture movement, pressure and functional characteristics associated with osteoarthritis. The same core sensing concept can be adapted to different joints by changing sensor placement and the movement being assessed.

The current prototype concept is designed to support assessment of OA-related changes in:
**Knee:** Joint movement, gait, range of motion and left-right movement asymmetry
**Ankle:** Ankle movement, range of motion and gait-related patterns
**Elbow:** Joint movement and range of motion during functional movements
**Hand:** Finger/hand movement, range of motion and functional limitations

### Sensor Pods
The prototype uses wearable sensor pods that can be positioned around the joint and its adjoining limb segments. For the current knee-focused implementation, four pods are positioned on both legs to enable simultaneous measurement and comparison:
**Pod 1:** Upper left leg
**Pod 2:** Lower left leg
**Pod 3:** Upper right leg
**Pod 4:** Lower right leg

This arrangement allows the system to capture movement characteristics and identify differences between corresponding limbs.

### Components
The sensing system incorporates:
**IMU sensors:** Capture acceleration, angular velocity and orientation-related movement data.
**Force Sensitive Resistor (FSR):** Captures pressure/force-related information and can provide additional information about loading or weight-bearing patterns.
**Microcontroller:** Collects and processes sensor readings before transmitting the required data for further analysis.

The collected multimodal sensor data is processed to extract relevant movement and functional features, which can then be analysed using AI/ML techniques for preliminary OA risk indication and further clinical evaluation.

## AI/ML Analysis
The collected sensor and patient-reported data is processed to identify meaningful movement, gait, pressure and functional features associated with osteoarthritis risk.

The planned AI/ML pipeline follows:
Sensor & Patient Data
↓
Data Preprocessing
↓
Feature Extraction
↓
Pattern Analysis
↓
OA Risk Estimation
↓
Preliminary Risk & Severity Indication
↓
Screening Report

The system is intended to support preliminary screening rather than replace clinical diagnosis. Individuals identified as potentially at risk can be recommended for further medical evaluation.

## Application
OSTEOSENSE is designed to provide a simple digital screening workflow for healthcare workers at PHCs and community-level healthcare settings.

The application is intended to support:
- Patient registration and basic demographic information
- Digital collection of pain, symptoms and mobility-related information
- Sensor-based movement assessment
- AI/ML-assisted analysis of collected data
- Preliminary OA risk and severity indication
- Digital screening reports for record-keeping and further clinical evaluation
- Multilingual and easy-to-use interaction for accessibility in the North Eastern Region
- Offline-friendly operation in areas with limited or unreliable internet connectivity

## Current Development Status
OSTEOSENSE is currently under prototype development.

### Current Focus
- Wearable multi-sensor pod architecture
- Bilateral lower-limb movement assessment for the initial knee-focused prototype
- Integration of movement and pressure-related sensing
- Sensor data acquisition and preprocessing
- Development of the AI/ML analysis pipeline
- Digital screening workflow and report generation

The prototype and software components are being developed iteratively, with hardware testing, data collection and model development progressing alongside each other.

## Future Scope
Future development of OSTEOSENSE may include:
- Expansion of the sensing architecture for additional OA-affected joints and assessment scenarios
- Integration of additional sensing modalities for richer joint assessment
- Exploration of acoustic-emission/vibroarthrography sensing to capture joint sounds during movement
- Improvement of AI/ML models using larger and more diverse datasets
- Enhanced multilingual support for regional users
- Integration of longitudinal patient records for monitoring changes over time
- Improved offline functionality for low-connectivity healthcare settings
- Further validation in real-world PHC and community healthcare environments

## References
This project is being developed based on research and technical literature related to osteoarthritis, movement analysis, wearable sensing, gait assessment and AI-assisted screening.
