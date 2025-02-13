---
{"dg-publish":true,"permalink":"/literature-review/lencastre2024a/","title":"Identifying Autism Gaze Patterns in Five-Second Data Records","tags":["autism","AI","eye-tracking","autism","diagnosis","eye","gaze","dynamics","intelligent","health","EyeTracking"]}
---


## Identifying Autism Gaze Patterns in Five-Second Data Records

> [!Cite]
> Lencastre, P., Lotfigolian, M., & Lind, P. G. (2024). Identifying Autism Gaze Patterns in Five-Second Data Records. _Diagnostics_, _14_(10), Article 10. [https://doi.org/10.3390/diagnostics14101047](https://doi.org/10.3390/diagnostics14101047)



## 📌 Summary

This study explores the **identification of autism gaze patterns** using **eye-tracking data from only five-second time windows**. Traditional autism diagnoses rely on **long observational periods**, making early screening challenging. The authors introduce a **new exploratory gaze metric (Λ)** that effectively differentiates **ASD (Autism Spectrum Disorder) and TD (Typically Developing) children**. Their approach **achieves a 93.9% classification accuracy**, outperforming standard **eye-tracking metrics** and state-of-the-art **AI classifiers**. This method offers a **simple, transparent, and effective diagnostic tool** requiring minimal data.


## 🔬 Methods

### Study Design

- **Observational study** analyzing **short-duration (5s) eye-tracking data** from ASD and TD children.
- **Comparison of classification models**:
    1. **Standard Eye-Tracking Metrics** (fixation/saccade dynamics).
    2. **State-of-the-Art AI Classifier** (InceptionTime deep learning model).
    3. **New Exploratory Gaze Metric (Λ)**.
- **Goal**: Evaluate whether **short gaze sequences** can provide a reliable ASD classification.

### Participants

- **Total sample**: **57 children** (age: **3–12 years**).
    - **ASD group**: **28 children** (Mean age: **7.74 years**, 24 males).
    - **TD group**: **29 children** (Mean age: **8.02 years**, 13 males).
- **Diagnosis confirmation**: ASD diagnosis validated using:
    - **Autism Diagnostic Interview-Revised (ADI-R)**.
    - **Autism Diagnostic Observation Schedule (ADOS-G)**.
    - **Clinical psychologist assessments** (CARS & Early Social Communication Scale).

### Tasks for Participants

- **Gaze-tracking experiment**:
    - **Viewing static images & videos** (human faces & non-organic distractors).
    - **Children instructed to follow social cues** (eye gaze, gestures, speech).
    - **Trials**:
        - **ASD children completed ~5.5 trials (154 total)**.
        - **TD children completed ~7.8 trials (225 total)**.

### System Setup and Hardware

|**Component**|**Description**|
|---|---|
|**Monitor**|**1280 × 1080 pixels**, 60 cm viewing distance.|
|**Eye-Tracking Device**|**SMI Red-M Eye Tracker** (60Hz sampling rate).|
|**Data Collected**|Right-eye gaze position, pupil diameter, saccade/fixation classification.|

### Data Analysis

#### Benchmark Models

1. **Standard Eye-Tracking Metrics**:
    
    - Fixation/saccade **velocity (µF, σS)**.
    - Probability of fixation-to-saccade transitions (**PFS, PSF**).
    - **Logistic Regression Model** for classification.
2. **AI-Based Classifier**:
    
    - **InceptionTime Deep Learning Model** (trained on time-series data).
    - Extracts **temporal gaze features** across multiple scales.
3. **New Exploratory Gaze Metric (Λ)**:
    
    - **Measures how much of an image is explored** within **5s**.
    - Quantifies **visited area in degrees of visual angle**.
    - Applied to **5-fold cross-validation** for classification.


## 📊 Results & Key Findings

### 1. Classification Accuracy of Different Models

|**Model**|**Accuracy**|**Sensitivity**|**Specificity**|**Precision**|
|---|---|---|---|---|
|**Standard Eye-Tracking Metrics**|**72.5%**|68.9%|74.4%|59.0%|
|**AI-Based Classifier**|**86.6%**|82.5%|89.9%|85.7%|
|**New Exploratory Gaze Metric (Λ)**|**93.9%**|95.1%|93.1%|89.6%|

### 2. Key Differences in Gaze Patterns Between ASD and TD Groups

|**Feature**|**ASD Group**|**TD Group**|**Statistical Significance**|
|---|---|---|---|
|**Fixation Speed (µF)**|**Faster**|Slower|**p = 0.0043**|
|**Fixation Dispersion (σF)**|No difference|No difference|**Not significant**|
|**Saccade Variability (σS)**|**Lower**|Higher|**p = 0.0001**|
|**Fixation-Saccade Ratio (PFS)**|**More frequent saccades**|Fewer saccades|**p = 0.022**|
|**Exploration Area (Λ, first 5s)**|**Higher (More exploration)**|Lower|**p < 0.00001**|

### 3. Advantage of the Exploratory Gaze Metric (Λ)

- Provides **higher classification accuracy (93.9%)** with **just 5s of gaze data**.
- Outperforms **AI-based classifiers and standard eye-tracking models**.
- **More interpretable** than deep learning (avoids “black-box” concerns).
- Requires **less computational power and training data**.


## 🔍 Related Work

- **Traditional ASD gaze research** relies on **long eye-tracking sessions (minutes to hours)**.
- **Previous studies** using **static image fixation** achieved ~**85% accuracy**.
- **Gaze dynamics (saccade velocity, fixation duration)** linked to **cerebellum & brainstem dysfunctions**.
- **AI models for ASD detection** consistently surpass **90% accuracy**, but raise concerns over **interpretability**.
- **This study introduces a simple metric (Λ) that rivals AI accuracy** while requiring only **5 seconds of data**.


## 📝 Observations

### Strengths of the Study

✅ **Highly accurate classification (93.9%)** using **just 5s of data**.  
✅ **Simple and interpretable**: Avoids **black-box AI models**.  
✅ **Efficient**: Uses **small data samples**, making **real-time screening feasible**.  
✅ **No reliance on complex saccade/fixation classification algorithms**.  
✅ **Potential for remote assessments** using **webcam-based gaze tracking**.

### Major Concerns and Challenges

⚠️ **Limited dataset**: **57 children**, with a **male bias (ASD: 24 males, TD: 13 males)**.  
⚠️ **Generalizability concerns**: Needs **validation on larger, diverse populations**.  
⚠️ **Short-term vs. long-term gaze behavior**: **Λ metric drops to 70% accuracy** when tested on later trial segments.  
⚠️ **No detailed analysis of cognitive or linguistic differences** among ASD participants.  
⚠️ **Potential confounds**: **Increased exploration** could stem from **sensory-seeking behaviors**, not just ASD-related attention patterns.


## 🚀 Future Directions

🔹 **Expand dataset**: Test **larger, more diverse groups** (age, gender, cognitive profiles).  
🔹 **Compare Λ with real-world gaze behaviors** (e.g., social interactions, school environments).  
🔹 **Evaluate the use of webcam-based gaze tracking** for **low-cost remote ASD screening**.  
🔹 **Integrate with multimodal assessments** (e.g., combine Λ with **facial expression analysis**).  
🔹 **Investigate how ASD traits (social avoidance, sensory preferences) affect Λ values**.


This study introduces **a powerful, simple metric (Λ) for ASD gaze classification**. By requiring **only 5s of data**, it **surpasses conventional eye-tracking models** and **rivals AI classifiers** while remaining **transparent and clinically useful**. 🚀
