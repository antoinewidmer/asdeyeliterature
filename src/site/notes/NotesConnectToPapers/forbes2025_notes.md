---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/forbes2025-notes/"}
---


[[Literature_review/forbes2025\|forbes2025]]


## 📌 Summary


## 🔬 Methods 
### Participants


| Characteristic            | Value |
|--------------------------|--------------------------------|
| **Total Sample**         | 405 Australian children and adolescents |
| **ADHD Group**           | 64 children |
| **Autism (ASD) Group**   | 66 children |
| **Autism + ADHD Group**  | 146 children |
| **Neurotypical (NT) Controls** | 129 children |
| **Age Range**            | 4 to 18 years (Mean: 9.64 ± 3.20 years) |
| **Confirmatory Dataset - University of Nottingham (UK)** | 101 children (17 ASD, 22 ADHD, 32 ASD+ADHD, 30 NT) |
| **Confirmatory Dataset - University of Kansas (USA)** | 70 children (29 ASD, 41 NT) |
| **Clinical Assessments for ASD & ADHD Diagnosis** | ADOS-2, CPRS, SRS-2, WISC-V, VABS-3 |
| **Medication Considerations** | ADHD medication stopped 48-72 hours before eye-tracking tests |


### Tasks for participants

|**Task**|**Description**|**Key Measures**|
|---|---|---|
|**Visually Guided Saccade (VGS)**|Look at a target appearing on the screen.|Saccade gain (accuracy), peak velocity, final eye position (FEP).|
|**Anti-Saccade (AS)**|Inhibit reflexive saccades; look opposite of target.|Number of directional errors, anticipatory saccades.|
|**Sinusoidal Pursuit**|Follow a moving target along a wave-like path.|Smooth pursuit gain, number of catch-up saccades.|
|**Step-Ramp Pursuit**|Follow a target that changes speed.|Open-loop gain (initial tracking accuracy), catch-up saccades.|

Participants in the study completed **four oculomotor (eye-tracking) tasks** designed to assess **saccadic (rapid eye movements) and smooth pursuit (tracking moving objects) eye movements**. Below is a breakdown of each task and what the participants were required to do.

---

#### Visually Guided Saccade (VGS) Task

**Purpose:** Measure basic eye movement accuracy and reaction time.

##### Task Instructions:

1. Participants **fixated on a central target (green cross)** on the screen.
2. A **new target appeared in the periphery (left or right)** after a short delay.
3. **Participants had to shift their gaze quickly to the new target**.
4. Once the participant fixated on the peripheral target, the **central target reappeared** to signal the start of a new trial.
5. **Total trials:** 48 (randomized left/right target appearances).

##### Data Collected:

- **Saccade gain:** Accuracy of eye movements to the target.
- **Time to peak velocity:** How quickly the eyes reached maximum movement speed.
- **Final Eye Position (FEP):** The accuracy of the final gaze position after movement.
- **Gain variability:** Differences in accuracy across trials.


#### Anti-Saccade (AS) Task

**Purpose:** Measure **inhibitory control** (ability to suppress automatic responses).

##### Task Instructions:

6. Participants **fixated on a central target**.
7. A **new target appeared in the periphery (left or right)**.
8. Instead of looking at the new target, **participants were instructed to look in the opposite direction**.
9. A **correction cue** was given if the participant made an error.
10. **Total trials:** 48 (randomized left/right).

##### Data Collected:

- **Number of directional errors:** How often participants mistakenly looked at the peripheral target instead of the opposite direction.
- **Number of anticipatory saccades:** Premature eye movements before the target appeared.

---

#### Sinusoidal Pursuit Task

**Purpose:** Measure **smooth pursuit eye movements** (ability to track a moving object).

##### Task Instructions:

1. Participants **fixated on a moving circular target** on the screen.
2. The target **moved back and forth in a wave-like (sinusoidal) pattern**.
3. Participants were instructed to **follow the target with their eyes while keeping their head still**.
4. The **target changed speed** (slow: 6°/s, fast: 18°/s).
5. **Total trials:** 15 oscillations per condition (slow and fast).

##### Data Collected:

- **Closed-loop gain:** Accuracy of smooth pursuit tracking.
- **Number of catch-up saccades:** Small corrective eye movements made to catch up with the target.

#### Step-Ramp Pursuit Task

**Purpose:** Measure **adaptive eye movement tracking** when target speed changes.

##### Task Instructions:

6. Participants **fixated on a stationary circular target** at the center of the screen.
7. The target **jumped 3° to the left or right (step phase)** and then **moved continuously in the opposite direction (ramp phase)**.
8. The target’s **speed increased or decreased gradually**.
9. Participants had to **track the moving target as smoothly as possible**.
10. **Total trials:** 32 (randomized left/right, slow/fast conditions).

##### Data Collected:

- **Open-loop gain:** Accuracy of initial pursuit response.
- **Number of catch-up saccades:** Corrective saccades to maintain tracking accuracy.

---

#### **Summary of Participant Tasks**

|**Task Name**|**Type of Eye Movement**|**What Participants Had to Do**|**Key Measures**|
|---|---|---|---|
|**Visually Guided Saccade (VGS)**|Saccades (rapid eye movements)|Look at a new target as fast as possible.|Accuracy, reaction time, final gaze position.|
|**Anti-Saccade (AS)**|Inhibitory control|Look in the **opposite direction** of the target.|Directional errors, anticipatory saccades.|
|**Sinusoidal Pursuit**|Smooth pursuit (tracking)|Follow a target moving in a **wave-like path**.|Tracking accuracy, catch-up saccades.|
|**Step-Ramp Pursuit**|Adaptive pursuit (tracking)|Follow a **speed-changing target**.|Initial tracking accuracy, corrective saccades.|

### System setup and hardware
Eye movements were recorded using **EyeLink 1000** (500Hz sampling rate).  
Each child’s **head was stabilized** for accurate tracking.

### Data Analysis
#### Eye-Tracking Metrics in ASD Study

| **Category**                  | **Metric**                        | **Definition**                                                                     | Tag                                          |
| ----------------------------- | --------------------------------- | ---------------------------------------------------------------------------------- | ------------------------------------------- |
| **Saccade-Based Metrics**     | **Saccade Gain**                  | Accuracy of eye movement amplitude relative to target displacement.                | #EyeTracking/Saccades/Amplitude                |
|                               | **Peak Saccade Velocity**         | Maximum speed of a saccade.                                                        | #EyeTracking/Saccades/PeakVelocity               |
|                               | **Final Eye Position (FEP)**      | Accuracy of eye position after movement.                                           | #EyeTracking/Saccades/FEP                        |
| **Anti-Saccade Metrics**      | **Directional Errors**            | % of incorrect saccades (looking at the target instead of the opposite direction). | #Oculometry/AntiSaccade/DirectionalError       |
|                               | **Anticipatory Saccades**         | % of saccades made before the target appears.                                      | #Oculometry/AntiSaccade/Anticipatory                |
| **Smooth Pursuit Metrics**    | **Smooth Pursuit Gain**           | Accuracy of eye velocity matching the moving target.                               | #Oculometry/SmoothPursuit/Gain                       |
|                               | **Catch-Up Saccades**             | Number of corrective saccades needed to keep up with the target.                   | #Oculometry/SmoothPursuit/CatchUpSaccade       |
| **Step-Ramp Pursuit Metrics** | **Open-Loop Gain**                | Accuracy of the initial tracking response before feedback correction.              | #Oculumetry/StepRampPursuit/OpenLoopGain        |
|                               | **Catch-Up Saccades (Step-Ramp)** | Quick saccades made to correct tracking errors when a target changes speed         | #Oculumetry/StepRampPursuit/CatchUpSaccade    |


## 📊 Results & Key Findings 

### (A) Visually Guided Saccade (VGS) Task

- **ASD + ADHD group** showed **greater variability in final eye position (FEP)**.
- **No significant differences in peak velocity or saccade gain**.

### (B) Anti-Saccade (AS) Task

- **Kansas cohort** found that **ASD participants made more directional errors**.
- **No significant differences in anticipatory saccades**.

### (C) Sinusoidal Pursuit Task

- **ASD group showed significantly more catch-up saccades** than NT controls.
- **No major differences in smooth pursuit gain**.

### (D) Step-Ramp Pursuit Task

- **ASD group had more catch-up saccades** than NT controls.
- **No differences between ADHD and NT groups**.

### (E) Confirmatory Datasets

- **Nottingham cohort did not replicate significant findings**.
- **Kansas cohort replicated increased AS errors in ASD but not ADHD**.

### Summary

11. **Oculomotor variability (FEP) is higher in ASD + ADHD than NT controls.**
12. **Autistic individuals have more catch-up saccades**, suggesting **sensorimotor deficits in pursuit eye movements.**
13. **ADHD does not show the same oculomotor abnormalities as ASD**.
14. **Findings were partially replicated in external datasets**, but some differences exist across studies.


- ## 🔍 Related Work 



- ## 📝 Notes for Review 
