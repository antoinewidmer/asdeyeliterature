---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/davis2025-notes/"}
---

[[Literature_review/davis2025\|davis2025]]
## 📌 Summary

- The study investigates early **behavioral characteristics** in toddlers who were later diagnosed with **autism (ASD), ADHD symptoms, or both**.
- **506 toddlers** from a longitudinal study were analyzed based on **parent questionnaires at two time points**.
- Four groups were identified: **Autism (n=45), ADHD (n=70), Autism+ADHD (n=30), and Neurotypical (n=361)**.
- Findings indicate that toddlers later identified with **both Autism and ADHD** had **higher levels of behavioral challenges**, including **social-emotional difficulties and higher parental stress levels**.
- ADHD symptoms were **evident in toddlerhood**, supporting **early screening for ADHD alongside autism**.

## 🔬 Methods

### Study Design

- **Longitudinal study** conducted in **four pediatric primary care clinics**.
- Parent-reported behavior data collected at **two time points** (18-24 months & ~36 months).
- Diagnostic classifications were **confirmed through research evaluations and electronic health records**.

### Participants

| Characteristic       | Value |
|---------------------|--------------------------------|
| **Total Sample**    | 506 toddlers (16–38 months old) |
| **Autism Group**    | 45 children |
| **ADHD Group**      | 70 children |
| **Autism+ADHD**     | 30 children |
| **Neurotypical**    | 361 children |
| **Gender Distribution** | 51.8% female, 48.2% male |
| **Ethnicity**       | 15% Hispanic, 12.3% Black, 58.8% White, 10.5% Multiracial, 3.4% Other |
| **Caregiver Education** | 60.3% Graduate degree, 39.7% Bachelor's or Associate's, 19% No college |
| **Inclusion Criteria** | Age 16–38 months, English/Spanish-speaking caregivers |
| **Exclusion Criteria** | Illness, distress preventing participation |


### Tasks for Participants
| Task Name                | Purpose                                    | Format                        | Data Collected |
|--------------------------|--------------------------------|-------------------------|----------------------------|
| **M-CHAT-R/F**           | Autism screening             | Parent questionnaire  | Autism-related behaviors |
| **ADHD-RS**              | ADHD symptom measurement     | Parent questionnaire  | Inattention, hyperactivity |
| **CBCL**                 | Emotional & behavioral functioning | Parent questionnaire | Internalizing & externalizing symptoms |
| **SRS-2**                | Social communication skills  | Parent questionnaire  | Autism-related impairments |
| **Parent Stress Scale**   | General parenting stress | Parent questionnaire  | Emotional and support needs |
| **Autism Parent Stress Index** | Autism-specific parenting stress | Parent questionnaire | Autism-specific caregiver burden |

### System Setup and Hardware

| Device | Purpose | Specifications |
|--------|---------|------------------|
| **REDCap Online Survey Tool** | Parent questionnaire delivery | Web-based secure data collection |
| **Electronic Health Records (EHR)** | Diagnostic confirmation | ICD-9/10 diagnosis retrieval |
| **Remote Telehealth Assessments** | Autism/ADHD evaluation | Used due to COVID-19 restrictions |
| **In-Person Clinical Assessments** | Diagnostic gold standard | ADOS-2, CARS-2, MINI interviews |

### Data Analysis

#### Collected Features in Dataset

| Feature Category          | Feature Name              | Related Task | Measurement Description |
|--------------------------|----------------------|-------------|--------------------------|
| **Autism Behaviors**     | M-CHAT-R/F Score    | M-CHAT-R/F | Autism screening total score |
| **ADHD Symptoms**       | ADHD-RS Score       | ADHD-RS | Hyperactivity/Inattention percentile |
| **Emotional Functioning** | CBCL Internalizing  | CBCL | Anxiety, depression subscale |
| **Behavioral Functioning** | CBCL Externalizing  | CBCL | Aggression, hyperactivity subscale |
| **Social Communication** | SRS-2 Total Score   | SRS-2 | Social responsiveness impairments |
| **Parent Stress Levels** | Autism Stress Index | Autism Parent Stress Index | Autism-specific caregiver stress |

## 📊 Results & Key Findings

### Key Findings:

- **Toddlers later identified with Autism+ADHD showed the most severe behavioral difficulties.**
- **Autism+ADHD group exhibited higher externalizing & internalizing behaviors than Autism-only or ADHD-only groups.**
- **ADHD symptoms were evident by toddlerhood**, supporting **early ADHD screening alongside autism.**
- **Parents of Autism+ADHD toddlers reported significantly greater stress and support needs.**
- **Gender differences:**
    - **Boys had higher Autism and ADHD scores.**
    - **Girls had lower reported ADHD and Autism symptoms.**

### Implications for the Project

- **Supports the need for early, dual screening for both ASD and ADHD.**
- **Emphasizes the importance of parent-reported measures in early identification.**
- **Highlights the necessity for tailored intervention strategies for children with Autism+ADHD.**
- **Suggests that diagnostic delays in ADHD may be problematic for early intervention efforts.**

## 🔍 Related Work

- **Builds on prior research (Hong et al., 2021)** showing **high ADHD symptoms in young autistic children**.
- **Aligns with studies (Gadow et al., 2006; Lecavalier et al., 2011)** confirming **preschool-age ADHD identification.**
- **Confirms earlier findings (Rommelse et al., 2010)** that **Autism+ADHD is associated with lower adaptive behavior.**

## 📝 Observations

### Strengths of the Study

✅ **Large sample size (506 toddlers), diverse racial and socioeconomic representation.**  
✅ **Use of longitudinal data increases reliability of findings.**  
✅ **Gold-standard diagnostic tools (ADOS-2, CARS-2, M-CHAT-R/F, ADHD-RS) used for validation.**  
✅ **Incorporates real-world clinical data from electronic health records (EHR).**  
✅ **First study to track early ADHD symptoms in toddlers later diagnosed with Autism+ADHD.**

### Major Concerns and Challenges

⚠ **Parent-reported data may introduce bias**

- Relies **heavily on subjective questionnaires** rather than **direct behavioral observations**.
- No **teacher or clinician ratings for cross-validation**.

⚠ **Small Autism+ADHD sample (n=30) weakens statistical power**

- A **larger sample** is needed to **confirm findings on Autism+ADHD differences**.

⚠ **Potential Socioeconomic Bias**

- **Higher-income, more-educated families were overrepresented** in the sample.
- **Low-income families less likely to have completed follow-ups**, affecting generalizability.

⚠ **COVID-19 Disruptions May Have Impacted Data**

- **Some diagnostic evaluations were conducted via telehealth**, which **may be less accurate** than in-person assessments.
- **Study attrition was high**, potentially **excluding families facing greater challenges**.

⚠ **No Direct Assessment of Attention in Autism**

- **The study lacks eye-tracking or gaze-based assessments** for objective attention measurement.


### **Final Verdict: Strong but Needs Refinement**

✅ **Provides critical evidence that ADHD symptoms appear in toddlerhood**.  
✅ **Supports early screening for both ASD and ADHD.**  
⚠ **Needs more objective measures, larger Autism+ADHD sample, and better socioeconomic representation.**
