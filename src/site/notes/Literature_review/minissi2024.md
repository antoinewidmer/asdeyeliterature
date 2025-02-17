---
{"dg-publish":true,"permalink":"/literature-review/minissi2024/","title":"Biosignal comparison for autism assessment using machine learning models and virtual reality","tags":["Virtual","reality","Autism","spectrum","disorder","Eye","movements","Biosignal","Motor","skills","Statistical","machine","learning"]}
---


## Biosignal comparison for autism assessment using machine learning models and virtual reality

> [!Cite]
> Minissi, M. E., Altozano, A., Marín-Morales, J., Chicchi Giglioli, I. A., Mantovani, F., & Alcañiz, M. (2024). Biosignal comparison for autism assessment using machine learning models and virtual reality. _Computers in Biology and Medicine_, _171_, 108194. [https://doi.org/10.1016/j.compbiomed.2024.108194](https://doi.org/10.1016/j.compbiomed.2024.108194)


>[!md]
> **Year**:: 2024   
> **Citekey**:: minissi2024  
> **itemType**:: journalArticle  
> **Journal**:: *Computers in Biology and Medicine*  
> **Volume**:: 171   
> **Pages**:: 108194  
> **DOI**:: 10.1016/j.compbiomed.2024.108194    

> [!LINK] 
> [2024_Minissi et al._Biosignal comparison for autism assessment using machine learning models and virtual reality.pdf](zotero://select/library/items/UQ6E5E73)

> [!Abstract]
>
> Clinical assessment procedures encounter challenges in terms of objectivity because they rely on subjective data. Computational psychiatry proposes overcoming this limitation by introducing biosignal-based assessments able to detect clinical biomarkers, while virtual reality (VR) can offer ecological settings for measurement. Autism spectrum disorder (ASD) is a neurodevelopmental disorder where many biosignals have been tested to improve assessment procedures. However, in ASD research there is a lack of studies systematically comparing biosignals for the automatic classification of ASD when recorded simultaneously in ecological settings, and comparisons among previous studies are challenging due to methodological inconsistencies. In this study, we examined a VR screening tool consisting of four virtual scenes, and we compared machine learning models based on implicit (motor skills and eye movements) and explicit (behavioral responses) biosignals. Machine learning models were developed for each biosignal within the virtual scenes and then combined into a final model per biosignal. A linear support vector classifier with recursive feature elimination was used and tested using nested cross-validation. The final model based on motor skills exhibited the highest robustness in identifying ASD, achieving an AUC of 0.89 (SD = 0.08). The best behavioral model showed an AUC of 0.80, while further research is needed for the eye-movement models due to limitations with the eye-tracking glasses. These findings highlight the potential of motor skills in enhancing objectivity and reliability in the early assessment of ASD compared to other biosignals.
>.
> 


## Notes

| File                                                             | file.name         |
| ---------------------------------------------------------------- | ----------------- |
| [[NotesConnectToPapers/minissi2024_notes\|minissi2024_notes]] | minissi2024_notes |

{ .block-language-dataview}


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">





## 📌 Summary

- The study compares biosignal-based models using virtual reality (VR) and machine learning for ASD assessment.
- It examines motor skills, eye movements, and behavioral responses to distinguish between ASD and TD children.
- A VR environment with four interactive scenes was used for data collection.
- Motor skills provided the most robust classification performance (AUC = 0.89).
- Eye movement models exhibited high variability due to technical challenges.
- The study supports VR-based biosignal analysis as a promising, objective ASD assessment tool.

## 🔬 Methods

### Study Design

- Comparative analysis of biosignal models for ASD classification.
- VR-based experimental setup with motor, eye movement, and behavioral response data collection.

### Participants

|Group|N|Gender (M/F)|Age (Mean ± SD)|Diagnosis|
|---|---|---|---|---|
|ASD|39|32/7|53.14 ± 12.38|ADOS-2 diagnosis|
|TD|42|19/23|57.88 ± 11.62|No reported developmental issues|

### Tasks for Participants

Participants interacted with virtual objects and avatars to elicit motor, behavioral, and visual responses.

|Task|Purpose|Format|Data Collected|
|---|---|---|---|
|Park Presentation|Assess joint attention|Avatar introduces park|Eye movements, motor data|
|Kick Task|Evaluate motor responses|Kick virtual ball|Motor skills, behavioral data|
|Bubble Task|Measure interaction patterns|Pop virtual bubbles|Motor, behavioral performance|
|Flower Task|Evaluate task completion|Collect flowers|Motor, behavioral data|

### System Setup and Hardware

|Device|Purpose|Specifications|
|---|---|---|
|CAVE VR System|Immersive VR environment|4m x 4m x 3m room|
|Azure Kinect DK|Track body movements|Depth camera, 30 fps|
|Tobii Pro Glasses 2|Track eye movements|3D gaze tracking|
|Olorama Technology™|Olfactory stimulation|Two scents: wet grass, rose|
|Logitech Z906|Audio output|5.1 surround sound|

### Data Analysis

|Feature|Task|Description|
|---|---|---|
|Motor displacement|All tasks|Mean, min, max body joint displacement|
|Gaze fixations|Park Presentation|Fixation duration, saccade amplitude|
|Behavioral responses|All tasks|Response time, task accuracy|
|Pupil diameter|Park Presentation|Mean pupil size changes|

## 📊 Results & Key Findings

### Key Findings

- Motor skills models achieved the highest classification performance (AUC = 0.89).
- Behavioral models also performed well (AUC = 0.80), especially in the combined model.
- Eye movement models showed high variability due to calibration difficulties with child participants.
- Non-semantic eye movements performed better than semantic eye movements.

### Implications

- Motor skills data collected in VR can improve objective ASD diagnosis.
- VR-based assessments provide ecologically valid settings for biosignal analysis.
- Eye-tracking tools for children should be optimized for better data quality.

## 🔍 Related Work

- Extends prior research on motor and eye movement differences in ASD.
- Aligns with findings that motor abnormalities are prevalent in ASD populations.
- Highlights the benefits of VR-based diagnostics over traditional lab settings.

## 📝 Observations

### Strengths of the Study

- Multi-biosignal comparison within a controlled VR setting.
- Use of ecologically valid tasks to mimic real-life interactions.
- High-performance motor skill model with robust cross-validation.

### Major Concerns and Challenges

- Eye-tracking limitations due to equipment not designed for young children.
- Sample imbalance in terms of gender, reflecting ASD prevalence but limiting generalizability.
- Potential bias from task novelty and VR unfamiliarity.
- Limited generalizability due to a narrow age range (3-7 years).

The study demonstrates that motor skills are a promising biosignal for ASD assessment, while improvements in eye-tracking technology could enhance the methodology's reliability.

</div></div>


## Figures

**Imported: 2025-02-17**

> ![Images/minissi2024/image-4-x115-y519.png](/img/user/Images/minissi2024/image-4-x115-y519.png)

> ![Images/minissi2024/image-4-x33-y223.png](/img/user/Images/minissi2024/image-4-x33-y223.png)

> ![Images/minissi2024/image-5-x79-y114.png](/img/user/Images/minissi2024/image-5-x79-y114.png)

> ![Images/minissi2024/image-7-x303-y411.png](/img/user/Images/minissi2024/image-7-x303-y411.png)