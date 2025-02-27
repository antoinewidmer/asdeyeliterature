---
{"dg-publish":true,"permalink":"/literature-review/megerian2022a/","title":"Evaluation of an artificial intelligence-based medical device for diagnosis of autism spectrum disorder","tags":["learning","Autism","Diagnosis","Paediatric"]}
---


## Evaluation of an artificial intelligence-based medical device for diagnosis of autism spectrum disorder

> [!Cite]
> Megerian, J. T., Dey, S., Melmed, R. D., Coury, D. L., Lerner, M., Nicholls, C. J., Sohl, K., Rouhbakhsh, R., Narasimhan, A., Romain, J., Golla, S., Shareef, S., Ostrovsky, A., Shannon, J., Kraft, C., Liu-Mayo, S., Abbas, H., Gal-Szabo, D. E., Wall, D. P., & Taraman, S. (2022). Evaluation of an artificial intelligence-based medical device for diagnosis of autism spectrum disorder. _Npj Digital Medicine_, _5_(1), 1–11. [https://doi.org/10.1038/s41746-022-00598-6](https://doi.org/10.1038/s41746-022-00598-6)


>[!md]
> **Year**:: 2022   
> **Citekey**:: megerian2022a  
> **itemType**:: journalArticle  
> **Journal**:: *npj Digital Medicine*  
> **Volume**:: 5  
> **Issue**:: 1   
> **Pages**:: 1-11  
> **DOI**:: 10.1038/s41746-022-00598-6    

> [!LINK] 
> [2022_Megerian et al._Evaluation of an artificial intelligence-based medical device for diagnosis of autism spectrum disor.pdf](zotero://select/library/items/8I7C3RFL)

> [!Abstract]
>
> Autism spectrum disorder (ASD) can be reliably diagnosed at 18 months, yet significant diagnostic delays persist in the United States. This double-blinded, multi-site, prospective, active comparator cohort study tested the accuracy of an artificial intelligence-based Software as a Medical Device designed to aid primary care healthcare providers (HCPs) in diagnosing ASD. The Device combines behavioral features from three distinct inputs (a caregiver questionnaire, analysis of two short home videos, and an HCP questionnaire) in a gradient boosted decision tree machine learning algorithm to produce either an ASD positive, ASD negative, or indeterminate output. This study compared Device outputs to diagnostic agreement by two or more independent specialists in a cohort of 18–72-month-olds with developmental delay concerns (425 study completers, 36% female, 29% ASD prevalence). Device output PPV for all study completers was 80.8% (95% confidence intervals (CI), 70.3%–88.8%) and NPV was 98.3% (90.6%–100%). For the 31.8% of participants who received a determinate output (ASD positive or negative) Device sensitivity was 98.4% (91.6%–100%) and specificity was 78.9% (67.6%–87.7%). The Device’s indeterminate output acts as a risk control measure when inputs are insufficiently granular to make a determinate recommendation with confidence. If this risk control measure were removed, the sensitivity for all study completers would fall to 51.6% (63/122) (95% CI 42.4%, 60.8%), and specificity would fall to 18.5% (56/303) (95% CI 14.3%, 23.3%). Among participants for whom the Device abstained from providing a result, specialists identified that 91% had one or more complex neurodevelopmental disorders. No significant differences in Device performance were found across participants’ sex, race/ethnicity, income, or education level. For nearly a third of this primary care sample, the Device enabled timely diagnostic evaluation with a high degree of accuracy. The Device shows promise to significantly increase the number of children able to be diagnosed with ASD in a primary care setting, potentially facilitating earlier intervention and more efficient use of specialist resources.
>.
> 
### Summary

This study evaluates an **AI-based Software as a Medical Device (SaMD)** designed to assist **primary care healthcare providers (HCPs)** in diagnosing **autism spectrum disorder (ASD)** in children aged **18–72 months**. The device integrates **caregiver questionnaires, home video analysis, and HCP assessments** into a **gradient-boosted decision tree algorithm** to classify children as **ASD positive, ASD negative, or indeterminate**. The study, conducted across **14 sites in six U.S. states**, included **425 children** with developmental concerns. The device demonstrated **high sensitivity (98.4%) and specificity (78.9%)** for children receiving a determinate output. Importantly, no significant performance differences were observed across **sex, race/ethnicity, income, or education level**. This AI-based tool holds promise for **reducing diagnostic delays** and expanding **ASD diagnosis capacity** in **primary care settings**.

---

## 🔬 Methods

### **Study Design**

- **Type**: **Double-blinded, multi-site, prospective cohort study** with an **active comparator**.
- **Setting**: **14 sites in six U.S. states**, including **pediatric clinics** and **developmental centers**.
- **Objective**: Assess the **accuracy and safety** of the AI-based device in diagnosing ASD compared to expert clinical evaluations.
- **Diagnostic Reference Standard**: **DSM-5 ASD criteria** confirmed by **at least two blinded specialist clinicians**.

---

### **Participants**

- **Total Enrolled**: **711 children** aged **18–72 months**.
- **Study Completers**: **425 children** (due to **COVID-19 disruptions**, some dropped out).
- **Demographics**:
    - **Sex**: 63.8% male, 36.2% female.
    - **Race/Ethnicity**: 53.9% White, 13.2% Black, 11.5% Hispanic/Latino, 13.4% Multiracial, others <5%.
    - **Parental Education**: 32% Bachelor's, 18.4% Graduate degree.
    - **Income Levels**: Balanced across economic brackets.

**Clinical Diagnosis Breakdown**:

- **28.7% ASD-positive**.
- **61.9% Non-ASD developmental conditions**.
- **9.4% Neurotypical**.

---

### **Tasks for Participants**

1. **Caregiver Questionnaire**:
    
    - Parents answered a **mobile-app-based** questionnaire (~5 minutes).
    - Questions targeted **social interaction, communication, repetitive behaviors, and sensory responses**.
2. **Home Video Submissions**:
    
    - Parents uploaded **two short videos (1.5–5 minutes each)** of their child **in natural settings**.
    - Trained **video analysts** assessed social cues, play behavior, and interactions.
3. **HCP Clinical Assessment**:
    
    - Pediatricians or family physicians completed a **13–15 item questionnaire** (~10 minutes).
    - Evaluated **motor skills, verbal/non-verbal communication, and repetitive behaviors**.

---

### **System Setup and Hardware**

|**Component**|**Description**|
|---|---|
|**Device Type**|**AI-based Software as a Medical Device (SaMD)**|
|**Input 1**|**Caregiver questionnaire** (mobile app)|
|**Input 2**|**Two home video recordings** (1.5–5 min each)|
|**Input 3**|**HCP clinical questionnaire**|
|**Algorithm**|**Gradient-boosted decision tree machine learning model**|
|**Outputs**|**ASD positive, ASD negative, or indeterminate**|
|**Processing Time**|~**11 minutes for video analysis**; **instant AI-generated diagnosis**|

---

### **Data Analysis**

- **Performance Metrics**:
    - **Positive Predictive Value (PPV):** **80.8%**.
    - **Negative Predictive Value (NPV):** **98.3%**.
    - **Sensitivity (for determinate cases):** **98.4%**.
    - **Specificity (for determinate cases):** **78.9%**.
- **Statistical Analysis**:
    - **Clopper-Pearson confidence intervals** for performance measures.
    - **Boschloo’s Exact Test** for subgroup comparisons (age, sex, race).
    - **Cross-validation** and **hyperparameter tuning** ensured model robustness.

#### Home Video Recordings in the Study

The **home video recordings** were a **key input** for the AI-based autism diagnosis device, allowing the system to analyze **naturalistic child behavior**. Below are detailed aspects of the **video collection, analysis, and processing**:

---

#### Purpose of Home Video Recordings

- Capture **natural, unstructured behaviors** in a **familiar environment**.
- Reduce **clinic-based bias**, where children might not exhibit typical behavior.
- Enable **remote assessment**, making the device adaptable to **telemedicine**.
- Support **automated behavioral feature extraction** using **trained analysts and AI**.

---

#### Video Recording Guidelines for Caregivers

Caregivers were required to **record and submit two short home videos** via the **mobile app**.

|**Parameter**|**Specification**|
|---|---|
|**Number of Videos**|**Two (2)**|
|**Duration**|**1 minute 30 seconds – 5 minutes** each|
|**Setting**|Natural home environment (e.g., living room, play area)|
|**Camera Angle**|Ensure **full view of the child’s face and hands**|
|**Lighting**|Sufficient brightness to capture facial expressions|
|**Audio**|Ensure clear **verbal responses and background speech**|

---

#### Types of Behavioral Interactions Captured

The videos were required to include **natural social interactions**, such as:

| **Category**                     | **Behavioral Indicators** |
|----------------------------------|------------------------------------------------|
| **👀 Social Engagement**         | ✔️ Eye contact with parents or siblings  |
|                                  | ✔️ Response to being called by name  |
|                                  | ✔️ Joint attention (e.g., pointing, shared gaze)  |
| **🗣️ Communication & Language**  | ✔️ Babbling, verbal responses, or gesturing  |
|                                  | ✔️ Turn-taking in conversations or play  |
| **🤖 Repetitive Behaviors & Motor Skills** | ✔️ Hand-flapping, rocking, spinning  |
|                                  | ✔️ Fine motor interactions with objects/toys  |
| **🎮 Play Behavior**             | ✔️ Pretend play, imaginative interactions  |
|                                  | ✔️ Object exploration and manipulation  |

---

### **4️⃣ Video Processing & Feature Extraction**

The **submitted videos** were analyzed by **trained human analysts** and an **AI-powered system**.

#### **Step 1: Human Video Analysts**

👥 **Certified specialists** (e.g., psychologists, therapists) reviewed the videos and provided **structured behavior scores**.

##### **👀 Social Engagement Scoring Criteria**

|**Behavior**|**Scoring Criteria**|
|---|---|
|**Eye Contact**|✅ Frequent eye contact (3+ instances) = **High Score**  <br>⚠️ Occasional eye contact (1–2 instances) = **Moderate Score**  <br>❌ No eye contact = **Low Score**|
|**Response to Name**|✅ Turns to caregiver within **2 seconds** = **High Score**  <br>⚠️ Turns **after multiple attempts** (>3 sec) = **Moderate Score**  <br>❌ No response = **Low Score**|
|**Joint Attention**|✅ Points/follows gaze at least **twice** = **High Score**  <br>⚠️ Limited response (once) = **Moderate Score**  <br>❌ No pointing or gaze-following = **Low Score**|

---

##### **🗣️ Communication & Language Scoring Criteria**

|**Behavior**|**Scoring Criteria**|
|---|---|
|**Verbalizations**|✅ Frequent verbal responses (babbling, words) = **High Score**  <br>⚠️ Occasional verbalizations = **Moderate Score**  <br>❌ No verbal output = **Low Score**|
|**Turn-Taking in Play**|✅ Engages in back-and-forth play **spontaneously** = **High Score**  <br>⚠️ Needs prompting to interact = **Moderate Score**  <br>❌ Does not participate = **Low Score**|

---

##### **🤖 Repetitive Behaviors & Motor Skills Scoring Criteria**

|**Behavior**|**Scoring Criteria**|
|---|---|
|**Hand-Flapping/Rocking**|✅ Persistent repetitive movements = **High Score**  <br>⚠️ Occasional or mild movements = **Moderate Score**  <br>❌ No repetitive behaviors = **Low Score**|
|**Fine Motor Interaction**|✅ Manipulates objects purposefully = **High Score**  <br>⚠️ Some engagement but limited coordination = **Moderate Score**  <br>❌ No fine motor interaction = **Low Score**|

---

##### **🎮 Play Behavior Scoring Criteria**

|**Behavior**|**Scoring Criteria**|
|---|---|
|**Pretend Play**|✅ Engages in **imaginative play** (e.g., pretending to feed a doll) = **High Score**  <br>⚠️ Some functional play but limited imagination = **Moderate Score**  <br>❌ No pretend play = **Low Score**|
|**Object Exploration**|✅ Examines/manipulates toys purposefully = **High Score**  <br>⚠️ Limited engagement = **Moderate Score**  <br>❌ Avoids toys, fixates on one object = **Low Score**|

---

##### **🔍 Additional Scoring Factors**

✔ **Behavioral Variability** – Analysts considered **consistency vs. sporadic** behavior.  
✔ **Video Clarity** – Poor lighting, framing, or background noise **could affect scoring**.  
✔ **Engagement Levels** – **Passive (low score) vs. interactive (high score)** behaviors.

---

##### **🚀 Summary**

- **Higher scores** indicate **strong social engagement, communication, and play interactions**.
- **Lower scores** highlight **potential ASD markers**, such as **lack of response, poor eye contact, and repetitive behaviors**.
- The AI system **cross-validated human scoring** to enhance **accuracy and objectivity**.

#### **Step 2: AI-Based Feature Extraction**

🤖 The **AI model** processed videos using **computer vision and machine learning** to extract **predictive features**:

|**Feature Type**|**Extracted AI Features**|
|---|---|
|**Facial expressions**|Microexpressions, smiling frequency|
|**Gaze behavior**|Attention to social vs. non-social stimuli|
|**Head movements**|Orientation shifts, response latency|
|**Hand movements**|Repetitive motions, fine motor control|

---

##### Reliability & Inter-Rater Consistency

- **Analysts underwent standardized training** to ensure **consistent scoring**.
- **Preliminary validation showed high agreement** between **human analysts and AI models**.
- **Videos flagged as low quality** (poor lighting, obscured face) were **excluded** from analysis.

---

##### Challenges & Limitations

⚠️ **Variability in Video Quality** – Some submissions had **poor lighting or camera angles**, affecting AI analysis.  
⚠️ **Parental Influence** – Parents may have **unknowingly coached children**, altering natural behavior.  
⚠️ **Home Environment Differences** – Background noise, siblings, or distractions could impact behavioral expressions.  
⚠️ **Limited Spontaneous Interaction** – Some children **did not engage** much during filming, limiting data collection.

## 📊 Results & Key Findings

### **1. Device Performance for ASD Diagnosis**

|**Metric**|**Value**|
|---|---|
|**PPV**|**80.8%**|
|**NPV**|**98.3%**|
|**Sensitivity**|**98.4%**|
|**Specificity**|**78.9%**|

- **High accuracy** in determining ASD-positive children.
- **No significant bias** across **sex, race, ethnicity, or income level**.
- **Indeterminate outputs (68.2%)** were **effective in filtering complex cases** (91% had other neurodevelopmental disorders).

---

### **2. Subgroup Performance (Age, Sex, Race)**

|**Subgroup**|**AUC (%)**|**Sensitivity**|**Specificity**|
|---|---|---|---|
|**Girls**|**89.1**|**90.9%**|**83.5%**|
|**Boys**|**89.6**|**86.8%**|**77.8%**|
|**White**|**86.9**|**82.6%**|**82.7%**|
|**Black**|**81.2**|**90.9%**|**53.6%**|
|**Hispanic**|**95.3**|**92.3%**|**90.9%**|

- **Consistently high accuracy across demographics**.
- **Lower specificity in Black children (53.6%)**, indicating need for further validation.

---

### **3. Key Predictive Features (SHAP Analysis)**

|**Feature**|**Importance (%)**|
|---|---|
|**Gaze to social stimuli**|**11.1%**|
|**Response to name delay**|**7.1%**|
|**Facial expression complexity**|**6.0%**|
|**Head movement rate**|**4.9%**|

- **Social attention & response to name were the strongest ASD predictors**.

---

## 🔍 Related Work

- **Existing screening tools (M-CHAT-R/F)** often lack **sensitivity** in real-world settings.
- **AI-based models (e.g., eye-tracking, motor analysis)** show promise for **objective ASD diagnostics**.
- **Deep learning approaches** are increasingly used in **behavioral phenotyping**.

---

## 📝 Observations

### **Strengths of the Study**

✅ **High sensitivity (98.4%)** and **strong diagnostic accuracy**.  
✅ **Objective, automated, and scalable**—reduces **clinician burden**.  
✅ **Equitable screening**—performs well across **sex, race, and ethnicity**.  
✅ **Rapid diagnostic turnaround (~11 min)**—potentially shortens **waitlists for ASD specialists**.

---

### **Major Concerns and Challenges**

⚠️ **Indeterminate outputs (68.2%)**—suggests the AI is cautious, **limiting its standalone use**.  
⚠️ **Lower specificity in Black children (53.6%)**—requires **further validation on diverse populations**.  
⚠️ **Exclusion of non-English speakers**—device **not yet multilingual**.  
⚠️ **Home video quality variability**—affects AI’s ability to analyze behavior accurately.

![image-2-x310-y411.png](/img/user/Images/megerian2022a/image-2-x310-y411.png)

![image-3-x35-y145.png](/img/user/Images/megerian2022a/image-3-x35-y145.png)

![image-5-x31-y610.png](/img/user/Images/megerian2022a/image-5-x31-y610.png)

![image-6-x41-y88.png](/img/user/Images/megerian2022a/image-6-x41-y88.png)

![image-7-x29-y51.png](/img/user/Images/megerian2022a/image-7-x29-y51.png)
