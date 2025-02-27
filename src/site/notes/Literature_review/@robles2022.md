---
{"dg-publish":true,"permalink":"/literature-review/robles2022/","title":"A Virtual Reality Based System for the Screening and Classification of Autism","tags":["VirtualReality","Autism","ML","Avatars","diagnosis"]}
---


## A Virtual Reality Based System for the Screening and Classification of Autism

> [!Cite]
> Robles, M., Namdarian, N., Otto, J., Wassiljew, E., Navab, N., Falter-Wagner, C. M., & Roth, D. (2022). A Virtual Reality Based System for the Screening and Classification of Autism. _IEEE Transactions on Visualization and Computer Graphics_, _28_(5), 2168–2178. IEEE Transactions on Visualization and Computer Graphics. [https://doi.org/10.1109/TVCG.2022.3150489](https://doi.org/10.1109/TVCG.2022.3150489)


>[!md]
> **Year**:: 2022   
> **Citekey**:: robles2022  
> **itemType**:: journalArticle  
> **Journal**:: *IEEE Transactions on Visualization and Computer Graphics*  
> **Volume**:: 28  
> **Issue**:: 5   
> **Pages**:: 2168-2178  
> **DOI**:: 10.1109/TVCG.2022.3150489    

> [!LINK] 
> [2022_Robles et al._A Virtual Reality Based System for the Screening and Classification of Autism.pdf](zotero://select/library/items/VDZNNGNM)

> [!Abstract]
>
> Autism - also known as Autism Spectrum Disorders or Autism Spectrum Conditions - is a neurodevelopmental condition characterized by repetitive behaviours and differences in communication and social interaction. As a consequence, many autistic individuals may struggle in everyday life, which sometimes manifests in depression, unemployment, or addiction. One crucial problem in patient support and treatment is the long waiting time to diagnosis, which was approximated to seven months on average. Yet, the earlier an intervention can take place the better the patient can be supported, which was identified as a crucial factor. We propose a system to support the screening of Autism Spectrum Disorders based on a virtual reality social interaction, namely a shopping experience, with an embodied agent. During this everyday interaction, behavioral responses are tracked and recorded. We analyze this behavior with machine learning approaches to classify participants from an autistic participant sample in comparison to a typically developed individuals control sample with high accuracy, demonstrating the feasibility of the approach. We believe that such tools can strongly impact the way mental disorders are assessed and may help to further find objective criteria and categorization.
>.
> 


## Notes

| File                                                           | file.name        |
| -------------------------------------------------------------- | ---------------- |
| [[NotesConnectToPapers/robles2022_notes\|robles2022_notes]] | robles2022_notes |

{ .block-language-dataview}


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/notes-connect-to-papers/robles2022-notes/" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">




## 📌 Summary

- The paper presents a virtual reality (VR)-based system for the screening and classification of Autism Spectrum Disorder (ASD).
- The system simulates a social shopping interaction to collect non-verbal behavioral data (e.g., eye gaze, head movements).
- Machine learning models classify participants as ASD or typically developed (TD) based on recorded behavioral patterns.
- The method demonstrates high classification accuracy and highlights VR's potential as a non-invasive, efficient screening tool.

## 🔬 Methods

### Study Design

- Between-group design comparing ASD and TD participants.
- Participants performed tasks in a VR supermarket scenario while behavioral data was collected.

### Participants

|Group|N|Gender|Age (Mean ± SD)|Verbal IQ|Non-verbal IQ|
|---|---|---|---|---|---|
|ASD|6|3F / 3M|28.83 ± 8.98|110.0|110.66|
|TD Matched|6|3F / 3M|23.16 ± 2.0|108.0|114.1|
|TD Random|7|4F / 3M|23.31 ± 2.39|104.16|114.1|

### Tasks for participants

- The primary task was a shopping simulation in a virtual supermarket.

|Task|Purpose|Format|Data Collected|
|---|---|---|---|
|Introductory Tutorial|Acclimate participants to VR|VR tutorial & virtual mirror|Familiarization time, eye calibration|
|Shopping Task|Simulate real-life social interaction|VR interaction with agent|Gaze patterns, head motion|
|Payment Task|Introduce a transactional context|Drag cash to virtual register|Hand movement data|

### System setup and hardware

- The system used HTC Vive Pro Eye with integrated eye-tracking.

|Device|Purpose|Specs|
|---|---|---|
|HTC Vive Pro Eye|VR and eye-tracking|Integrated Tobii eye tracker|
|Vive Controllers|Interaction with objects|Position, rotation logging|
|Vive Trackers|Body motion tracking|Real-time avatar replication|

### Data Analysis

- Behavioral data was analyzed to identify differences between ASD and TD groups.

|Feature|Task|Description|
|---|---|---|
|Eye gaze dwell time|Social interaction|Time spent looking at specific areas|
|Head movement|Social interaction|Head orientation changes|
|Gaze vector shifts|Social interaction|Changes in gaze direction|
|Fixation time on AOIs|Social interaction|Attention to agent's face vs. background|

## 📊 Results & Key Findings

### Key Findings:

- ASD participants showed significantly reduced fixation on the agent's eyes and increased attention to background elements.
- Differences in gaze shift patterns were evident, with ASD participants displaying more abrupt changes.
- Machine learning models achieved high classification accuracy, with the best-performing model reaching 100% accuracy in some configurations.

### Implications:

- VR-based screening tools offer promising potential for early, objective ASD diagnosis.
- Eye-tracking metrics, particularly fixation time on social areas, can be key markers for ASD.
- The system could be adapted for children and for screening other neurodevelopmental disorders.

## 🔍 Related Work

- Previous studies indicated differences in eye gaze and social attention in ASD populations.
- Similar machine learning-based approaches using desktop eye-tracking have shown lower classification accuracies.
- The current study extended prior work by introducing VR to create a more immersive, ecologically valid environment.

## 📝 Observations

### Strengths of the Study

- Innovative use of VR to simulate social interactions.
- Objective, non-invasive screening approach using eye-tracking data.
- High classification accuracy with relatively simple interaction paradigms.
- Potential scalability for clinical settings.

### Major Concerns and Challenges

- Small sample size limits the generalizability of findings.
- Potential overfitting in machine learning models due to limited data.
- VR environment may not replicate the full complexity of real-life social interactions.
- Lack of diverse age groups and intellectual profiles.
- The system's reliance on static narratives may reduce engagement for some participants.

The study demonstrates the feasibility of VR-based ASD screening, yet future work should address sample diversity, interaction dynamics, and potential applications for children to improve generalizability and clinical relevance.

</div></div>


## Figures

**Imported: 2025-02-17**

> ![Images/robles2022/image-undefined-x40-y329.png](/img/user/Images/robles2022/image-undefined-x40-y329.png)

> ![Images/robles2022/image-3-x16-y620.png](/img/user/Images/robles2022/image-3-x16-y620.png)

> ![Images/robles2022/image-3-x16-y430.png](/img/user/Images/robles2022/image-3-x16-y430.png)

> ![Images/robles2022/image-3-x285-y424.png](/img/user/Images/robles2022/image-3-x285-y424.png)

> ![Images/robles2022/image-4-x26-y413.png](/img/user/Images/robles2022/image-4-x26-y413.png)

> ![Images/robles2022/image-4-x287-y412.png](/img/user/Images/robles2022/image-4-x287-y412.png)

> ![Images/robles2022/image-5-x20-y490.png](/img/user/Images/robles2022/image-5-x20-y490.png)

> ![Images/robles2022/image-5-x283-y661.png](/img/user/Images/robles2022/image-5-x283-y661.png)