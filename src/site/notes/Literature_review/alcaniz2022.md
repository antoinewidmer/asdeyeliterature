---
{"dg-publish":true,"permalink":"/literature-review/alcaniz2022/","title":"Eye gaze as a biomarker in the recognition of autism spectrum disorder using virtual reality and machine learning A proof of concept for diagnosis","tags":["VirtualReality","EyeTracking","machine","autism","spectrum","disorder","behavioral","biomarker","multivariate","supervisedlearning"]}
---


## Eye gaze as a biomarker in the recognition of autism spectrum disorder using virtual reality and machine learning: A proof of concept for diagnosis

> [!Cite]
> Alcañiz, M., Chicchi-Giglioli, I. A., Carrasco-Ribelles, L. A., Marín-Morales, J., Minissi, M. E., Teruel-García, G., Sirera, M., & Abad, L. (2022). Eye gaze as a biomarker in the recognition of autism spectrum disorder using virtual reality and machine learning: A proof of concept for diagnosis. _Autism Research_, _15_(1), 131–145. [https://doi.org/10.1002/aur.2636](https://doi.org/10.1002/aur.2636)


>[!md]
> **Year**:: 2022   
> **Citekey**:: alcaniz2022  
> **itemType**:: journalArticle  
> **Journal**:: *Autism Research*  
> **Volume**:: 15  
> **Issue**:: 1   
> **Pages**:: 131-145  
> **DOI**:: 10.1002/aur.2636    

> [!LINK] 
> [2022_Alcañiz et al._Eye gaze as a biomarker in the recognition of autism spectrum disorder using virtual reality and mac.pdf](zotero://select/library/items/5XAUKQAU)

> [!Abstract]
>
> The core symptoms of autism spectrum disorder (ASD) mainly relate to social communication and interactions. ASD assessment involves expert observations in neutral settings, which introduces limitations and biases related to lack of objectivity and does not capture performance in real-world settings. To overcome these limitations, advances in technologies (e.g., virtual reality) and sensors (e.g., eye-tracking tools) have been used to create realistic simulated environments and track eye movements, enriching assessments with more objective data than can be obtained via traditional measures. This study aimed to distinguish between autistic and typically developing children using visual attention behaviors through an eye-tracking paradigm in a virtual environment as a measure of attunement to and extraction of socially relevant information. The 55 children participated. Autistic children presented a higher number of frames, both overall and per scenario, and showed higher visual preferences for adults over children, as well as specific preferences for adults' rather than children's faces on which looked more at bodies. A set of multivariate supervised machine learning models were developed using recursive feature selection to recognize ASD based on extracted eye gaze features. The models achieved up to 86% accuracy (sensitivity = 91%) in recognizing autistic children. Our results should be taken as preliminary due to the relatively small sample size and the lack of an external replication dataset. However, to our knowledge, this constitutes a first proof of concept in the combined use of virtual reality, eye-tracking tools, and machine learning for ASD recognition. Lay Summary Core symptoms in children with ASD involve social communication and interaction. ASD assessment includes expert observations in neutral settings, which show limitations and biases related to lack of objectivity and do not capture performance in real settings. To overcome these limitations, this work aimed to distinguish between autistic and typically developing children in visual attention behaviors through an eye-tracking paradigm in a virtual environment as a measure of attunement to, and extraction of, socially relevant information.
>.
> 


## Notes

| File                                                             | file.name         |
| ---------------------------------------------------------------- | ----------------- |
| [[NotesConnectToPapers/alcaniz2022_notes\|alcaniz2022_notes]] | alcaniz2022_notes |

{ .block-language-dataview}


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/notes-connect-to-papers/alcaniz2022-notes/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




## 📌 Summary

- The study explores the use of eye gaze as a biomarker for ASD diagnosis using virtual reality (VR) and machine learning.
- It aims to distinguish autistic children from typically developing (TD) peers based on eye-tracking data within an immersive VR environment.
- The study found that autistic children displayed distinct visual attention behaviors, showing preferences for adults and certain social elements.
- Machine learning models trained on eye-tracking data achieved up to 86% accuracy in identifying ASD.
- Results suggest the potential of VR and gaze analysis as an objective ASD assessment tool.

## 🔬 Methods

### Study Design

- Experimental proof-of-concept study using VR and eye-tracking to assess social attention differences between autistic and TD children.
- Applied machine learning models to classify ASD based on eye gaze features.

### Participants

|Group|N|Gender (M/F)|Age (Mean ± SD)|Age Range|
|---|---|---|---|---|
|Autistic|35|Not Specified|5.26 ± 0.51|4–7|
|Neurotypical|20|Not Specified|4.75 ± 0.77|4–7|

- ASD diagnosis was confirmed using ADOS-2 and ADI-R assessments.
- Participants had no ocular pathologies and did not wear glasses.
- Ethical approval obtained from the Polytechnic University of Valencia.

### Tasks for Participants

Participants interacted with various social and non-social stimuli within a VR environment, while their gaze behavior was tracked.

|Task|Purpose|Format|Data Collected|
|---|---|---|---|
|Virtual Mall|Assess eye gaze towards social stimuli|Interactive VR environment|Eye-tracking data|
|Dynamic Stimuli|Examine reactions to moving objects|VR with moving elements|Fixation duration, transitions|
|Static Stimuli|Compare social vs. non-social focus|Stationary elements in VR|Gaze duration on faces, objects|

### System Setup and Hardware

|Device|Purpose|Specifications|
|---|---|---|
|Tobii Pro Glasses 2|Track eye movement|Head-mounted system|
|CAVE VR System|Display immersive environment|3-wall projection|
|Motion Sensors|Record participant movement|Integrated with VR setup|

### Data Analysis

|Feature|Task|Description|
|---|---|---|
|Frames on social AOIs|All tasks|Measures duration of fixation on social stimuli|
|Frames on objects|All tasks|Measures preference for static vs. dynamic objects|
|Face vs. body gaze|Social tasks|Analyzes preference for faces over body parts|
|ML Classification|All tasks|Uses gaze metrics to classify ASD vs. TD|

## 📊 Results & Key Findings

### Key Findings

- Autistic children exhibited greater fixation on adults compared to TD children.
- Autistic children looked more at faces than bodies, particularly in child avatars.
- Static non-social objects received more attention from autistic children than TD children.
- Machine learning models identified ASD with 86% accuracy, with the best performance achieved using SVM classifiers.

### Implications

- Eye-tracking and VR could enhance ASD diagnosis objectivity.
- Machine learning can improve classification of ASD-related gaze behaviors.
- Potential for early detection through gaze-based assessments in virtual settings.

## 🔍 Related Work

- Builds on previous studies using eye-tracking for ASD diagnosis.
- Extends research by integrating immersive VR with real-time gaze tracking.
- Supports existing theories on social attention differences in ASD.

## 📝 Observations

### Strengths of the Study

- Use of an immersive VR environment increases ecological validity.
- Objective gaze tracking provides quantifiable behavioral markers.
- High classification accuracy using machine learning supports feasibility of automated ASD assessment.

### Major Concerns and Challenges

- Small sample size limits generalizability.
- Lack of external validation dataset for machine learning models.
- Limited control over confounding factors such as cognitive ability and sensory sensitivity.
- High equipment costs may restrict clinical adoption.
- VR discomfort or aversion in some autistic children may affect participation.

The study demonstrates promising applications of VR and eye-tracking in ASD assessment but requires further validation with larger and more diverse samples.

</div></div>


## Figures

