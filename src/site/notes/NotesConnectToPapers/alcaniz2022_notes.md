---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/alcaniz2022-notes/"}
---

## 📌 Summary

- The study explores the use of eye gaze as a biomarker for ASD diagnosis using virtual reality (VR) and machine learning.
- It aims to distinguish autistic children from typically developing (TD) peers based on eye-tracking data within an immersive VR environment.
- The study found that autistic children displayed distinct visual attention behaviors, showing preferences for adults and certain social elements.
- Machine learning models trained on eye-tracking data achieved up to 86% accuracy in identifying ASD.
- Results suggest the potential of VR and gaze analysis as an objective ASD assessment tool.

## 🔬 Methods

### Study Design

- Experimental proof-of-concept study using VR and eye-tracking to assess social attention differences between autistic and TD children.
- Applied machine learning models to classify ASD based on eye gaze features.

### Participants

|Group|N|Gender (M/F)|Age (Mean ± SD)|Age Range|
|---|---|---|---|---|
|Autistic|35|Not Specified|5.26 ± 0.51|4–7|
|Neurotypical|20|Not Specified|4.75 ± 0.77|4–7|

- ASD diagnosis was confirmed using ADOS-2 and ADI-R assessments.
- Participants had no ocular pathologies and did not wear glasses.
- Ethical approval obtained from the Polytechnic University of Valencia.

### Tasks for Participants

Participants interacted with various social and non-social stimuli within a VR environment, while their gaze behavior was tracked.

|Task|Purpose|Format|Data Collected|
|---|---|---|---|
|Virtual Mall|Assess eye gaze towards social stimuli|Interactive VR environment|Eye-tracking data|
|Dynamic Stimuli|Examine reactions to moving objects|VR with moving elements|Fixation duration, transitions|
|Static Stimuli|Compare social vs. non-social focus|Stationary elements in VR|Gaze duration on faces, objects|

### System Setup and Hardware

|Device|Purpose|Specifications|
|---|---|---|
|Tobii Pro Glasses 2|Track eye movement|Head-mounted system|
|CAVE VR System|Display immersive environment|3-wall projection|
|Motion Sensors|Record participant movement|Integrated with VR setup|

### Data Analysis

|Feature|Task|Description|
|---|---|---|
|Frames on social AOIs|All tasks|Measures duration of fixation on social stimuli|
|Frames on objects|All tasks|Measures preference for static vs. dynamic objects|
|Face vs. body gaze|Social tasks|Analyzes preference for faces over body parts|
|ML Classification|All tasks|Uses gaze metrics to classify ASD vs. TD|

## 📊 Results & Key Findings

### Key Findings

- Autistic children exhibited greater fixation on adults compared to TD children.
- Autistic children looked more at faces than bodies, particularly in child avatars.
- Static non-social objects received more attention from autistic children than TD children.
- Machine learning models identified ASD with 86% accuracy, with the best performance achieved using SVM classifiers.

### Implications

- Eye-tracking and VR could enhance ASD diagnosis objectivity.
- Machine learning can improve classification of ASD-related gaze behaviors.
- Potential for early detection through gaze-based assessments in virtual settings.

## 🔍 Related Work

- Builds on previous studies using eye-tracking for ASD diagnosis.
- Extends research by integrating immersive VR with real-time gaze tracking.
- Supports existing theories on social attention differences in ASD.

## 📝 Observations

### Strengths of the Study

- Use of an immersive VR environment increases ecological validity.
- Objective gaze tracking provides quantifiable behavioral markers.
- High classification accuracy using machine learning supports feasibility of automated ASD assessment.

### Major Concerns and Challenges

- Small sample size limits generalizability.
- Lack of external validation dataset for machine learning models.
- Limited control over confounding factors such as cognitive ability and sensory sensitivity.
- High equipment costs may restrict clinical adoption.
- VR discomfort or aversion in some autistic children may affect participation.

The study demonstrates promising applications of VR and eye-tracking in ASD assessment but requires further validation with larger and more diverse samples.