---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/robles2022-notes/"}
---

## 📌 Summary

- The paper presents a virtual reality (VR)-based system for the screening and classification of Autism Spectrum Disorder (ASD).
- The system simulates a social shopping interaction to collect non-verbal behavioral data (e.g., eye gaze, head movements).
- Machine learning models classify participants as ASD or typically developed (TD) based on recorded behavioral patterns.
- The method demonstrates high classification accuracy and highlights VR's potential as a non-invasive, efficient screening tool.

## 🔬 Methods

### Study Design

- Between-group design comparing ASD and TD participants.
- Participants performed tasks in a VR supermarket scenario while behavioral data was collected.

### Participants

|Group|N|Gender|Age (Mean ± SD)|Verbal IQ|Non-verbal IQ|
|---|---|---|---|---|---|
|ASD|6|3F / 3M|28.83 ± 8.98|110.0|110.66|
|TD Matched|6|3F / 3M|23.16 ± 2.0|108.0|114.1|
|TD Random|7|4F / 3M|23.31 ± 2.39|104.16|114.1|

### Tasks for participants

- The primary task was a shopping simulation in a virtual supermarket.

|Task|Purpose|Format|Data Collected|
|---|---|---|---|
|Introductory Tutorial|Acclimate participants to VR|VR tutorial & virtual mirror|Familiarization time, eye calibration|
|Shopping Task|Simulate real-life social interaction|VR interaction with agent|Gaze patterns, head motion|
|Payment Task|Introduce a transactional context|Drag cash to virtual register|Hand movement data|

### System setup and hardware

- The system used HTC Vive Pro Eye with integrated eye-tracking.

|Device|Purpose|Specs|
|---|---|---|
|HTC Vive Pro Eye|VR and eye-tracking|Integrated Tobii eye tracker|
|Vive Controllers|Interaction with objects|Position, rotation logging|
|Vive Trackers|Body motion tracking|Real-time avatar replication|

### Data Analysis

- Behavioral data was analyzed to identify differences between ASD and TD groups.

|Feature|Task|Description|
|---|---|---|
|Eye gaze dwell time|Social interaction|Time spent looking at specific areas|
|Head movement|Social interaction|Head orientation changes|
|Gaze vector shifts|Social interaction|Changes in gaze direction|
|Fixation time on AOIs|Social interaction|Attention to agent's face vs. background|

## 📊 Results & Key Findings

### Key Findings:

- ASD participants showed significantly reduced fixation on the agent's eyes and increased attention to background elements.
- Differences in gaze shift patterns were evident, with ASD participants displaying more abrupt changes.
- Machine learning models achieved high classification accuracy, with the best-performing model reaching 100% accuracy in some configurations.

### Implications:

- VR-based screening tools offer promising potential for early, objective ASD diagnosis.
- Eye-tracking metrics, particularly fixation time on social areas, can be key markers for ASD.
- The system could be adapted for children and for screening other neurodevelopmental disorders.

## 🔍 Related Work

- Previous studies indicated differences in eye gaze and social attention in ASD populations.
- Similar machine learning-based approaches using desktop eye-tracking have shown lower classification accuracies.
- The current study extended prior work by introducing VR to create a more immersive, ecologically valid environment.

## 📝 Observations

### Strengths of the Study

- Innovative use of VR to simulate social interactions.
- Objective, non-invasive screening approach using eye-tracking data.
- High classification accuracy with relatively simple interaction paradigms.
- Potential scalability for clinical settings.

### Major Concerns and Challenges

- Small sample size limits the generalizability of findings.
- Potential overfitting in machine learning models due to limited data.
- VR environment may not replicate the full complexity of real-life social interactions.
- Lack of diverse age groups and intellectual profiles.
- The system's reliance on static narratives may reduce engagement for some participants.

The study demonstrates the feasibility of VR-based ASD screening, yet future work should address sample diversity, interaction dynamics, and potential applications for children to improve generalizability and clinical relevance.