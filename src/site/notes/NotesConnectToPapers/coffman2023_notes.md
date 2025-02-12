---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/coffman2023-notes/"}
---

[[Literature_review/coffman2023\|coffman2023]]

## 📌 Summary

- The study explores whether **quantitative digital behavioral features** measured via the **SenseToKnow app** on a smartphone or tablet correlate with clinical autism assessments.
- **485 toddlers (43 with ASD)** participated, with behaviors measured via **computer vision analysis (CVA)** and compared to standardized clinical tools.
- Gaze variables related to **social attention** and **response to name** were associated with autism-related behaviors.
- **Fine motor skills** were linked to performance in a **bubble-popping game**.
- The study supports the **concurrent validity** of digital phenotyping for autism detection.
- Future research is needed to assess the **screening potential and longitudinal tracking** of autism behaviors using the app.

---

## 🔬 Methods

### **Study Design**

- **Observational study** conducted during **routine pediatric well-child visits**.
- Children interacted with the **SenseToKnow app**, while **video and touch data** were recorded.
- **Clinical assessments (ADOS-2, MSEL, M-CHAT-R/F, CBCL, SRS-2)** were used for validation.

---

### **Participants**

| Characteristic        | Value |
|----------------------|--------------------------------|
| **Total Sample**     | 485 toddlers (17–36 months old) |
| **ASD Group**       | 43 children |
| **Typically Developing (TD) Group** | 442 children |
| **Gender Distribution** | 53.8% boys, 46.2% girls |
| **Ethnicity**        | 10.5% Hispanic/Latino, 89.5% Non-Hispanic/Latino |
| **Race**            | 68.7% White, 10.9% Black, 9.9% Other |
| **Caregiver Education** | 80.6% College Degree, 16.5% High School, 2.9% < High School |
| **Inclusion Criteria** | Age 16–38 months, No sensory/motor impairments, Parent speaks English/Spanish |
| **Exclusion Criteria** | Illness/distress preventing participation |




### **Tasks for Participants**

| Task Name               | Purpose                                  | Format                        | Data Collected                  |
|-------------------------|---------------------------------|-------------------------|----------------------------|
| **Blowing Bubbles**     | Social attention assessment    | Video of an actor blowing bubbles | Gaze fixation on actor vs. bubbles |
| **Spinning Top**        | Social vs. Object Preference   | Actor playing with toy  | Gaze distribution between actor and toy |
| **Fun at the Park**     | Gaze-Speech Coordination       | Two people conversing   | Synchronization of gaze shifts with conversation |
| **Floating Bubbles**    | Control Task (Non-Social)     | Bubbles floating        | General visual engagement |
| **Mechanical Puppy**    | Response to Name              | Toy dog barking         | Head-turn response to name call |
| **Bubble-Popping Game** | Fine Motor Skills             | Touchscreen game        | Touch accuracy, force, speed |


### **System Setup and Hardware**

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **iPad 9.7-inch** | Displaying stimuli & recording gaze | 1920x1080 resolution, 30 FPS camera |
| **iPhone 8 Plus** | Alternative display & tracking | Similar to iPad |
| **SenseToKnow App** | Data Collection | Runs on iOS |
| **Computer Vision Analysis (CVA)** | Gaze & head tracking | Uses face recognition, gaze estimation, head pose tracking |


### Data Analysis

#### Collected Features in Dataset

| Feature Category | Feature Name  | Related Task | Measurement Description |
|----------------|--------------|-------------|--------------------------|
| **Social Attention** | Gaze Percent Social (GPS) | Blowing Bubbles, Spinning Top | Percentage of gaze directed at social stimuli |
| **Attention to Speech** | Gaze Speech Correlation (GSC) | Fun at the Park | Coordination of gaze with speech flow |
| **Response to Name** | Response to Name Ratio (RN) | Name Call in Mechanical Puppy | Proportion of times child oriented to name call |
| **Response Latency** | Response to Name Delay (RND) | Name Call in Mechanical Puppy | Time delay before looking towards name-caller |
| **Head Movements** | Head Movement Social (HMS) | Social movies | Frequency of head movements while watching social stimuli |
| **Fine Motor Skills** | Touch Popping Ratio (TPR) | Bubble-Popping Game | Accuracy of touch interactions |
| **Exploration Behavior** | Touch Exploration Percentage (TEP) | Bubble-Popping Game | Percentage of screen area explored |
| **Force Applied** | Touch Average Applied Force (TAAF) | Bubble-Popping Game | Pressure applied during touch |


## 📊 Results & Key Findings

### Key Findings:

- **Reduced social gaze** (lower **GPS**) was correlated with **higher autism severity** (SRS, CBCL, M-CHAT).
- **Delayed response to name** (higher **RND**) was linked to **lower expressive language scores** (MSEL).
- **Reduced gaze-speech coordination** (lower **GSC**) was associated with **weaker language skills**.
- **Increased head movements during social stimuli** (higher **HMS**) correlated with **higher autism scores**.
- **Lower fine motor skills** in ASD toddlers were reflected in **poorer touch accuracy** (TPR) and **reduced screen exploration** (TEP).
- **Linear regression models** found that **GPS, GSC, and RN** were the **strongest predictors of autism scores**.

---

### Implications for the Project

- **Confirms feasibility of scalable, digital behavioral assessments for ASD.**
- **Gaze tracking and motor behavior analysis can be used as biomarkers.**
- **Highlights need for improved fine motor assessments in digital tools.**
- **Supports use of AI-driven gaze analysis for real-world ASD screening.**

---

## 🔍 Related Work

- Study builds on prior work by [[Literature_review/chang2021abn\|chang2021abn]] on **gaze tracking for ASD detection**.
- Similar to **Perochon et al. (2021, 2022)**, which analyzed **fine motor skills via touchscreen games**.
- Reinforces findings from **Dawson et al. (2018)** that **autistic toddlers show increased head movements**.
- Expands **Campbell et al. (2019)** who used **computer vision for social attention analysis**.



## 📝 Observations

### Strengths of the Study

✅ **Large sample size (485 toddlers), diverse demographics.**  
✅ **Mobile-based system increases accessibility and scalability.**  
✅ **Validated against gold-standard ASD measures (ADOS-2, MSEL, CBCL).**  
✅ **Computer vision analysis (CVA) eliminates observer bias.**  
✅ **Multi-modal approach (gaze, head movement, touch, response to name).**



### Major Concerns and Challenges

⚠ **Potential Overfitting in Predictive Models**

- High AUC scores without external validation suggest **possible overfitting**.
- No **cross-validation or independent test set** reported.

⚠ **Limited ASD Sample Size (43 children)**

- Could inflate **classification performance** due to class imbalance.
- Need **larger, independent ASD validation cohorts**.

⚠ **No Comparison with Gold-Standard Eye-Tracking Devices**

- Reliance on **mobile front camera tracking** might reduce accuracy.
- Comparison with **infrared eye-tracking tools (Tobii, Pupil Labs)** needed.

⚠ **Lack of Longitudinal Data**

- Does **not track changes over time**, limiting clinical use for **progress monitoring**.

⚠ **Conflict of Interest Concerns**

- Several authors have **financial ties to Apple Inc.**, which has **licensed related technology**.
- Raises questions about **potential bias in reporting results**.