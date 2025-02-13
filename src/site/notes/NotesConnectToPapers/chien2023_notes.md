---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/chien2023-notes/"}
---

[[Literature_review/chien2023\|chien2023]]

## 📌 **Summary**

- **Objective**:
    
    - The study develops a **game-based social interaction platform** incorporating **eye-tracking technology** to assess **social cognition and gaze behavior** in children and preadolescents with autism.
    - The platform aims to **quantify social attention deficits** and **evaluate cognitive functions through serious games**.
- **Methodology**:
    
    - **Three game modules** focused on:
        1. **Gaze following & joint attention**
        2. **Facial emotion recognition**
        3. **Complex social interactions**
    - **Eye-tracking metrics** (fixation duration, saccades, time-to-first-fixation) were used to identify **biomarkers of ASD**.
- **Findings**:
    
    - **Children with ASD exhibited shorter fixation durations on positive emotions and social stimuli**.
    - **ASD participants had longer saccade durations**, particularly when reading descriptions of social scenarios.
    - **Autistic children showed reduced gaze-following abilities**, especially when tracking multiple characters.
    - **Eye-tracking signals were validated as potential biomarkers for ASD cognitive assessment**.

---

## 🔬 Methods

### Study Design

- **Experimental study** testing a **game-based social training interface** for **ASD children and teenagers**.
- **Eye-tracking technology** recorded **gaze patterns and visual attention behaviors**.
- **Participants were divided into two age groups**:
    1. **Toddlers & young children (4–7 years old)**
    2. **Preadolescents & teenagers (11–13 years old)**
- **Three modules were developed**, each targeting different social and cognitive skills.

### Participants

| Characteristic       | Value |
|---------------------|--------------------------------|
| **Total Sample**    | 48 participants (14–13 years old) |
| **Autism Group**    | 18 children |
| **Typically Developing (TD) Group** | 30 children |
| **Age Groups** | 4–7 years (toddlers & children), 11–13 years (preadolescents & teenagers) |
| **Gender Distribution** | 10 males, 8 females (ASD); 19 males, 11 females (TD) |
| **Recruitment Site** | National Taiwan University Hospital |
| **Inclusion Criteria** | Diagnosed ASD (DSM-5 & ICD-10 criteria) |
| **Exclusion Criteria** | Comorbid major neuropsychiatric disorders (epilepsy, bipolar, schizophrenia) |


### Tasks for participants

| Task Name                | Purpose                                    | Format                        | Data Collected |
|--------------------------|--------------------------------|-------------------------|----------------------------|
| **Joint-Attention Game** | Assess gaze-following & joint attention | Cartoon-based interactive task | Fixation time, reaction time, accuracy |
| **Emotion-Recognition Game** | Evaluate emotion perception & empathy | Matching cartoon faces with real emotions | Fixation patterns, emotion-matching accuracy |
| **Social Interaction Game** | Simulate complex social interactions | Role-playing with animated characters | Facial expression recognition, appropriate vs. inappropriate behavior selection |


### System setup and hardware

#### Eye-Tracking Data Collection

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **Tobii X2-30 Eye-Tracker** | Gaze tracking | 30 Hz sampling rate, infrared-based |
| **Tobii Pro Studio** | Eye-tracking data processing | Fixation & saccade analysis |
| **Unity 3D** | Game platform development | Custom animations & role-playing scenarios |
| **TONI-4 (Nonverbal IQ Test)** | Cognitive assessment | Standardized test for abstract reasoning |


### Data Analysis

| Feature Category         | Feature Name              | Related Task | Measurement Description |
|--------------------------|----------------------|-------------|--------------------------|
| **Gaze Behavior**       | Fixation Percentage  | Joint-Attention Game | % time looking at correct vs. incorrect gaze cues |
| **Emotion Processing**  | Emotion-Matching Accuracy | Emotion-Recognition Game | Correctly matching cartoon & real facial expressions |
| **Visual Exploration**  | Saccade Duration | Social Interaction Game | Time spent scanning different social features |
| **Social Attention**    | Fixation on Eyes vs. Mouth | Social Interaction Game | % fixation time on socially relevant features |


The study utilized **statistical tests** to analyze **task performance and eye-tracking features** between **autistic (ASD) and typically developing (TD) children**. Below is a detailed breakdown of the analysis performed:



#### 1. Statistical Analysis of Task Performance

**Goal:** Compare **task accuracy and reaction times** between ASD and TD groups.

- **Statistical Tests Used:**
    - **Independent Samples t-test** (for normally distributed data)
    - **Mann-Whitney U test** (for non-normally distributed data)
- **Key Findings:**
    - **Gaze Following Task:** No significant difference in accuracy.
    - **Emotion Recognition Task:**
        - **ASD children had lower accuracy for happy emotions (p = 0.047).**
    - **Social Interaction Task:**
        - No significant difference in accuracy, but **ASD children had longer reaction times**.

#### 2. Eye-Tracking Data Analysis

**Goal:** Identify differences in gaze patterns between ASD and TD children.

##### Eye-Tracking Features Extracted:

|Eye Movement Metric|Corresponding Tag|
|---|---|
|**Total Fixation Duration (TFD):** Total time fixating on a target.|[#EyeTracking/Fixation/Duration](app://obsidian.md/index.html#EyeTracking/Fixation/Duration)|
|**Saccade Duration (SD):** Time taken to shift gaze between elements.|[#EyeTracking/Saccades/Latency](app://obsidian.md/index.html#EyeTracking/Saccades/Latency)|
|**Time to First Fixation (TTFF):** Time before first looking at a target.|[#EyeTracking/Fixation/FirstFixation/Latency](app://obsidian.md/index.html#EyeTracking/Fixation/FirstFixation/Latency)|
|**First Fixation Duration (FFD):** Time spent during the first gaze on an object.|[#EyeTracking/Fixation/FirstFixation/Duration](app://obsidian.md/index.html#EyeTracking/Fixation/FirstFixation/Duration)|
|**Average Fixation Time (AFT).**|[#EyeTracking/Fixation/Duration](app://obsidian.md/index.html#EyeTracking/Fixation/Duration)|
|**Average Saccade Time (AST).**|[#EyeTracking/Saccades/AverageTime](app://obsidian.md/index.html#EyeTracking/Saccades/AverageTime)|

---

##### (A) Fixation Duration Analysis

- **Statistical Test Used:**
    - **Mann-Whitney U test** (since fixation duration data was not normally distributed).
- **Key Findings:**
    - **Fixation on Positive Emotions:**
        - ASD children **spent significantly less time looking at happy faces** than TD children (**p = 0.047**).
    - **Fixation on Social Captions:**
        - ASD children **fixated significantly longer on text-based social captions** than TD children (**p = 0.018**).
    - **Fixation on Multiple Targets:**
        - ASD children **spent less time on multiple social targets** than TD children (**p = 0.042**).

##### (B) Saccade Duration Analysis

- **Statistical Test Used:**
    - **Wilcoxon Signed-Rank Test** (since saccade durations were skewed).
- **Key Findings:**
    - ASD children **had significantly longer saccade durations when reading social cues** compared to TD children (**p = 0.018**).
    - ASD children **took longer to shift gaze between elements**, indicating **delayed visual attention shifting**.

##### (C) Correlation Analysis

**Goal:** Identify relationships between eye-tracking features and cognitive assessments (IQ, working memory).

- **Statistical Test Used:**
    - **Pearson Correlation Coefficient (for normally distributed data)**.
- **Key Findings:**
    - **Positive correlation between fixation duration on happy faces and IQ scores in TD children.**
    - **Negative correlation between saccade duration and working memory in ASD children.**

---

### Outlier Handling and Data Validation

- **Normality Testing:**
    - **Shapiro-Wilk Test** was used to check if data was normally distributed.
    - **Results:**
        - Some eye-tracking features were **not normally distributed**, requiring the use of **non-parametric tests** (Mann-Whitney U, Wilcoxon Signed-Rank Test).
- **Variance Homogeneity Testing:**
    - **Levene’s Test** was performed before applying t-tests.
- **Data Exclusions:**
    - **Participants with missing gaze data >30% were excluded.**
    - **Reaction times exceeding 3 standard deviations were removed.**

---

### Final Summary of Statistical Tests Used

|**Test**|**Purpose**|**Application in Study**|
|---|---|---|
|**Independent Samples t-Test**|Compare means between ASD and TD groups|Task accuracy and reaction times|
|**Mann-Whitney U Test**|Compare non-normal distributions|Fixation durations, saccades|
|**Wilcoxon Signed-Rank Test**|Compare paired data|Social interaction fixation data|
|**Pearson Correlation**|Assess relationships|Eye-tracking features vs. cognitive scores|
|**Shapiro-Wilk Test**|Check normality|Task performance and gaze features|
|**Levene’s Test**|Check variance homogeneity|Ensured valid t-test results|

## 📊 **Results & Key Findings**

### **Key Findings:**

- **ASD children showed shorter fixation durations on positive emotional expressions**.
- **Increased saccade durations in ASD when reading social scenario descriptions**.
- **ASD children spent less time tracking multiple targets in gaze-following tasks**.
- **No significant difference in task reaction times between ASD and TD groups**.
- **Facial emotion recognition accuracy was lower in ASD but not statistically significant**.

### **Implications for the Project**

- **Supports the use of eye-tracking for ASD cognitive assessment in game-based interventions**.
- **Findings reinforce social attention deficits as a core ASD feature**.
- **Potential applications for adaptive intervention tools that adjust difficulty based on gaze behavior**.

---

## 🔍 **Related Work**

- **Aligns with studies (Wang et al., 2020) showing altered gaze patterns in ASD**.
- **Expands research on serious games (Babu et al., 2020) by integrating gaze-based social cognition tasks**.
- **Contrasts with EEG-based ASD cognitive assessments, focusing solely on gaze-tracking**.

---

## 📝 **Observations**

### **Strengths of the Study**

✅ **Multimodal assessment integrating game-based tasks and eye-tracking**.  
✅ **First study in East Asia to use gaze tracking for ASD assessment in a game-based platform**.  
✅ **Structured modules allow for stratification of ASD severity based on gaze behavior**.  
✅ **Validated against standardized diagnostic tools (DSM-5, ICD-10, TONI-4)**.

---

### **Major Concerns and Challenges**

⚠ **Small Sample Size & Limited Diversity**

- Only **18 ASD children** → **insufficient for generalizable conclusions**.
- **No data on socioeconomic backgrounds** or **cultural gaze biases**.

⚠ **Lack of Longitudinal Tracking**

- Study does **not track improvements in social cognition over time**.
- Would benefit from **pre-post intervention comparison**.

⚠ **Reliance on Cartoon-Based Stimuli**

- **Findings may not generalize to real-world social interactions**.
- **Faces used in emotion recognition tasks are highly stylized**, possibly affecting ASD children's responses.

⚠ **No Integration with Physiological or Machine Learning Models**

- Could benefit from **EEG-based emotion recognition or deep learning for gaze classification**.
- **No mention of automated ASD classification accuracy**.