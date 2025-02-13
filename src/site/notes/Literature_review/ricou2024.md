---
{"dg-publish":true,"permalink":"/literature-review/ricou2024/","title":"Invariant response to faces in ASD unexpected trajectory of oculo-pupillometric biomarkers from childhood to adulthoo","tags":["obsidian","EyeTracking","ASD"]}
---


## Invariant response to faces in ASD: unexpected trajectory of oculo-pupillometric biomarkers from childhood to adulthoo

> [!Cite]
> Ricou, C., Mofid, Y., Roché, L., Bufo, M. R., Houy-Durand, E., Malvy, J., Lemaire, M., Elian, J.-C., Martineau, J., Bonnet-Brilhault, F., Wardak, C., & Aguillon-Hernandez, N. (2024). _Invariant response to faces in ASD: Unexpected trajectory of oculo-pupillometric biomarkers from childhood to adulthoo_. [https://doi.org/10.31234/osf.io/vfte9](https://doi.org/10.31234/osf.io/vfte9)


>[!md]
> **Year**:: 2024   
> **Citekey**:: ricou2024  
> **itemType**:: preprint  
> **DOI**:: 10.31234/osf.io/vfte9    

> [!LINK] 
> [2024_Ricou et al._Invariant response to faces in ASD unexpected trajectory of oculo-pupillometric biomarkers from chi.pdf](zotero://select/library/items/G6XYJFE7)

> [!Abstract]
>
> Human faces contain a large amount of information, attracting our attention and inducing physiological engagement. Attraction to human faces can be observed from birth and develops with age and social experience. The oculometric (visual exploration) and pupillometric (physiological reactivity) parameters quantified by eye-tracking can be relevant measures to study attractiveness and engagement with human faces. Autistic people have particularities in terms of visual exploration and physiological reactivity to faces, with a reduction in the time spent on the eyes associated with a reduced pupil dilation. To date, no study has assessed the developmental dynamics of oculo-pupillometric parameters in response to faces. This study aimed to characterize these parameters throughout typical and autistic development. 109 autistic participants (3-34 years old) were compared to 150 neurotypical participants (3-32 years old). Visual stimuli were organized along a gradient of social saliency, going from static objects to static neutral faces, dynamic neutral faces and dynamic emotional faces. Ocular exploration and physiological reactivity in response to faces appear invariant throughout life in the autistic population. Their developmental dynamics differ from those of the neurotypical population, which shows first, an increasing attentional focus on the eye region with age, and second, a pupillary hypersensitivity to social salient stimuli at an early age which then decreases linearly. Our results highlight an apparent lack of maturation of face processing in the case of autism spectrum disorder (ASD) at the population level, possibly hiding atypical and complex individual developmental trajectories. On the other hand, the neurotypical population exhibits a maturation of both oculometric and pupillometric parameters, pointing towards limited age windows in which specific parameters could be used as discriminating biomarkers of ASD.
>.
> 


## Notes

| File                                                         | file.name       |
| ------------------------------------------------------------ | --------------- |
| [[NotesConnectToPapers/ricou2024_notes\|ricou2024_notes]] | ricou2024_notes |

{ .block-language-dataview}


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">





## 📌 Summary

- **Objective**: The study examines the **developmental trajectory of face processing** in autistic individuals using **eye-tracking and pupillometry**.
- **Methodology**:
    - **109 autistic and 150 neurotypical participants** aged **3-34 years**.
    - Measured **visual exploration and pupil dilation** in response to faces of varying social saliency.
- **Key Findings**:
    - **Autistic individuals showed invariant gaze and pupillary responses to faces over time**, while neurotypicals developed stronger **eye fixation and physiological responses** to social stimuli.
    - **Pupillary hypersensitivity in neurotypicals decreased with age**, while autistic individuals exhibited **low and stable physiological responses** across life stages.
    - Differences in **face processing** suggest **atypical maturation of social attention networks in ASD**.


## 🔬 Methods

### Study Design

- **Cross-sectional** design with participants grouped by **four age ranges** (3–7, 8–12, 13–18, 19–33 years).
- **Eye-tracking** and **pupillometry** were used to measure **gaze behavior and physiological reactivity**.
- **Face stimuli varied in social saliency** (static objects, neutral faces, emotional faces).

---

### Participants

| Characteristic        | Value |
|----------------------|--------------------------------|
| **Total Sample**     | 259 participants (3–34 years old) |
| **Autistic Group**   | 109 (93 males, 16 females) |
| **Neurotypical Group** | 150 (84 males, 66 females) |
| **Age Groups**       | 3-7, 8-12, 13-18, 19-33 years |
| **Mean Age**         | ASD: 13.03 ± 7.90, TD: 13.05 ± 7.39 |
| **CARS Score (ASD Group)** | 29.13 ± 5.20 |
| **Developmental Quotient (DQ, ASD Group)** | 79.72 ± 28.17 |
| **Exclusion Criteria** | Neurological disorders, vision impairments |



### Tasks for Participants

| Task Name                | Purpose                                    | Format                        | Data Collected |
|--------------------------|--------------------------------|-------------------------|----------------------------|
| **Visual Exploration Task** | Measure gaze behavior | Eye-tracking on static and dynamic face stimuli | Fixation time, gaze transitions |
| **Pupillometry Task** | Assess physiological reactivity | Pupil dilation in response to faces | Pupil size variations (ERPD) |
| **ADOS-2, CARS, DQ Assessments** | Validate ASD diagnosis | Standardized clinical tools | Autism severity, cognitive function |


**Criticism**:

- **Only static images and short videos were used**, lacking **real-world social interaction** elements.
- **No non-social dynamic control stimuli**, making it unclear if **motion itself** influenced responses.

---

### System Setup and Hardware

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **SMI RED500 Eye-Tracker** | Gaze tracking | 60 Hz sampling rate |
| **GazeTracker & SMI Experiment Center** | Data acquisition | Defines AOIs, logs fixation time |
| **MATLAB (2018a)** | Pupil Data Processing | Filters noise, computes pupil size changes |


**Criticism**:

- **60 Hz sampling rate is relatively low** for pupillometry, potentially missing **fine-grained pupil dynamics**.
- **No mention of calibration methods**, which are crucial for accurate eye-tracking data.

---

### Data Analysis

#### Collected Features in Dataset

| Feature Category         | Feature Name              | Related Task | Measurement Description |
|--------------------------|----------------------|-------------|--------------------------|
| **Gaze Behavior**       | Fixation Percentage  | Visual Exploration Task | Time spent looking at eyes, nose, mouth |
| **Gaze Consistency** | Gaze Transition Frequency | Visual Exploration Task | Frequency of gaze shifts between face regions |
| **Pupillary Response**  | Event-Related Pupil Dilation (ERPD) | Pupillometry Task | Pupil dilation to different stimuli |

**Criticism**:

- **No analysis of real-time gaze shifts**, which are more informative than total fixation time.
- **No mention of eye-tracking drift correction**, which is essential for long experiments.

---

## 📊 Results & Key Findings

### Key Findings:

- **Neurotypical participants showed increased attention to eyes with age**, while **autistic individuals had stable, lower fixation on eyes** across all age groups.
- **Pupillary reactivity to social stimuli was stronger in younger neurotypical children** but declined over time.
- **ASD participants had uniformly reduced pupil dilation across all age groups**, indicating **a lack of developmental adaptation to social saliency**.
- **ROC analysis** showed that gaze and pupillary markers could distinguish ASD and TD individuals **more reliably in childhood than in adulthood**.

---

### Implications for the Project

- **Supports the idea that ASD individuals follow an alternative developmental trajectory in face processing**.
- **Suggests that early eye-tracking markers could help identify ASD before behavioral symptoms become pronounced**.
- **Highlights the need for adaptive interventions to improve face-processing skills in autistic children**.

---

## 🔍 Related Work

- **Aligns with previous studies (Klin et al., 2002; Pelphrey et al., 2002) showing reduced eye fixation in ASD**.
- **Extends Martineau et al. (2011) and Sepeta et al. (2012) by demonstrating pupillometry differences across a lifespan**.
- **Contrasts with Fujioka et al. (2020), which suggested increasing eye fixation in ASD until age 10**.

---

## 📝 Observations

### Strengths of the Study

✅ **Large age range (3–34 years) provides insight into long-term ASD developmental trajectories**.  
✅ **Combination of eye-tracking and pupillometry offers both behavioral and physiological insights**.  
✅ **Findings support potential age-specific ASD biomarkers for early diagnosis**.  
✅ **Use of dynamic face stimuli improves ecological validity compared to static-only studies**.

---

### Major Concerns and Challenges

⚠ **Overgeneralization of "Invariant Response"**

- The study **implies that ASD face processing is static across life**, but **individual variability is not well explored**.
- **Cluster analysis could reveal distinct ASD subtypes with different trajectories**.

⚠ **Low Sampling Rate in Eye-Tracking Data**

- **60 Hz is insufficient** for detecting **micro-expressions or rapid gaze shifts**.
- **Future work should use higher-resolution tracking (e.g., 120-300 Hz)**.

⚠ **Limited Task Complexity**

- The study only used **face stimuli with neutral or basic emotions**.
- **More complex real-world interactions (e.g., joint attention, social conversations) should be tested**.

⚠ **Potential Confounds in Pupillary Response**

- **No control for luminance changes between trials**, which could impact pupil dilation.
- **Individual differences in baseline pupil size were not accounted for**.

---

### Final Verdict: Strong but Requires More Real-World Validation

✅ **Provides compelling evidence of ASD-specific differences in face processing**.  
⚠ **Needs refinement in methodology, higher-resolution tracking, and individualized ASD subtyping**.  
🚀 **Future studies should incorporate naturalistic social interactions and real-time tracking methods**.

</div></div>


## Figures

**Imported: 2025-02-13**

> ![Images/ricou2024/image-18-x63-y158.png](/img/user/Images/ricou2024/image-18-x63-y158.png)

> ![Images/ricou2024/image-19-x68-y520.png](/img/user/Images/ricou2024/image-19-x68-y520.png)

> ![Images/ricou2024/image-20-x68-y63.png](/img/user/Images/ricou2024/image-20-x68-y63.png)

> ![Images/ricou2024/image-22-x23-y71.png](/img/user/Images/ricou2024/image-22-x23-y71.png)

> ![Images/ricou2024/image-24-x45-y70.png](/img/user/Images/ricou2024/image-24-x45-y70.png)

> ![Images/ricou2024/image-25-x74-y77.png](/img/user/Images/ricou2024/image-25-x74-y77.png)

> ![Images/ricou2024/image-26-x44-y260.png](/img/user/Images/ricou2024/image-26-x44-y260.png)