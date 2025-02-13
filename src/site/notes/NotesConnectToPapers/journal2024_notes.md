---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/journal2024-notes/"}
---



## 📌 Summary

- **Objective**: The study examines **variability in early socio-communicative skills** in young autistic children and how these skills influence later **cognitive and adaptive development**.
- **Participants**: **171 children (103 with ASD, 68 typically developing [TD])** aged **18–60 months** were assessed longitudinally.
- **Method**: Used **Early Social Communication Scales (ESCS)** to measure preverbal communication and **Principal Component Analysis (PCA)** to identify key behavioral patterns.
- **Findings**:
    - **Autistic children had consistently lower preverbal communication skills** than TD children, but some skills improved by age 5.
    - **Two major components of social communication** emerged:
        1. **Object-directed behaviors** (e.g., pointing, reaching).
        2. **Social interaction-directed behaviors** (e.g., turn-taking, social gaze).
    - **Cluster analysis identified three ASD subgroups**, each with different communication profiles and developmental trajectories.
    - Children with **strong early social interaction skills had better cognitive and adaptive outcomes** later.
- **Implications**: Findings **support early intervention tailored to specific preverbal communication profiles** in ASD.

---

## 🔬 Methods

### **Study Design**

- **Longitudinal study** tracking **preverbal social communication skills** in ASD and TD children from **18 to 60 months**.
- **Multiple assessments (2–7 per participant)** over time.
- **Cluster analysis** used to identify subgroups based on communication patterns.

---

### Participants

| Characteristic       | Value |
|---------------------|--------------------------------|
| **Total Sample**    | 171 children (18–60 months old) |
| **Autism Group**    | 103 children (18 females) |
| **Typically Developing (TD) Group** | 68 children (28 females) |
| **Number of Timepoints** | 596 (avg. 3.5 per participant) |
| **Parents’ Education** | 84% university, 13% high school, 3% primary |
| **Inclusion Criteria** | Valid ESCS assessment before age 3 |
| **Exclusion Criteria** | Severe cognitive impairment preventing participation |


### Tasks for Participants

| Task Name                | Purpose                                    | Format                        | Data Collected |
|--------------------------|--------------------------------|-------------------------|----------------------------|
| **Early Social Communication Scales (ESCS)** | Assess preverbal social communication skills | Structured play-based tasks with examiner | Gaze, pointing, turn-taking, requests |
| **ADOS-2 Assessment** | Confirm ASD diagnosis | Clinical observation | Social interaction, repetitive behaviors |
| **Mullen Scales of Early Learning (MSEL)** | Measure cognitive ability | Standardized test | Expressive/receptive language, visual perception |
| **Vineland Adaptive Behavior Scales (VABS-II)** | Measure adaptive functioning | Parent interview | Socialization, communication, motor skills |

### System Setup and Hardware

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **Video Recording System** | Record ESCS sessions | High-definition camera |
| **IBM SPSS Statistics** | Data Analysis | Used for PCA and cluster analysis |
| **MATLAB (R2019b)** | Mixed-effects modeling | Tracks longitudinal changes |
| **GraphPad PRISM** | Data Visualization | Graph generation for PCA results |


### Data Analysis

#### Collected Features in Dataset

| Feature Category          | Feature Name              | Related Task | Measurement Description |
|--------------------------|----------------------|-------------|--------------------------|
| **Gaze Behavior**     | Joint Attention (IJA, RJA) | ESCS | Time spent looking at an object/social partner |
| **Gestural Communication** | Pointing, reaching | ESCS | Frequency of gestures used to communicate |
| **Turn-Taking Skills** | Social Interaction Responses | ESCS | Ability to engage in back-and-forth interaction |
| **Cognitive Ability** | MSEL Score | MSEL | General cognitive functioning |
| **Adaptive Functioning** | VABS Composite Score | VABS-II | Overall daily living and social skills |


## 📊 Results & Key Findings

### Key Findings:

- **TD children consistently outperformed ASD children in preverbal communication skills**, but both groups showed improvement over time.
- **Two major social communication factors were identified**:
    1. **Object-directed behaviors** (pointing, reaching, responding to requests).
    2. **Social interaction behaviors** (turn-taking, facial engagement).
- **Cluster analysis revealed three ASD subgroups**:
    - **Cluster A**: Strong object-directed skills, weak social engagement.
    - **Cluster B**: Balanced mix of object and social interaction skills.
    - **Cluster C**: Weak in both object and social engagement (poorest developmental outcomes).
- **Children in Cluster C had the worst cognitive and adaptive functioning trajectories**.
- **Initiation of behavioral requests (pointing, reaching) was the strongest predictor of later language and social development**.

---

### Implications for the Project

- **Supports personalized intervention strategies based on preverbal communication profiles**.
- **Highlights the role of nonverbal communication as a predictor of later cognitive and social outcomes**.
- **Suggests that object-directed skills (pointing, reaching) should be a focus in early intervention**.
- **Findings could inform AI-driven assessment tools for early ASD screening**.

---

## 🔍 Related Work

- **Extends previous findings (Chiang et al., 2008) that ASD children struggle with high-level joint attention behaviors**.
- **Supports Mundy et al. (2007), who found that early social communication deficits persist into preschool years**.
- **Contrasts with some studies (Bottema-Beutel, 2016), which argue that response to joint attention is more important than initiation**.
- **Provides new evidence linking social engagement skills with long-term cognitive outcomes**.

---

## 📝 Observations

### Strengths of the Study

✅ **Large longitudinal dataset (171 children, 596 timepoints), allowing for robust developmental analysis**.  
✅ **Innovative use of PCA and cluster analysis to identify ASD subgroups**.  
✅ **Includes multiple standardized assessments (ESCS, ADOS-2, MSEL, VABS-II)**.  
✅ **Findings provide practical guidance for tailoring early intervention programs**.  
✅ **Explores both object-directed and social interaction-directed communication strategies**.

---

### Major Concerns and Challenges

⚠ **Potential Overinterpretation of Clusters**

- **Do these subgroups represent meaningful clinical differences, or are they just statistical artifacts?**
- **Need validation in an independent dataset** before using these subgroups for clinical decision-making.

⚠ **Limited Generalizability**

- **Participants were recruited from a single research center** → Findings may not generalize to more diverse populations.
- **Cultural and linguistic background differences** were not analyzed.

⚠ **Lack of Direct Real-World Interaction Measurements**

- Study **relies on structured lab-based tasks** rather than **real-world social interactions**.
- **Would be stronger with parent-reported naturalistic observations**.

⚠ **Possible Intervention Bias**

- Some children **may have received early intervention**, influencing their developmental trajectories.
- **No information on intervention history was controlled for in the analysis**.

⚠ **No Neurobiological Correlates**

- Would benefit from **neuroimaging or physiological measures** to link behavioral findings to brain function.