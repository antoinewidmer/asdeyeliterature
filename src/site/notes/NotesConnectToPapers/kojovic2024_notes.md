---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/kojovic2024-notes/"}
---


# Unraveling the developmental dynamic of visual exploration of social interactions in autism

[[Literature_review/kojovic2024\|kojovic2024]]

## 📌 Summary

- **Objective**: The study investigates the **developmental dynamics of visual exploration** in autistic children while watching social interactions in a cartoon.
- **Participants**: **166 autistic children and 51 typically developing (TD) children**, aged **1.7–6.9 years**.
- **Method**: **Eye-tracking recordings** captured **moment-to-moment gaze patterns** as children watched **a cartoon featuring social interactions**.
- **Findings**:
    - **Autistic children displayed more dispersed and less consistent gaze patterns over time** compared to TD children.
    - **Greater divergence from TD gaze patterns was linked to lower adaptive functioning and communication skills in ASD**.
    - **ASD gaze divergence increased with age, while TD children showed increasing convergence in gaze patterns**.
    - **Autistic children fixated less on social interaction moments and more on visually prominent but non-social elements**.
    - **Stronger correlation between gaze consistency and later cognitive/adaptive outcomes** suggests **early visual exploration influences social development**.
- **Implications**: Highlights **importance of early interventions targeting social attention to mitigate developmental divergence**.

---

## 🔬 Methods

### **Study Design**

- **Longitudinal study** using **eye-tracking** to analyze gaze behavior in autistic and TD children.
- **Stimulus**: A **3-minute cartoon ("Trotro")** depicting social interactions.
- **Repeated assessments** tracked changes in gaze behavior over **one to two years**.
- **Custom-developed Proximity Index (PI)** quantified divergence from TD gaze patterns.

---

### **Participants**

| Characteristic       | Value |
|---------------------|--------------------------------|
| **Total Sample**    | 217 children (1.7–6.9 years old) |
| **Autism Group**    | 166 children |
| **Typically Developing (TD) Group** | 51 children |
| **Gender Distribution** | Only males (due to limited ASD females) |
| **Ethnicity**       | Not specified |
| **Inclusion Criteria** | ASD diagnosis confirmed via ADOS-2 |
| **Exclusion Criteria** | Severe cognitive impairment, poor eye-tracking quality (<50% valid data) |


### **Tasks for Participants**

| Task Name                | Purpose                                    | Format                        | Data Collected |
|--------------------------|--------------------------------|-------------------------|----------------------------|
| **Visual Exploration of Social Interaction (VET)** | Measure gaze behavior | 3-minute cartoon viewing | Gaze fixation, first fixation, gaze dispersion |
| **Proximity Index Calculation (PI)** | Quantify divergence from TD gaze | Comparison to TD gaze distribution | Frame-wise measure of gaze similarity |
| **Adaptive Behavior Assessments** | Assess functional outcomes | Parent questionnaires | Vineland Adaptive Behavior Scales (VABS-II) |
| **Autism Diagnostic Observation Schedule (ADOS-2)** | Confirm ASD diagnosis | Structured clinical assessment | Social affect, repetitive behaviors |


### **System Setup and Hardware**

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **Tobii TX300 Eye-Tracker** | Gaze tracking | 300 Hz sampling rate |
| **Tobii TXL60 (for some sessions)** | Alternative eye-tracking device | 60 Hz sampling rate |
| **Proximity Index Algorithm** | Compute gaze divergence | Custom MATLAB implementation |
| **Vineland Adaptive Behavior Scales (VABS-II)** | Measure adaptive skills | Parent-reported questionnaire |


### **Data Analysis**

#### **Collected Features in Dataset**

| Feature Category          | Feature Name              | Related Task | Measurement Description |
|--------------------------|----------------------|-------------|--------------------------|
| **Gaze Behavior**     | Fixation Percentage    | VET | Time spent looking at key stimuli |
| **Gaze Consistency** | Proximity Index (PI) | PI Task | Similarity to TD gaze patterns |
| **Gaze Dispersion** | Mean Pairwise Distance | VET | Spread of gaze across scene |
| **Adaptive Functioning** | VABS-II Scores | Parent Questionnaire | Socialization, daily living skills |
| **Autism Symptoms** | ADOS-2 Social Affect | ADOS-2 | Measure of social communication impairment |


## 📊 Results & Key Findings

### **Key Findings:**

- **ASD gaze patterns were more dispersed and less consistent than TD children**.
- **Gaze divergence increased with age in ASD, while TD children showed more coherent gaze patterns over time**.
- **Less divergence in gaze patterns was associated with better adaptive functioning and social communication**.
- **Autistic children fixated less on moments of social interaction but were drawn to low-level visual features (motion, brightness)**.
- **Children with lower gaze divergence at early stages had fewer autistic symptoms a year later**.

---

### **Implications for the Project**

- **Confirms that visual exploration differences emerge early in ASD**.
- **Supports the use of eye-tracking as an early biomarker for ASD severity and developmental trajectories**.
- **Suggests potential interventions targeting gaze patterns to improve social communication skills**.
- **Could inform AI-driven gaze tracking tools for ASD assessment and intervention**.

---

## 🔍 Related Work

- **Extends prior findings (Jones & Klin, 2013) that gaze differences emerge in infancy and persist over time**.
- **Supports research (Falck-Ytter et al., 2013) showing reduced social attention in ASD using eye-tracking**.
- **Aligns with studies (Avni et al., 2020) reporting greater gaze idiosyncrasy in ASD**.
- **Contrasts with studies (Wang et al., 2015) suggesting ASD gaze is dominated by low-level salience factors**.

---

## 📝 Observations

### **Strengths of the Study**

✅ **Large sample size for a longitudinal eye-tracking study** (166 ASD, 51 TD).  
✅ **Innovative Proximity Index (PI) method allows frame-by-frame comparison to TD gaze patterns**.  
✅ **Combines eye-tracking with standardized clinical measures (ADOS-2, VABS-II)**.  
✅ **First study to track gaze divergence over childhood and link it to future adaptive outcomes**.  
✅ **Uses a naturalistic, engaging stimulus (cartoon) rather than static images or artificial lab tasks**.

---

### **Major Concerns and Challenges**

⚠ **Limited Gender Representation**

- **Study only included males**, making findings less generalizable to autistic females.

⚠ **Potential Overinterpretation of Proximity Index**

- **Does lower divergence in gaze truly indicate better social function, or just more TD-like behavior?**
- **Need further validation linking PI scores to real-world social interactions**.

⚠ **No Direct Intervention Testing**

- **Study suggests early gaze training might improve ASD outcomes, but no intervention was tested**.
- **Would need trials testing targeted gaze interventions**.

⚠ **Stimulus Limitations**

- **A single cartoon (Trotro) was used**—unclear if results generalize to other types of social stimuli.
- **Would be stronger if gaze patterns were tested across multiple social interaction contexts**.

⚠ **Reliance on Parent-Reported Adaptive Skills**

- **VABS-II relies on subjective parental reporting**, which may **introduce bias**.
- **Direct behavioral measures of social adaptation would strengthen the study**.

---

### **Final Verdict: Strong but Needs Further Validation**

✅ **Provides compelling evidence of atypical gaze development in ASD**.  
✅ **Reinforces need for early gaze-based interventions**.  
⚠ **Requires replication with more diverse stimuli, gender balance, and real-world validation**.