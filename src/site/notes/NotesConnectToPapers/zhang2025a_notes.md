---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/zhang2025a-notes/"}
---



# Exploring Eye-tracking based Biomarkers to Assess Cognitive Abilities in Autistic Children: A Feasibility Study

[[Literature_review/zhang2025a\|zhang2025a]]

## 📌 Summary


## 🔬 Methods 
### Participants

The study included **37 participants**, with a mix of **children with Autism Spectrum Disorder (ASD) and typically developing (TD) children**. Below are the key details about the participants:

- **23 children with ASD**
    - **Mean age:** 6.05 years (± 0.96)
    - **Number of girls:** 4
- **14 typically developing (TD) children**
    - **Mean age:** 6.96 years (± 0.78)
    - **Number of girls:** 3


[[Zhang_2025\|Zhang_2025]]

### Tasks for participants

The study provides **tasks to participants (children)** during the cognitive assessment process to evaluate their cognitive abilities, specifically focusing on autistic children. These tasks are embedded in human-computer interaction (HCI) protocols and utilize **serious games and interactive videos** to collect eye-tracking data. Below is an overview of the **tasks provided to the users (participants)**:

---

#### Pairing and Categorization Task

**Purpose:** Evaluate the user's ability to process and organize information, which forms the basis for higher-level cognitive functions like emotion recognition.

- **Format:**  
    Participants interact with a **serious game** on a touchscreen.
    
    - A cartoon character gives prompts to pair or categorize items based on **color, shape, or function**.
    - The task complexity increases progressively:
        - **Level 1 (Easy)**: Simple geometric shapes.
        - **Level 2 (Medium)**: Combination of geometric shapes and common objects.
        - **Level 3 (Hard)**: Complex daily objects.
- **Data Collected:** Eye-tracking features such as **response latency, total fixation duration (TFD), time to first fixation (TTFF)**, and fixation on specific regions (prompt and correct/wrong options).
    


#### Emotion Recognition Task

**Purpose:** Assess the user's ability to recognize and differentiate emotional expressions, a critical aspect of social cognition.

- **Format:**  
    Participants play a **serious game** where they must match emotional expressions with prompts.
    
    - **Emotions Tested:** Happiness, sadness, anger, neutrality.
    - **Levels of Difficulty:**
        - **Level 1:** Match emotions on the same cartoon character.
        - **Level 2:** Match emotions across different cartoon characters.
        - **Level 3:** Match cartoon emotions with real human faces.
        - **Level 4:** Match real human emotions with cartoon prompts.
- **Data Collected:** Eye-tracking features such as **mean fixation duration (MFD), visit count (VC), fixation on correct vs. incorrect emotions (FPCE/FPWE)**.
    

#### Social Interaction Task

**Purpose:** Evaluate social interaction cognition by observing how users perceive and respond to social cues like body language, facial expressions, and verbal communication.

- **Format:**  
    Participants watch **interactive videos** of actors performing social actions (e.g., waving hello, saying “Hi, how are you?”).
    
    - Each video is about **4 seconds long**.
    - Users’ eye-tracking data is collected as they observe the interaction.
- **Data Collected:**  
    Eye-tracking features such as **total fixation duration (TFD)** on different regions of interest (ROIs), including **face, eyes, mouth, and hand**.
    

#### Progression and Difficulty Levels

The tasks progressively increase in complexity to evaluate the participants’ cognitive limits and adaptability:

1. **Simple Categorization → Complex Object Matching** (Pairing Task).
2. **Cartoon Faces → Real Human Faces** (Emotion Task).
3. **Simple Greetings → Complex Social Cues** (Interaction Task).

This progression helps assess **different stages of cognitive processing**, from basic categorization to advanced social interaction.

#### Performance Measurement and Error Analysis

In addition to tracking the users’ gaze, the study records and analyzes their task performance:

- **Game Score:** Measures the number of incorrect responses in each task.
- **Error Consistency for Emotion (ECE):** Tracks whether users repeatedly choose the same incorrect emotion, indicating potential cognitive processing issues.

### System setup and hardware

- **Touchscreen display** (1920 × 1080 resolution) for interaction.
- **Azure Kinect DK** camera for capturing RGB images.
- **Central controller** to manage data collection.

### Data Analysis

#### Key Eye-tracking Features Collected Across Tasks

| **Task**                       | **Eye-tracking Feature**                                                  | Tag                                         |
| ------------------------------ | ------------------------------------------------------------------------- | ------------------------------------------- |
| **Pairing and Categorization** | Response latency (RL)                                                     | #Pupillometry/PLR/Latency                   |
|                                | Time to first fixation (TTFF)                                             | #EyeTracking/Fixation/FirstFixation/Latency |
|                                | Total fixation duration (TFD) on prompt and options                       | #EyeTracking/Fixation/Duration              |
| **Emotion Recognition**        | Mean fixation duration (MFD)                                              |                                             |
|                                | Fixation proportion on correct emotion (FPCE)                             |                                             |
|                                | Fixation proportion on wrong emotion (FPWE)                               |                                             |
| **Social Interaction**         | Total fixation duration (TFD) on facial regions (face, eyes, mouth, hand) | #EyeTracking/SocialAttention/Face           |

- ## 📊 Results & Key Findings 

### Key Findings:

- 1. Eye-tracking features (such as total fixation duration, response latency, time to first fixation, and visit count) showed significant differences between autistic and typically developing (TD) children, even when traditional cognitive assessment scores (e.g., WPPSI/WISC) did not.
- 2. Autistic children exhibited **longer response times** and **slower cognitive processing speeds** in tasks requiring pairing and categorization.
- 3. In emotion recognition tasks, autistic children made more mistakes, showed **less focus on correct emotions**, and tended to fixate more on incorrect choices, possibly due to **stereotyped behaviors or cognitive misunderstanding of emotions**.
- 4. In social interaction tasks, autistic children **spent significantly less time looking at facial regions**, particularly the mouth, suggesting **atypical gaze behavior** associated with social impairments.

### Implications:

4. The study highlights the **potential of eye-tracking features as objective biomarkers** for cognitive assessment in ASD.
5. It suggests that traditional assessments may miss important cognitive processing differences that eye-tracking can reveal.
6. The hierarchical structured protocols proposed in the study could be useful for identifying **specific cognitive processing challenges** in ASD, aiding in early diagnosis and intervention strategies.

- ## 🔍 Related Work 



- ## 📝 Notes for Review 
