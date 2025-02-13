---
{"dg-publish":true,"permalink":"/literature-review/tafasca2023a/","title":"The AI4Autism Project A Multimodal and Interdisciplinary Approach to Autism Diagnosis and Stratification","tags":["ASD","EyeTracking"]}
---


## The AI4Autism Project: A Multimodal and Interdisciplinary Approach to Autism Diagnosis and Stratification

> [!Cite]
> Tafasca, S., Gupta, A., Kojovic, N., Gelsomini, M., Maillart, T., Papandrea, M., Schaer, M., & Odobez, J.-M. (2023). The AI4Autism Project: A Multimodal and Interdisciplinary Approach to Autism Diagnosis and Stratification. _Companion Publication of the 25th International Conference on Multimodal Interaction_, 414–425. [https://doi.org/10.1145/3610661.3616239](https://doi.org/10.1145/3610661.3616239)


>[!md]
> **Year**:: 2023   
> **Citekey**:: tafasca2023a  
> **itemType**:: conferencePaper  
> **Publisher**:: Association for Computing Machinery  
> **Location**:: New York, NY, USA   
> **Pages**:: 414–425  
> **DOI**:: 10.1145/3610661.3616239  
> **ISBN**:: 979-8-4007-0321-8    

> [!LINK] 
> [2023_Tafasca et al._The AI4Autism Project A Multimodal and Interdisciplinary Approach to Autism Diagnosis and Stratific.pdf](zotero://select/library/items/TMN42AAH)

> [!Abstract]
>
> Nowadays, 1 in 36 children is diagnosed with autism spectrum disorder (ASD) according to the Centers for Disease Control and Prevention (CDC) [52], which makes this condition one of the most prevalent neurodevelopmental disorders. For children on the autism spectrum who face substantial developmental delays, the trajectory of their cognitive growth can be markedly improved by interventions if the condition is identified early. Therefore, there is a critical need for more scalable screening and diagnostic tools, as well as the need to improve phenotyping to refine estimates of ASD symptoms in children. Here, we introduce AI4Autism: a 4-year project funded by the Swiss National Science Foundation, which aims to address the needs outlined above. In this project, we examine the potential of digital sensing to provide automated measures of the extended autism phenotype. This is accomplished using multimodal techniques based on computer vision and Internet of Things sensing, for the purpose of stratifying autism subtypes in ways that would allow for precision medicine. We present an overview of our main results so far, introducing datasets and annotations that we intend to make publicly available, as well as methods and algorithms for analyzing children’s behaviors and producing an ASD diagnosis.
>.
> 


## Notes

| File                                                               | file.name          |
| ------------------------------------------------------------------ | ------------------ |
| [[NotesConnectToPapers/tafasca2023a_notes\|tafasca2023a_notes]] | tafasca2023a_notes |

{ .block-language-dataview}


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/notes-connect-to-papers/tafasca2023a-notes/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




# The AI4Autism Project: A Multimodal and Interdisciplinary Approach to Autism Diagnosis and Stratification

[[Literature_review/tafasca2023a\|tafasca2023a]]

## Summary

- **Objective**: The study presents AI4Autism, a **Swiss National Science Foundation-funded** project aiming to improve **ASD diagnosis and stratification** using **multimodal AI techniques**.
- **Methodology**: Uses **computer vision, Internet of Things (IoT) sensors, and machine learning models** to capture **motor, gaze, and social behaviors** in autistic children.
- **Datasets**:
    - **UniGe ADOS Dataset** – video recordings of ADOS-2 autism diagnostic sessions.
    - **Geneva Pose for Autism Dataset** – extracted **skeletal pose data** to assess body motion.
    - **ChildPlay Dataset** – publicly available videos capturing children’s gaze and play behaviors.
- **Findings**:
    - **Automated gaze tracking and movement analysis** can predict ASD with **81% accuracy**.
    - **Gaze and gesture coordination deficits** are strongly correlated with ASD severity.
    - **IoT-based play behavior analysis** can provide objective ASD markers.



## Aims of the AI4Autism Project
### Better Stratification of ASD Subtypes

- Improve the classification of autism subtypes using **fine-grained behavioral quantification**.
- Move beyond traditional **ADOS-2-based categorization** to enable **precision medicine**.
- Identify **previously undetected ASD subtypes** that may have **different prognoses or treatment responses**.

### Building a Large-Scale Curated Dataset

- Create an extensive dataset with **manual annotations of non-verbal behaviors** (e.g., joint attention, gestures, eye contact).
- Use ADOS coding protocols as a basis for **training AI-driven ASD profiling tools**.
- Develop **publicly available datasets** to promote **open research in ASD detection**.

### Designing AI Tools for Automated ASD Identification

- Develop **computer vision and IoT-based AI models** for **automated ASD screening**.
- Train **deep learning algorithms** to analyze:
    - **Motor-Gaze Coordination**
    - **Free-Play Activities**
    - **Social Communication Patterns**
- Build interpretable AI models to **reduce clinician workload** and enable **scalable digital phenotyping**.

### Validation and Generalization in Real-World Settings

- Transition AI models from **controlled clinical environments** to **daycare centers and outpatient clinics**.
- Ensure models remain **robust under different conditions** (e.g., varying lighting, camera angles, and diverse child populations).
- Address potential **co-occurring conditions (ADHD, language delay, etc.)** that may affect ASD classification.

## 🔬 **Methods**

### **Study Design**

- **AI-driven behavioral assessment for ASD diagnosis**.
- **Combines video-based pose estimation, gaze tracking, and IoT-based movement analysis**.
- **Designed for large-scale deployment in clinical and daycare settings**.

---

### **Participants**


| Characteristic        | Value |
|----------------------|--------------------------------|
| **Total Sample**     | 450+ children (ASD + TD) |
| **Autism Group**     | Not specified explicitly |
| **Typically Developing (TD) Group** | Not specified explicitly |
| **Age Range**        | 1–6 years |
| **Gender Distribution** | Not specified |
| **Dataset Sources**  | Geneva Autism Cohort |
| **Inclusion Criteria** | ASD diagnosis confirmed with ADOS-2 |
| **Exclusion Criteria** | Severe cognitive impairment, poor eye-tracking data |


---

### **Tasks for Participants**

| Task Name                | Purpose                                    | Format                        | Data Collected |
|--------------------------|--------------------------------|-------------------------|----------------------------|
| **ADOS-2 Diagnostic Assessment** | Standardized ASD evaluation | Structured clinical session | Social interaction, repetitive behaviors |
| **Visual Exploration (Gaze Tracking)** | Measure gaze behavior | Video of social interactions | Gaze fixation, gaze shifts, attention patterns |
| **Body Motion Tracking** | Assess motor behavior | Pose estimation from videos | Gesture coordination, movement patterns |
| **IoT-based Play Analysis** | Evaluate play behaviors | Smart toys with motion sensors | Toy interaction patterns, movement data |

### **System Setup and Hardware**

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **Tobii TX300 Eye-Tracker** | Gaze tracking | 300 Hz sampling rate |
| **OpenPose (Pose Estimation)** | Body motion analysis | Extracts 2D skeletal data |
| **IoT Smart Toys (AutoPlay Kit)** | Play behavior assessment | Embedded IMU + UWB localization sensors |
| **BORIS Annotation Tool** | Video coding for ADOS sessions | Event-logging software |
| **Neural Networks (VGG16, LSTM)** | ASD classification | Extracts features from video and pose data |


---

### **Data Analysis**

#### **Collected Features in Dataset**

| Feature Category         | Feature Name              | Related Task | Measurement Description |
|--------------------------|----------------------|-------------|--------------------------|
| **Gaze Behavior**       | Fixation Percentage  | Visual Exploration Task | Time spent looking at key stimuli |
| **Motor Coordination**  | Gesture Tracking     | Body Motion Task | Frequency and quality of gestures |
| **Social Interaction**  | Eye Contact Ratio    | Visual Exploration Task | Proportion of mutual gaze events |
| **Play Behavior**       | Object Interaction   | IoT Play Task | Frequency and type of toy interactions |


---

## 📊 **Results & Key Findings**

### **Key Findings:**

- **AI models reached 81% accuracy in ASD prediction**, with high correlation between **gaze-motor coordination and ASD severity**.
- **Early differences in gaze and gesture use** predict later ASD symptoms.
- **IoT-based movement tracking provides objective behavioral markers** for ASD.
- **Automated stratification suggests potential new ASD subtypes**.

### **Implications:**

- **Supports digital phenotyping for precision ASD diagnosis**.
- **Suggests gaze-motor coordination as a key diagnostic target**.
- **Could enable large-scale ASD screening in daycare centers**.

---

## 🔍 **Related Work**

- **Extends work on digital ASD screening** (Dawson et al., 2018; Klin et al., 2009).
- **Aligns with prior research using OpenPose for ASD assessment** (Kojovic et al., 2021).
- **Contrasts with static image-based gaze tracking studies** by focusing on **dynamic interactions**.

---

## 📝 **Observations**

### **Strengths of the Study**

✅ **Multimodal approach (gaze, motion, play behavior) enhances ASD profiling**.  
✅ **Large dataset (450+ children) surpasses many previous ASD studies**.  
✅ **Stratification method could improve targeted interventions**.  
✅ **IoT play tracking introduces a novel, scalable ASD assessment method**.  
✅ **Open dataset initiative promotes transparency and reproducibility**.

---

### **Major Concerns and Challenges**

⚠ **Potential Overfitting in Neural Network Models**

- Reported **81% accuracy**, but **without external validation**.
- **No discussion of dataset biases or class imbalance correction**.

⚠ **Lack of Longitudinal Validation**

- **No follow-up to confirm AI-detected ASD subtypes correspond to real developmental differences**.
- Long-term validation is **critical before clinical deployment**.

⚠ **Interpretability Issues in AI Models**

- Direct **end-to-end ASD classification lacks explainability** – how do specific behaviors influence predictions?
- **More transparent feature importance analysis needed**.

⚠ **Limited Consideration of Real-World Variability**

- Model trained on **standardized ADOS sessions**, but **how does it perform in everyday environments (e.g., home, school)?**
- **No assessment of cultural or socioeconomic biases in ASD detection**.

⚠ **Ethical and Privacy Considerations**

- **Tracking children’s gaze, motor, and play behaviors raises privacy risks**.
- **Lack of discussion on data security and informed consent processes**.

---

### **Final Verdict: Strong but Needs Real-World Validation**

✅ **The study presents a promising multimodal AI approach to ASD diagnosis and stratification**.  
⚠ **Before clinical adoption, external validation, longitudinal tracking, and interpretability improvements are required**.  
🚀 **Future work should focus on deploying models in diverse, uncontrolled environments**.



</div></div>


## Figures

**Imported: 2025-02-12**

> ![Images/tafasca2023a/image-2-x57-y595.png](/img/user/Images/tafasca2023a/image-2-x57-y595.png)

> ![Images/tafasca2023a/image-4-x55-y406.png](/img/user/Images/tafasca2023a/image-4-x55-y406.png)

> ![Images/tafasca2023a/image-5-x312-y438.png](/img/user/Images/tafasca2023a/image-5-x312-y438.png)

> ![Images/tafasca2023a/image-6-x312-y401.png](/img/user/Images/tafasca2023a/image-6-x312-y401.png)

> ![Images/tafasca2023a/image-7-x52-y454.png](/img/user/Images/tafasca2023a/image-7-x52-y454.png)

> ![Images/tafasca2023a/image-7-x52-y349.png](/img/user/Images/tafasca2023a/image-7-x52-y349.png)

> ![Images/tafasca2023a/image-7-x317-y570.png](/img/user/Images/tafasca2023a/image-7-x317-y570.png)

> ![Images/tafasca2023a/image-7-x316-y479.png](/img/user/Images/tafasca2023a/image-7-x316-y479.png)

> ![Images/tafasca2023a/image-8-x53-y580.png](/img/user/Images/tafasca2023a/image-8-x53-y580.png)