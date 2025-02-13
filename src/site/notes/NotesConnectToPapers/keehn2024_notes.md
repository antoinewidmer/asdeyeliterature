---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/keehn2024-notes/"}
---


## 📌 Summary

- **Objective**: To evaluate whether a **battery of eye-tracking biomarkers** can reliably **differentiate young children with and without autism** in a primary care setting.
- **Methodology**:
    - **146 children** aged **14-48 months** referred for autism evaluation by **7 Early Autism Evaluation (EAE) hubs**.
    - **Eye-tracking biomarker battery** assessed social and non-social attention, attentional disengagement, pupillary light reflex, and fixation patterns.
    - **Reference standard diagnosis** was conducted using **ADOS-2, VABS-3, and MSEL**.
- **Findings**:
    - A **composite eye-tracking biomarker** had **77.5% sensitivity** and **77.3% specificity** for ASD.
    - **When combined with PCP diagnosis and certainty**, accuracy improved to **90.7% sensitivity** and **86.7% specificity**.
    - **Gaze-based markers provide additional value beyond PCP diagnosis alone**, suggesting **a role for AI-driven ASD screening tools**.


## 🔬 Methods

### Study Design

- **Prospective diagnostic study** conducted from **June 2019 to September 2022**.
- **Participants referred by PCPs** at EAE hubs for autism evaluation.
- **Blinded eye-tracking assessments** were performed within **16 weeks** of referral.
- **Reference standard diagnosis** determined by a **licensed psychologist using ADOS-2, VABS-3, and MSEL**.

---

### Participants

| Characteristic        | Value |
|----------------------|--------------------------------|
| **Total Sample**     | 146 children (14–48 months old) |
| **Autism Group**     | 102 children (70%) |
| **Non-Autism Group** | 44 children (30%) |
| **Mean Age**         | 2.6 years (SD = 0.6) |
| **Gender Distribution** | 71% male, 29% female |
| **Ethnicity**        | 14% Hispanic/Latine, 66% non-Latine White |
| **Recruitment Sites** | 7 Early Autism Evaluation (EAE) hubs |
| **Inclusion Criteria** | Referred by PCP for autism evaluation |
| **Exclusion Criteria** | Severe cognitive impairment, incomplete eye-tracking data |


**Criticism**:

- **No detailed breakdown of ASD severity levels** (e.g., mild vs. severe ASD).
- **Ethnic diversity is low**, limiting generalizability.

---

### Tasks for Participants

| Task Name                | Purpose                                    | Format                        | Data Collected |
|--------------------------|--------------------------------|-------------------------|----------------------------|
| **GeoPref Test** | Measure preference for social vs. non-social stimuli | Simultaneous social & geometric stimuli videos | % looking time at social vs. non-social |
| **Gap-Overlap Task** | Measure attentional disengagement | Visual stimulus shift | Reaction time (RT) to disengage gaze |
| **Pupillary Light Reflex (PLR) Test** | Assess autonomic nervous response | Light stimulus | PLR latency & amplitude |
| **Resting Fixation Task** | Measure oculomotor behavior | Passive screen viewing | Fixation duration, saccade amplitude |
| **Exploration Task** | Assess gaze exploration strategies | Dynamic visual scene | Fixation duration, gaze shifts |


**Criticism**:

- **Tasks focus only on eye movements**—no integration with **motor behavior or social interaction tasks**.
- **No naturalistic interaction** (e.g., caregiver-child gaze tracking).


### System Setup and Hardware

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **Tobii TX300 Eye-Tracker** | Gaze tracking | 300 Hz sampling rate |
| **MATLAB & JMP 13.0** | Data analysis | Statistical modeling |
| **ADOS-2, VABS-3, MSEL** | Reference standard autism diagnosis | Standardized clinical assessments |
| **Survey Tool** | Caregiver-reported demographic data | Electronic questionnaire |




### Data Analysis

#### Collected Features in Dataset

| Feature Category         | Feature Name              | Related Task | Measurement Description |
|--------------------------|----------------------|-------------|--------------------------|
| **Gaze Behavior**       | Social vs. Non-Social Fixation | GeoPref Test | % looking time at social vs. non-social stimuli |
| **Attention Disengagement** | Gap-Overlap RT | Gap-Overlap Task | Reaction time to shift gaze |
| **Pupillary Response**  | PLR Latency & Amplitude | PLR Test | Time & size of pupil dilation |
| **Fixation Behavior**   | Resting Fixation Duration | Resting Fixation Task | Average fixation duration (ms) |
| **Gaze Exploration**    | Gaze Shifts & Fixation Time | Exploration Task | Time spent scanning visual scenes |


---

## 📊 **Results & Key Findings**

### Key Findings:

- **Eye-tracking biomarkers had 77.5% sensitivity and 77.3% specificity** in differentiating ASD from non-ASD.
- **PCP diagnosis alone had lower accuracy than eye-tracking biomarkers**.
- **Combining PCP diagnosis, diagnostic certainty, and biomarkers improved accuracy to 90.7% sensitivity and 86.7% specificity**.
- **Children with lower social gaze and increased nonsocial preference had lower adaptive functioning scores**.
- **Higher fixation duration was associated with ASD, while shorter pupillary light reflex latency predicted ASD**.

### Implications for the Project

- **Supports the feasibility of using eye-tracking for scalable ASD screening in primary care**.
- **Suggests that eye-tracking can enhance clinician judgment, reducing diagnostic uncertainty**.
- **Findings could inform AI-driven gaze analysis tools for ASD stratification**.



## 🔍 Related Work

- **Builds on previous work (Pierce et al., 2016) on social vs. nonsocial gaze differences in ASD**.
- **Aligns with studies (Jones & Klin, 2013) that show gaze patterns are predictive of ASD risk**.
- **Expands prior research (Nyström et al., 2018) on pupillary light reflex differences in ASD**.



## 📝 Observations

### Strengths of the Study

✅ **Large community-referred sample (146 children) improves real-world relevance**.  
✅ **Integration of eye-tracking biomarkers with clinical diagnosis enhances accuracy**.  
✅ **First study to test eye-tracking ASD biomarkers in a primary care setting**.  
✅ **Use of a multimodal approach (gaze, pupillary response, oculomotor behavior)**.


### Major Concerns and Challenges

⚠ **Limited Generalizability**

- **Sample is predominantly male (71%) and non-Hispanic White (66%)**.
- **Lack of diversity raises concerns about applicability to broader populations**.

⚠ **Lack of Longitudinal Validation**

- **No follow-up data on whether eye-tracking biomarkers predict long-term ASD outcomes**.

⚠ **Potential Overfitting in Classification Models**

- **Reported AUC values are high (0.90+), but generalization to unseen data is unclear**.

⚠ **Reliance on Static Lab-Based Stimuli**

- **No real-world social interactions tested**—could the biomarkers work in a natural setting?



### Final Verdict: Strong but Needs Further Validation

✅ **Promising approach for integrating AI-driven biomarkers into primary care ASD screening**.  
⚠ **Requires external validation, increased demographic diversity, and real-world deployment studies**.