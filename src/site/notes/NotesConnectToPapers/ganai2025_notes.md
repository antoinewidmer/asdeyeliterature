---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/ganai2025-notes/"}
---


## Zotero link

[[Literature_review/ganai2025\|ganai2025]]
## 📌 Summary

This study explores the potential of gait deviations as an early biomarker for Autism Spectrum Disorder (ASD). By utilizing a single RGB camera and pose estimation technology (MediaPipe), the study analyzed gait patterns in children with ASD and typically developing (TD) children. The results indicated that children with ASD exhibit shorter step lengths, reduced right elbow angles, and increased right shoulder angles. Four machine learning (ML) models were tested to classify ASD based on gait parameters, with **binomial logistic regression achieving the highest accuracy (82%)**. The findings highlight the feasibility of using gait analysis and ML techniques for early ASD detection.

---

## 🔬 Methods

### Study Design

The study employs a **case-control design**, comparing gait parameters between **32 children with ASD** and **29 typically developing (TD) children** using **computer vision-based gait analysis**.

### Participants

- **ASD Group**: 32 children (mean age: **5.97 years**)
    
- **TD Group**: 29 children (mean age: **4.86 years**)
    
- **Recruitment**:
    
    - ASD children were recruited from rehabilitation centers in Kanpur, India.
    - TD children were enrolled from nearby schools.
- **Exclusion Criteria**:
    
    - Neurological or genetic conditions
    - Preterm birth
    - Medication affecting the nervous system in the past week
- **Clinical Assessments**:
    
    - **Indian Scale for the Assessment of Autism (ISAA)**: Used to confirm ASD diagnosis.
    - **Vineland Adaptive Behavior Scale-3 (VABS-3)**: Used to assess adaptive functioning.

### Tasks for Participants

- Each child walked along a **4.57m walking pathway** for **120 seconds** or at least **two trials**.
- A **DJI Osmo Pocket RGB camera** recorded gait movements.
- Parents observed the test from an adjacent room.

### System Setup and Hardware

- **Camera**:
    - **DJI Osmo Pocket**
    - 3-axis stabilization, 80-degree field of view
    - Resolution: **1920×1080 pixels**, 30 fps
- **Pose Estimation Model**:
    - **Google MediaPipe (MP)**
    - Extracted **18 key joint points** from video data
- **Processing Pipeline**:
    - Trigonometric equations calculated **joint angles**.
    - **Savitzky-Golay filter** was applied to smooth gait signals.

### Data Analysis

- **Statistical Tests**:
    - **Mann-Whitney U test** (for group comparisons)
    - **Spearman’s correlation** (for gait-ASD symptom relations)
- **Machine Learning Classification**:
    - **Features**: Step length, right elbow angle, right shoulder angle
    - **Models Used**:
        - **Random Forest (RF)**
        - **XGBoost**
        - **Support Vector Machine (SVM-RBF)**
        - **Binomial Logistic Regression (Logit)**
    - **Evaluation Metrics**:
        - **Accuracy, Sensitivity, Specificity, AUC (Area Under Curve)**
    - **Best Model**: **Logistic Regression (82% accuracy, AUC = 0.97)**

---

## 📊 Results & Key Findings

- **Gait Differences in ASD vs. TD**:
    
    - **Step Length**: **↓ Shorter** in ASD children (**p = 0.028**)
    - **Right Elbow Angle**: **↓ Lower** in ASD (**p = 0.025**)
    - **Right Shoulder Angle**: **↑ Higher** in ASD (**p = 0.048**)
- **Correlation with ASD Symptoms**:
    
    - **Right Shoulder Angle** positively correlated with **sensory symptoms** (**ρ = 0.373, p = 0.039**).
- **Machine Learning Performance**:
    
    - **Logistic Regression** performed best (**Accuracy = 82%, AUC = 0.97**).
    - **XGBoost** was the worst (**Accuracy = 64%, AUC = 0.65**).

---

## 🔍 Related Work

- **Motor deficits in ASD** have been previously observed in studies showing:
    - **Shorter stride length**
    - **Slower walking speed**
    - **Increased gait variability**
- The **cerebellum and basal ganglia** have been implicated in ASD-related gait differences.
- Other studies have used **machine learning for ASD detection**, with some achieving **up to 95% accuracy** using neural networks and more features.

---

## 📝 Observations

### Strengths of the Study

✅ **Non-invasive, low-cost method**: Uses only a single RGB camera (vs. expensive motion capture systems).  
✅ **Objective measurement**: Reduces reliance on subjective behavioral assessments.  
✅ **Good machine learning performance**: Logistic regression achieved **82% accuracy** with only three features.  
✅ **Potential for early ASD detection**: Motor impairments appear earlier than social deficits.

### Major Concerns and Challenges

⚠ **Small sample size**: **Only 61 children** (32 ASD, 29 TD) → limited generalizability.  
⚠ **Single-camera limitation**: 2D pose estimation may introduce inaccuracies.  
⚠ **Weak correlations with ASD symptoms**: Gait differences may not strongly predict ASD severity.  
⚠ **Lack of sex-specific analysis**: Could affect generalizability.

---

### Future Directions

- **Larger sample size** to improve generalizability.
- **Multiview camera systems** to improve gait analysis accuracy.
- **Integration with other ASD biomarkers** (e.g., **eye tracking, EEG**).
- **Advanced deep learning models** for better classification.

This study **paves the way for automated, computer-assisted early ASD detection using gait analysis**. However, further research is needed to refine accuracy and robustness.