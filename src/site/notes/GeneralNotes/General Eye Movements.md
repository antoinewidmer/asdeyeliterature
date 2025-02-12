---
{"dg-publish":true,"permalink":"/general-notes/general-eye-movements/"}
---



Eye movements are broadly categorized into **fixation-based, saccade-based, gaze transition, pupillometry, and blink-based metrics**. 

---

## **Fixation-Based Metrics**

Fixations refer to **stable gaze points where the eyes remain focused on a target**.

| **Metric**                  | **Definition**                                                            | **Common Interpretation**                                                | Tag                                 |
| --------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ----------------------------------- |
| **Fixation Duration**       | Time spent looking at a single target (measured in milliseconds).         | Longer fixations indicate **higher interest or cognitive load**.         | #EyeTracking/Fixation/Duration      |
| **Fixation Count**          | Total number of fixations on a specific object or area.                   | More fixations suggest **higher attention or difficulty in processing**. |                                     |
| **First Fixation**          | The first object/region the gaze lands on when a stimulus appears.        | Indicates **initial visual preference**.                                 | #EyeTracking/Fixation/FirstFixation |
| **Fixation Location (ROI)** | Identifies which **region of interest (ROI)** the subject is fixating on. | Used to analyze **social vs. non-social preferences**.                   |                                     |

✅ **Fixation duration is a key metric for autism and cognitive load studies.**

---

## **Saccade-Based Metrics (Rapid Eye Movements)**

Saccades are **quick jumps between fixations**, essential for **visual exploration**.

| **Metric**                | **Definition**                                                  | **Common Interpretation**                                                                     | Tag                                |
| ------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ---------------------------------- |
| **Saccade Count**         | Total number of rapid eye movements (shifts between fixations). | More saccades suggest **higher exploratory behavior**.                                        | #EyeTracking/Saccades/Count        |
| **Saccade Rate**          | Number of saccades per second.                                  | Lower rates indicate **attention focus**, higher rates indicate **visual searching**.         |                                    |
| **Saccade Latency**       | Time taken before initiating a saccade after stimulus onset.    | Longer latency suggests **delayed response or cognitive effort**.                             | #EyeTracking/Saccades/Latency      |
| **Saccade Amplitude**     | Distance (in degrees) between fixations.                        | Shorter amplitudes suggest **local scanning**, longer amplitudes suggest **global scanning**. | #EyeTracking/Saccades/Amplitude    |
| **Peak Saccade Velocity** | Maximum speed of eye movement per second.                       | Higher velocities occur in **quick scanning tasks**.                                          | #EyeTracking/Saccades/PeakVelocity |

✅ **Saccade rate and amplitude are important in ASD studies (lower rates indicate reduced exploration).**

---

## **Gaze Transition Metrics**

These metrics measure **how often the eyes switch between different objects**.

| **Metric**                | **Definition**                                                          | **Common Interpretation**                                         | Tag                               |
| ------------------------- | ----------------------------------------------------------------------- | ----------------------------------------------------------------- | --------------------------------- |
| **Gaze Alternation Rate** | Number of gaze shifts between two stimuli.                              | Lower rates in ASD suggest **reduced social attention shifting**. | #EyeTracking/Gaze/AlternationRate |
| **Dwell Time**            | Time spent looking at an object before switching gaze.                  | Longer dwell time indicates **sustained attention**.              | #EyeTracking/Gaze/DwellTime       |
| **Gaze Following**        | Measures whether an individual follows another person's gaze direction. | Used in **social cognition research**.                            |                                   |
| **Gaze Contingency**      | Tracks whether a subject’s gaze aligns with expected visual stimuli.    | Important for **attention-based studies**.                        |                                   |

✅ **Lower gaze alternation and longer dwell times suggest social attention deficits in ASD.**

---

## **Pupillometry (Pupil-Based Metrics)**

Pupillometry measures **pupil dilation and constriction**, which reflect **cognitive load, emotional responses, and autonomic arousal**.

| **Metric**                       | **Definition**                                                   | **Common Interpretation**                                              | Tag                                    |
| -------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------------- | -------------------------------------- |
| **Pupil Diameter**               | Size of the pupil in millimeters.                                | Larger pupils indicate **higher cognitive load or emotional arousal**. |                                        |
| **Pupillary Light Reflex (PLR)** | Pupil response to sudden changes in light intensity.             | **Delayed PLR is associated with ASD.**                                | #Pupillometry/PLR/Latency              |
| **Pupil Dilation Latency**       | Time taken for pupil dilation to begin after a stimulus appears. | **Slower dilation can indicate cognitive effort.**                     |                                        |
| **Pupil Constriction Velocity**  | Speed at which the pupil constricts in response to light.        | Slower velocity is linked to **neurological impairments**.             | #Pupillometry/PLR/ConstrictionVelocity |

✅ **Pupil dilation is a strong biomarker for autism, cognitive load, and emotional processing.**

---

## **Blink-Based Metrics**

Blink patterns can indicate **cognitive processing, arousal, or attentional states**.

| **Metric**         | **Definition**                                              | **Common Interpretation**                                   | Tag                           |
| ------------------ | ----------------------------------------------------------- | ----------------------------------------------------------- | ----------------------------- |
| **Blink Rate**     | Number of spontaneous blinks per minute.                    | Lower blink rates in ASD suggest **hyper-focus**.           | #EyeTracking/Blink/Rate       |
| **Blink Latency**  | Time taken before the first blink after a stimulus appears. | Shorter latency suggests **higher stress or discomfort**.   | #EyeTracking/Blink/Latency    |
| **Blink Duration** | Time a blink lasts (in milliseconds).                       | Longer durations suggest **fatigue or cognitive overload**. | #EyeTracking/Blink/Duration   |

✅ **Lower blink rates in ASD indicate reduced social engagement and increased focus on repetitive stimuli.**

---

## **Specialized Eye-Tracking Metrics**

Some studies use **task-specific eye movements**.

|**Metric**|**Definition**|**Use Case**|
|---|---|---|
|**Anti-Saccade Errors**|% of incorrect saccades in an anti-saccade task (looking at the target instead of away).|Measures **inhibitory control in ASD and ADHD**.|
|**Catch-Up Saccades**|Corrective saccades to track a moving target.|**Higher rates indicate tracking deficits (common in ASD).**|
|**Smooth Pursuit Gain**|Accuracy of eye velocity matching a moving target.|Used for **motion tracking studies**.|
|**Fixation Preference (Social vs. Non-Social)**|% of time looking at faces vs. objects or geometric stimuli.|Used in **autism screening (e.g., GeoPref Test).**|

✅ **Fixation preference and anti-saccade errors are strong ASD-related eye-tracking biomarkers.**


## **Micro-Saccades: A Critical Eye-Tracking Metric**

Micro-saccades are **small, involuntary eye movements** that occur during fixation. They play a key role in **visual perception, attention, and neurological processing**.

---

### **What Are Micro-Saccades?**

- **Definition:** Small, rapid, and involuntary eye movements occurring during prolonged fixation.
- **Amplitude:** Typically **less than 1° of visual angle**.
- **Duration:** ~20–50 milliseconds.
- **Frequency:** **1–2 micro-saccades per second**.

✅ **Micro-saccades help refresh visual information and prevent visual fading during fixation.**  
✅ **They are linked to attention shifts and cognitive load.**

---

### **Key Micro-Saccade Metrics**

| **Metric**                  | **Definition**                                   | **Common Interpretation**                                                 | Tag |
| --------------------------- | ------------------------------------------------ | ------------------------------------------------------------------------- | --- |
| **Micro-Saccade Rate**      | Number of micro-saccades per second.             | Lower rates in ASD suggest **reduced active scanning**.                   |     |
| **Micro-Saccade Amplitude** | Distance of micro-saccade movement (in degrees). | Smaller amplitudes in ASD may indicate **hypoactive visual exploration**. |     |
| **Micro-Saccade Direction** | Preferred direction of micro-saccades.           | Linked to **spatial attention shifts**.                                   |     |
| **Micro-Saccade Latency**   | Time from fixation onset to first micro-saccade. | Longer latency suggests **delayed attentional shifts**.                   |     |
| **Micro-Saccade Velocity**  | Speed of micro-saccades in degrees/second.       | Reduced velocity is linked to **neurological disorders**.                 |     |

---

### **Role of Micro-Saccades in Autism & ADHD Research**

- **ASD:** Lower micro-saccade rates, suggesting **reduced active scanning**.
- **ADHD:** Higher micro-saccade rates, indicating **increased visual impulsivity**.
- **Neurotypicals:** Micro-saccades occur **predictably before voluntary saccades**.

✅ **Micro-saccades reveal differences in attentional control and neural processing across ASD, ADHD, and neurotypical populations.**

---

### **How Micro-Saccades Are Measured**

- **High-speed eye-tracking systems (≥500Hz)** are needed.
- **Algorithms detect sub-degree eye movement oscillations**.

✅ **Commonly used tools:**

- **EyeLink 1000 (500–1000Hz)**
- **Tobii Pro Spectrum (600Hz)**