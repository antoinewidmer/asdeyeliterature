---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/ko2023-notes/"}
---


### 📌 Summary

- The study investigates whether **joint attention behaviors** can be used for **automated ASD detection and symptom severity assessment** using **deep learning (DL) models**.
- **95 children (45 with ASD, 50 typically developing)** between **24-72 months old** were assessed using a **joint attention task protocol** with video-based behavioral analysis.
- A **deep learning system** was trained on **three types of joint attention behaviors**:
    - **Initiation of Joint Attention (IJA)**
    - **Low-Level Response to Joint Attention (RJA)**
    - **High-Level RJA**
- The **DL model performed with high accuracy**, achieving **99.6% AUROC for ASD detection** and **90.3% AUROC for symptom severity classification**.
- Results suggest that **DL-based joint attention analysis may enable scalable and objective ASD screening tools**.

---

### 🔬 Methods

#### Study Design

- **Prospective diagnostic study** conducted in multiple institutions in South Korea.
- Video data collected from **August 5, 2021 – July 18, 2022**.
- Three joint attention tasks were conducted to elicit **specific gaze and attention patterns**.
- **DL models** were trained on extracted behavioral data for **ASD classification and symptom severity estimation**.

---

#### Participants

| Characteristic       | Value |
|---------------------|--------------------------------|
| **Total Sample**    | 95 children (24–72 months old) |
| **Autism Group**    | 45 children (53.3% boys, 46.7% girls) |
| **Typically Developing (TD) Group** | 50 children (54% boys, 46% girls) |
| **Mean Age (ASD Group)** | 48.0 months (SD = 13.4) |
| **Mean Age (TD Group)** | 47.9 months (SD = 12.5) |
| **IQ Scores (ASD Group <48 months)** | 60.1 (SD = 15.4) |
| **IQ Scores (TD Group <48 months)** | 104 (SD = 19.1) |
| **Autism Severity Measure** | Korean CARS-2 & ADOS-2 |
| **Inclusion Criteria** | Clinical ASD diagnosis (ADOS-2), ability to sit independently |
| **Exclusion Criteria** | Visual or auditory deficits, severe cognitive impairment |


**Criticism**:

- **Sample size is relatively small**, especially for **deep learning training**.
- **IQ differences between ASD and TD groups** may confound results.
- **Homogeneous ethnic background (all Korean participants)** limits generalizability.

---

#### Tasks for Participants

| Task Name                | Purpose                                    | Format                        | Data Collected |
|--------------------------|--------------------------------|-------------------------|----------------------------|
| **Initiation of Joint Attention (IJA)** | Assess child-initiated gaze following | Toy-based interaction task | Gaze alternation, facial expressions |
| **Low-Level Response to Joint Attention (RJA)** | Measure attention to near-pointed objects | Examiner points to nearby objects | Fixation time, gaze latency |
| **High-Level Response to Joint Attention (RJA)** | Measure attention to far-pointed objects | Examiner points to distant objects | Head-turning response, fixation duration |


**Criticism**:

- **Lacks spontaneous social interactions**, which are critical in ASD diagnosis.
- **No baseline measure for general attention abilities**, making it unclear if **gaze deficits are ASD-specific**.

---

#### System Setup and Hardware

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **Sony DSC-RX100 IV Camera** | Video recording | 1920x1080 resolution, 30 FPS |
| **Custom Deep Learning System** | ASD classification | CNN + LSTM-based model |
| **Python (SciPy, Statsmodels)** | Statistical analysis | Computes AUROC, accuracy, recall |
| **Grad-CAM Attention Visualization** | Explainability | Highlights important video frames |

**Criticism**:

- **No mention of calibration for gaze-tracking accuracy**.
- **Frame rate (30 FPS) may be insufficient** for detecting subtle eye movements.
- **Lack of comparison with traditional eye-tracking devices**.

---

#### Data Analysis

| Feature Category        | Feature Name             | Related Task | Measurement Description |
|------------------------|-------------------------|-------------|--------------------------|
| **Gaze Behavior**   | Fixation Percentage  | IJA, RJA | Time spent looking at examiner vs. objects |
| **Head Orientation** | Response Latency  | High-Level RJA | Time taken to shift gaze to target |
| **Attention Stability** | Gaze Consistency | All tasks | Variation in gaze fixation over time |
| **Compliance Score** | Task Engagement | All tasks | Child's attentiveness across trials |


**Criticism**:

- **No real-world validation**—data collected in a controlled **lab setting**.
- **Reliance on video-based behavioral analysis** instead of **direct gaze-tracking technology**.

---

### 📊 Results & Key Findings

#### Key Findings:

- **ASD vs. TD classification was highly accurate**, with AUROC scores of **99.6% (IJA), 99.8% (Low-Level RJA), and 99.5% (High-Level RJA)**.
- **ASD symptom severity estimation was weaker**, with AUROC scores of **90.3% (IJA), 84.4% (Low-Level RJA), and 84.2% (High-Level RJA)**.
- **IJA was the strongest predictor of ASD severity**, as children with severe ASD **failed to engage in triadic gaze**.
- **Grad-CAM analysis revealed that ASD children** failed to fixate on social cues, reinforcing the model's predictive validity.

---

### Implications:

- **Supports AI-based behavioral assessment as a potential ASD screening tool**.
- **Suggests joint attention as a reliable digital biomarker for ASD severity**.
- **Can facilitate scalable, non-invasive ASD detection methods for clinical and home settings**.

---

### 🔍 Related Work

- **Builds on prior research** using **eye-tracking for ASD detection** (Chang et al., 2021).
- **Improves on previous DL-based ASD classification** (Tariq et al., 2018) by integrating **explainable AI tools (Grad-CAM)**.
- **Aligns with studies** on **joint attention deficits as early ASD indicators** (Mundy et al., 2016).

---

### 📝 Observations

#### Strengths of the Study

✅ **Innovative use of joint attention tasks for deep learning-based ASD detection**.  
✅ **High classification accuracy (AUROC >99%)** suggests strong model performance.  
✅ **Explainability techniques (Grad-CAM) provide insights into AI decision-making**.  
✅ **Scalable and accessible method using standard video cameras** instead of **costly eye-tracking devices**.

---

#### Major Concerns and Challenges

⚠ **Possible Overfitting in Deep Learning Models**

- **Extremely high AUROC scores (>99%)** suggest **potential overfitting**.
- **No external validation dataset was used**, raising concerns about **generalizability**.

⚠ **Limited Sample Size and Homogeneity**

- **Only 95 participants**, which is small for a deep learning study.
- **Korean-only sample** lacks **cross-cultural validation**.

⚠ **No Direct Comparison with Gold-Standard Methods**

- **Would be more convincing if compared with infrared eye-tracking systems**.
- **No correlation analysis with traditional ASD diagnostic tools (e.g., ADOS-2 scores)**.

⚠ **Controlled Experimental Setup May Not Translate to Real-World Use**

- **Children’s behavior in structured lab tasks may differ from spontaneous interactions**.
- **Would benefit from testing in home environments or daycare centers**.

---

### Final Verdict: Promising but Needs External Validation

✅ **Demonstrates strong potential for AI-based ASD screening**.  
⚠ **Requires real-world validation, external testing, and comparison with clinical tools**.  
🚀 **Future work should explore deployment in diverse, everyday settings**.