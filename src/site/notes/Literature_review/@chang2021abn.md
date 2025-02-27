---
{"dg-publish":true,"permalink":"/literature-review/chang2021abn/","title":"Computational Methods to Measure Patterns of Gaze in Toddlers With Autism Spectrum Disorder","tags":["EyeTracking","EyeTracking/Gaze","toddlers","autism"]}
---


## Computational Methods to Measure Patterns of Gaze in Toddlers With Autism Spectrum Disorder

> [!Cite]
> Chang, Z., Di Martino, J. M., Aiello, R., Baker, J., Carpenter, K., Compton, S., Davis, N., Eichner, B., Espinosa, S., Flowers, J., Franz, L., Harris, A., Howard, J., Perochon, S., Perrin, E. M., Krishnappa Babu, P. R., Spanos, M., Sullivan, C., Walter, B. K., … Sapiro, G. (2021). Computational Methods to Measure Patterns of Gaze in Toddlers With Autism Spectrum Disorder. _JAMA Pediatrics_, _175_(8), 827–836. [https://doi.org/10.1001/jamapediatrics.2021.0530](https://doi.org/10.1001/jamapediatrics.2021.0530)

## 📌 Summary

This study explores a **mobile-based gaze-tracking tool** for early ASD detection in toddlers, using an **iPhone/iPad app** that presents **social and non-social stimuli** while analyzing eye movements with **computer vision algorithms**. A total of **993 toddlers (40 diagnosed with ASD)** participated. ASD toddlers showed **reduced gaze to social stimuli** and **impaired gaze-speech coordination**. A **decision tree classifier** using multiple gaze features achieved **AUC = 0.90**, indicating strong classification performance. However, **potential overfitting and lack of external validation** raise concerns about real-world applicability. The findings suggest promise for **scalable ASD screening**, but further validation is needed.

## 🔬 Methods 

### Study Design
    
**Prospective study** conducted in **pediatric primary care clinics**.
Data collection period: **December 2018 – March 2020**.
    
    
### Participants

| Characteristic                                 | Value                                                        |
| ---------------------------------------------- | ------------------------------------------------------------ |
| **Total Participants**                         | 993                                                          |
| **Mean Age (months)**                          | 21.1                                                         |
| **Age Range (months)**                         | 17.1 - 36.9                                                  |
| **Gender Distribution (Boys)**                 | 50.6%                                                        |
| **Racial/Ethnic Composition**                  | 59.8% White, 16.5% Black, 23.7% Other, 16.9% Hispanic/Latino |
| **Education Level of Caregivers**              | 75.7% College Degree, 19.6% High School, 4.6% < High School  |
| **Toddlers Diagnosed with ASD**                | 40                                                           |
| **Toddlers with Developmental/Language Delay** | 17                                                           |
| **Typically Developing Toddlers**              | 936                                                          |


---



### Tasks for participants

|**Movie**|**Purpose**|**ASD vs. TD Differences**|
|---|---|---|
|**Blowing Bubbles** (iPad/iPhone)|Social preference, response to **expectant pause**|ASD toddlers fixated more on the **toy**, not the person|
|**Spinning Top/Pinwheel** (iPad/iPhone)|Social preference|ASD toddlers focused more on the **object**|
|**Fun at the Park** (iPad only)|**Gaze coordination** during conversation|ASD toddlers showed **disorganized gaze shifts**|
|**Floating Bubbles**|Control for **dynamic stimuli**|No ASD vs. TD difference|
|**Puppy Movie**|Control for **gaze alternation ability**|No ASD vs. TD difference|

### System setup and hardware

- A **mobile application** on **iPhone/iPad** presented brief, **strategically designed** movies.
    - The **device’s front-facing camera** recorded the child’s gaze.

### Data Analysis
- **Gaze tracking**: Computer vision-based **iTracker** model analyzed fixation patterns.
    - **Gaze features extracted**:
        - Fixation duration
        - gaze alternations
        - gaze-speech synchronization
    - **Statistical Analysis**:
        - **Mann-Whitney U tests** for group comparisons.
        - **Decision Tree Classifiers** for gaze-based ASD classification.
    - **Performance Metric**:
        - **AUC (Area Under Curve) = 0.90**, indicating high discrimination between ASD and TD groups.

#### Face & Gaze Tracking Details

##### 1. Face Detection and Landmark Extraction

- **Algorithm Used**:
    
    - The study employed a **face detection and recognition algorithm** (likely a CNN-based model).
    - The algorithm detected **49 facial landmarks** using **IntraFace**, a well-known facial landmark extraction tool.
- **Landmarks Tracked**:
    
    - **Eye corners, nose, mouth, and jawline**
    - **Head pose angles (yaw, pitch, roll)** were estimated.
- **Error Correction Process**:
    
    - If the automatic tracking **confidence dropped below a threshold**, human reviewers manually corrected errors for **≤10 frames per video**.
    - **Common failure cases**:
        - Extreme head poses
        - Rapid head movements
        - Poor lighting conditions


##### 2. Attention Filtering (Valid Gaze Frames)

- To ensure **accurate gaze data**, a **filtering process** excluded frames where:
    - **Eyes were closed** (detected using an eye aspect ratio threshold).
    - **Estimated gaze was outside the screen area**.
    - **Head movements were too rapid**, leading to tracking failures.


##### 3. Gaze Estimation Model

- **Gaze Tracking Model Used**:
    
    - The study used **iTracker**, a **deep learning-based gaze estimation model**.
    - iTracker was originally trained on **thousands of gaze samples** and adapted to **estimate gaze direction** from **RGB video frames** captured by the device’s **front camera**.
- **Processing Pipeline**:
    
    1. **Face Detection** → Extract facial landmarks.
    2. **Head Pose Estimation** → Calculate yaw, pitch, roll.
    3. **Gaze Estimation** → iTracker predicts **horizontal & vertical gaze coordinates**.
    4. **Post-Processing** → Binarization of gaze data using **Otsu’s method** to separate left/right gaze shifts.


##### 4. Gaze Feature Extraction & Analysis

- **Fixation Detection**:
    
    - Used a clustering approach to determine **stable gaze points**.
    - Applied **silhouette scores** to evaluate **how well gaze points clustered**.
- **Gaze-Speech Synchronization**:
    
    - Converted **conversation speech data into a binary signal** (left/right speaker).
    - Compared **gaze shifts to conversation timing** using **time correlation metrics**.


##### Key Limitations in Face & Gaze Tracking

✅ **Strengths**:

- No need for **specialized infrared eye-tracking equipment**.
- Uses **widely available mobile devices (iPhone/iPad)**.
- Extracts both **fixation-based** and **time-based gaze behaviors**.

⚠ **Limitations**:

- **No explicit calibration step** → Lower accuracy than **high-end infrared eye trackers**.
- **Front-camera tracking less robust** than dedicated **eye-tracking hardware** (e.g., Tobii, Pupil Labs).
- **Head movements may introduce errors**, especially in toddlers who are less compliant

## 📊 Results & Key Findings 
- **Overall Findings**:
    
    - The study **successfully identified distinct eye-gaze patterns** in toddlers with ASD.
    - ASD toddlers exhibited **reduced gaze to social stimuli** and **deficits in gaze-speech coordination**.
    - The **combination of multiple gaze features** resulted in an **AUC of 0.90**, demonstrating high discrimination between ASD and typically developing (TD) toddlers.
- **Social Preference Movies (Blowing Bubbles, Spinning Pinwheel, Spinning Top)**:
    
    - **ASD toddlers spent more time looking at objects (toys) than people**.
    - During **expectant pauses in the Blowing Bubbles movie**, ASD toddlers **failed to shift attention back to the person**, unlike TD toddlers.
    - **Effect sizes were larger when analyzing gaze during key social moments**.
- **Gaze-Speech Coordination (Fun at the Park Movie)**:
    
    - **TD toddlers' gaze shifts synchronized with conversational turns**, showing **higher gaze-speech correlation**.
    - **ASD toddlers had more disorganized gaze**, failing to track conversation flow effectively.
    - **Silhouette scores for gaze clustering** were significantly lower in ASD toddlers.
- **Control Movies (Floating Bubbles, Puppy Movie)**:
    
    - No significant differences between ASD and TD groups.
    - Confirmed that differences in social movies were **specific to social attention rather than general visual engagement**.
- **Classification Performance (Machine Learning Models)**:
    
    - **Single gaze features achieved AUCs between 0.76 - 0.84**.
    - **Combining multiple gaze features improved classification accuracy**, reaching an **AUC of 0.90**.
    - **Performance remained stable across different demographic subgroups (e.g., race, ethnicity, gender)**.

![image-5-x65-y64.png](/img/user/Images/chang2021a/image-5-x65-y64.png)
## 🔍 Related Work 



## 📝 Observations

### Strengths of the Study

1. **Scalability and Accessibility**
    
    - The study presents a compelling case for using a mobile app to measure eye-gaze patterns in toddlers with ASD. The use of widely available devices (iPhone/iPad) and computer vision techniques makes the approach potentially scalable and practical in real-world settings.
2. **Strong Statistical Analysis**
    
    - The study reports an impressive area under the ROC curve (AUC = 0.90), suggesting high discriminatory power between ASD and typically developing toddlers. The use of multiple gaze features strengthens the reliability of the results.
3. **Novelty and Contribution**
    
    - The study identifies previously unreported gaze-speech coordination deficits in toddlers with ASD, advancing our understanding of early social attention deficits.
4. **Robust Sample and Inclusion of Underrepresented Groups**
    
    - With 993 toddlers participating, including diverse racial/ethnic backgrounds and varying levels of caregiver education, the study attempts to mitigate biases often present in ASD research.

### Major Concerns and Challenges

1. **Limited Diagnostic Ground Truth**
    
    - Only 40 toddlers were clinically diagnosed with ASD, making up a small fraction of the total sample (993). The ASD group was thus heavily outnumbered by typically developing toddlers. This imbalance may inflate the performance metrics due to class priors in classification models.
2. **Reliance on M-CHAT-R/F for Initial Screening**
    
    - The study uses the **Modified Checklist for Autism in Toddlers–Revised With Follow-up (M-CHAT-R/F)** as the primary screening tool for ASD risk. However, M-CHAT-R/F has known limitations, including high false positive rates, especially among lower-income and minority populations. This could introduce **selection bias**.
3. **Lack of Cross-Validation with Standard Eye-Tracking Methods**
    
    - While the app-based method is novel, there is no direct comparison with **gold standard** infrared-based eye-tracking technology. Without validating results against existing methods, it remains unclear whether the app is truly capturing **clinically relevant** gaze biomarkers or if the differences arise from technical limitations.
4. **Confounding Variables in Gaze Analysis**
    
    - The study assumes that reduced attention to social stimuli directly correlates with ASD, but gaze behavior can be influenced by factors such as:
        - **Cognitive ability** (e.g., non-verbal IQ)
        - **Attention span** (e.g., ADHD symptoms)
        - **Sensory processing differences**
        - **Fatigue or irritability** during testing The lack of a thorough analysis of these potential confounders weakens causal claims.
5. **Absence of Longitudinal Validation**
    
    - The study does not track whether children identified as “at-risk” based on gaze analysis **actually develop ASD** later in childhood. A longitudinal follow-up would be critical to assessing **predictive validity**.
6. **Potential Overfitting in Machine Learning Analysis**
    
    - The **DecisionTreeClassifier** used for gaze feature classification might not generalize well beyond the dataset. The AUC of 0.90 is promising, but without **external validation on an independent dataset**, the model may be overfitting.
7. **Industry Ties and Potential Conflict of Interest**
    
    - Several authors have disclosed financial ties to **Apple Inc.**, which has licensed technology based on this study. While this does not invalidate the findings, it raises concerns about **bias in reporting** and the potential for **selective emphasis on positive results**.