---
{"dg-publish":true,"permalink":"/notes-connect-to-papers/cheng2024-notes/"}
---

## Zotero note

[[Literature_review/@cheng2024\|@cheng2024]]

### Appearance-based Gaze Estimation With Deep Learning: A Review and Benchmark

## 📌 Summary

- Provides a **systematic review** of **deep learning-based gaze estimation methods**.
- **Surveys** the **existing gaze estimation algorithms** along a typical pipeline:
    - **Deep feature extraction**
    - **Deep learning model design**
    - **Personal calibration**
    - **Device and platform considerations**
- Introduces a **benchmark for gaze estimation models**, including:
    - **Performance comparisons across different datasets**
    - **Summarization of preprocessing & postprocessing techniques**
- Highlights **current challenges** and proposes **future research directions**.

## 🔬 Methods 

### Gaze tracking history

Eye tracking has evolved from early **mechanical devices** in the late 19th century to **AI-driven gaze estimation** today. Initially, researchers like **Louis Émile Javal** (1879) and **Edmund Huey** (1908) studied eye movements using rudimentary tools. The **1950s** introduced **electrooculography (EOG)**, while the **1970s–80s** saw the rise of **infrared pupil tracking** for non-invasive monitoring. The **2000s** brought **commercial eye trackers** and **remote tracking systems**, expanding applications in **HCI, marketing, and accessibility**. Today, **deep learning and AI** enable real-time gaze tracking in **AR/VR, assistive technology, and medical diagnostics**, making eye tracking more powerful and accessible than ever.

### Deep Learning-Based Gaze Estimation

- **Breaks down gaze estimation models into four key perspectives**:
    1. **Deep Feature Extraction**
        - **Extracting features from:** eye images, face images, video sequences
        - **Use of CNNs, transformers, and self-attention mechanisms**
    2. **Deep Neural Network Architecture Design**
        - **CNN-based architectures** (Supervised, semi-/self-/unsupervised)
        - **Multi-task learning models**
        - **Recurrent CNNs (LSTM, GRU) for temporal modeling**
    3. **Personal Calibration**
        - **Calibration via domain adaptation**
        - **Unsupervised calibration & user-aware personalization**
    4. **Devices and Platforms**
        - **Camera types:** RGB, IR, Depth, Near-eye cameras
        - **Platforms:** Computers, Mobile Devices, Head-Mounted Displays (HMDs)

### Eye-Tracking Sensors & Camera Types from the Article

|**Sensor/Camera Type**|**Description**|**Use Cases**|
|---|---|---|
|**RGB Camera**|Standard cameras capturing facial/eye images.|Used in **appearance-based gaze estimation** with deep learning.|
|**Infrared (IR) Camera**|Uses infrared light to track eye movements and reflections.|Found in **high-precision eye trackers** like Tobii, Pupil Labs, and **VR headsets (HTC Vive Pro Eye, Meta Quest Pro, Apple Vision Pro)**.|
|**RGBD Camera (Depth Camera)**|Captures depth information along with RGB data.|Used in **3D gaze estimation** and **eye-tracking research** (e.g., **ETH-XGaze dataset**).|
|**Near-Eye Camera**|Small cameras placed near the eyes (e.g., embedded in glasses or VR headsets).|Used in **wearable eye trackers** like **Pupil Labs, Tobii Pro Glasses, and MagicEyes dataset**.|
|**Multi-Camera Systems**|Uses multiple cameras to track gaze from different angles.|Found in **head-mounted and remote eye trackers** for **improving accuracy**.|
|**Electrooculography (EOG)**|Measures electrical signals from the eye muscles.|**Older technology** still used in **medical and assistive applications**.|

### Eye-Tracking Devices Mentioned in the Article

|**Device**|**Type**|**Description & Use Cases**|
|---|---|---|
|**Tobii Pro Series** (e.g., **Tobii Pro Spectrum, Tobii Pro Fusion, Tobii EyeX**)|**Remote & Wearable Eye Tracker**|High-precision **infrared-based** trackers used in **research, usability studies, and medical applications**.|
|**Pupil Labs Eye Tracker**|**Wearable (Near-Eye)**|Open-source **eye-tracking glasses** for **VR, AR, and cognitive research**.|
|**SMI (SensoMotoric Instruments)** (Acquired by Apple)|**Remote & Wearable**|Used in **eye-tracking research, automotive safety, and assistive technology**.|
|**EyeLink Series (SR Research)**|**High-Speed Eye Tracker**|Laboratory-grade eye trackers used in **psychology, neuroscience, and vision research**.|
|**Gazepoint GP3**|**Remote Eye Tracker**|Affordable **60Hz gaze tracker** for **usability testing and academic research**.|
|**Tobii 4C**|**Consumer Eye Tracker**|Used for **gaming, accessibility, and HCI research**.|
|**HTC Vive Pro Eye**|**VR Headset with Eye Tracking**|Integrates **Tobii eye-tracking technology** for **VR research and foveated rendering**.|
|**Meta Quest Pro**|**VR Headset with Eye Tracking**|Uses **AI-powered gaze estimation** for **immersive experiences and productivity applications**.|
|**Apple Vision Pro**|**Mixed Reality Headset**|Advanced **eye-tracking system for spatial computing**, featuring **foveated rendering and gaze-based UI interaction**.|
|**MagicEyes Dataset (Wu et al.)**|**IR-Based Near-Eye Camera**|Dataset collected using **infrared-based head-mounted eye-tracking cameras**.|
#### Summary of Gaze Estimation Perspectives

| Perspective         | Methods |
|---------------------|--------------------------------------------------------------|
| **Feature Extraction** | Eye images, Face images, Videos |
| **Model**            | Supervised CNNs, Semi-/Self-/Un-supervised CNNs, Multi-task CNNs, Recurrent CNNs, CNNs with Priors |
| **Calibration**      | Domain Adaptation, User-unaware Data Collection |
| **Camera**          | Single Camera, Multi-Cameras, IR Camera, RGBD Camera, Near-eye Camera |
| **Platform**        | Computer, Mobile Device, HMD Device |


### Eye-Tracking Device Specifications from the Article

|**Device / Sensor Type**|**Sampling Frequency (Hz)**|**Accuracy (Degrees)**|**Resolution**|**Use Case**|
|---|---|---|---|---|
|**Tobii Pro Spectrum**|**600 Hz**|**0.2°**|High-Resolution IR Tracking|Research, Neuroscience, Cognitive Studies|
|**Tobii Pro Fusion**|**120/250 Hz**|**0.3°**|High-Resolution IR Tracking|Usability Testing, UX Research|
|**Pupil Labs Eye Tracker**|**200 Hz**|**Varies (~0.5°–1.5°)**|HD Video|AR/VR Research, HCI Studies|
|**EyeLink 1000 Plus (SR Research)**|**1000 Hz**|**0.15°–0.25°**|High-Resolution|Neuroscience, Vision Research|
|**Gazepoint GP3**|**60 Hz**|**0.5°–1°**|1280 × 1024|Affordable eye-tracking for UX/HCI|
|**HTC Vive Pro Eye**|**120 Hz**|**0.5°–1.1°**|Integrated IR Camera|VR, Gaming, Eye-Based UI|
|**Meta Quest Pro**|**90–120 Hz**|**~1°**|AI-Powered Gaze Estimation|VR/AR, Foveated Rendering|
|**Apple Vision Pro**|**High-Frequency (~500 Hz est.)**|**~0.5° (est.)**|AI-Based Eye Tracking|Mixed Reality, Eye-Based Interaction|
|**Tobii 4C (Consumer Tracker)**|**90 Hz**|**0.5°–1°**|Standard IR-Based|Gaming, Accessibility|
|**NVGaze Dataset (IR-Based Near-Eye Cameras)**|**1000 Hz**|**0.3°**|Infrared Imaging|Research, AR/VR Tracking|

### Challenges in Deep Learning-Based Gaze Estimation

Despite significant advancements, deep learning-based gaze estimation faces several **challenges** that impact **accuracy, generalizability, and real-world applicability**. Below are the key challenges:

---

### Cross-Subject Variability

🔹 **Problem**: Different individuals have **unique eye shapes, pupil sizes, and gaze behaviors**, making it difficult for models trained on one population to generalize to another.  
🔹 **Impact**: A model trained on one dataset often **performs poorly** on unseen individuals without **recalibration**.  
🔹 **Possible Solution**: **Personalized gaze models** or **domain adaptation techniques** can help address this issue.

---

### Head Pose & Eye Movement Variations

🔹 **Problem**: **Head movements** and **eye rotations** significantly affect gaze estimation accuracy, especially in **unconstrained environments** (e.g., mobile settings).  
🔹 **Impact**: Models trained on **static frontal views** struggle with **side angles or extreme head poses**.  
🔹 **Possible Solution**: Incorporating **head-pose-invariant features**, **multi-view training**, or **transformer-based models** to handle pose variations.

---

### Environmental & Lighting Conditions

🔹 **Problem**: **Ambient lighting**, screen brightness, and reflections affect **pupil visibility and corneal reflections**, reducing model reliability.  
🔹 **Impact**: Gaze estimation accuracy **drops significantly** in poor lighting or **outdoor environments**.  
🔹 **Possible Solution**: **Infrared-based tracking** or **adaptive contrast normalization** can mitigate this issue.

---

### Data Scarcity & Bias

🔹 **Problem**: Most datasets are collected in **controlled environments**, leading to **limited diversity** in age, ethnicity, and real-world conditions.  
🔹 **Impact**: Models trained on **homogeneous datasets** often fail in **real-world settings**.  
🔹 **Possible Solution**: Expanding **diverse, large-scale datasets** (e.g., **ETH-XGaze, Gaze360**) and using **synthetic gaze data augmentation**.

---

### Annotation Challenges & Label Noise

🔹 **Problem**: Manually labeling gaze data is **time-consuming and error-prone**, especially for **3D gaze estimation**.  
🔹 **Impact**: Inconsistent annotations introduce **label noise**, leading to **biased training data**.  
🔹 **Possible Solution**: Using **self-supervised learning** or **semi-automated labeling** to improve data quality.

---

### Real-Time Performance & Hardware Constraints

🔹 **Problem**: Deploying gaze estimation on **mobile devices, AR/VR headsets, and embedded systems** is computationally demanding.  
🔹 **Impact**: High **power consumption and latency** limit practical applications.  
🔹 **Possible Solution**: Optimizing models for **low-power devices** and using **lightweight neural networks (e.g., MobileNet, Transformer-Lite).**

---

### Privacy & Ethical Concerns

🔹 **Problem**: Gaze data can reveal **sensitive information** about a user’s **intentions, emotions, and cognitive state**.  
🔹 **Impact**: Potential **misuse of gaze-tracking data** in surveillance or **advertising** raises **privacy concerns**.  
🔹 **Possible Solution**: Implementing **privacy-preserving gaze estimation techniques**, such as **on-device processing** or **differential privacy models**.

### Benchmarks in Deep Learning-Based Gaze Estimation

The article provides **benchmarks** to evaluate the performance of gaze estimation methods. These benchmarks are designed to ensure **fair comparisons across different datasets, models, and evaluation settings**. Below are the main benchmarks outlined:

---

### Within-Dataset Evaluation

- **Description**: Measures the model's performance on unseen subjects within the same dataset.
- **Evaluation Protocol**:
    - Datasets are split into **training and testing sets** based on subjects (no overlap).
    - **Key Metric**: Angular error for 3D gaze or Euclidean distance for 2D gaze.
- **Top-Performing Models**:
    - **Gaze360** [43] (ResNet-based architecture with pretraining).
    - **CA-Net** [56] (Combines face and eye features).
    - **GazeTR-Hybrid** [34] (Transformer-based gaze estimation).

---

### Cross-Dataset Evaluation

- **Description**: Assesses a model's ability to generalize to new datasets or unseen environments.
- **Evaluation Protocol**:
    - Train on one dataset (source domain) and test on another (target domain).
    - Datasets include **ETH-XGaze, Gaze360, MPIIFaceGaze, and EyeDiap**.
- **Domain Adaptation Methods**:
    - **CRGA [143]**: Uses contrastive regression for better generalization.
    - **RUDA [111]**: Rotation-aware adaptation with target-specific calibration.
    - **CSA [143]**: Source-free domain adaptation to protect privacy.

---

### Dataset-Specific Benchmarks

- **Datasets**:
    - **MPIIGaze**: Collected in daily life; free head pose.
    - **Gaze360**: Indoor and outdoor environments; wide gaze range.
    - **ETH-XGaze**: High-resolution images; extreme head poses and lighting variations.
    - **EyeDiap**: Videos with depth data; free and fixed head poses.
    - **GazeCapture**: Mobile device data collected in uncontrolled settings.
- **Metrics**:
    - **Angular Error (Degrees)**: Measures 3D gaze estimation accuracy.
    - **Euclidean Distance (cm)**: Measures 2D point-of-gaze (PoG) estimation accuracy.

---

### 2D Point-of-Gaze (PoG) Estimation

- **Evaluation Protocol**:
    - Tested on **MPIIGaze, EyeDiap, and GazeCapture** datasets.
    - Evaluates the **distance error** between estimated and actual gaze points.
- **Top Models**:
    - **AFF-Net [57]**: Best performance across most datasets.
    - **EFE [187]**: Real-time frame-to-gaze estimation.

---

### 3D Gaze Estimation

- **Evaluation Protocol**:
    - Tested on datasets like **MPIIFaceGaze, ETH-XGaze, and Gaze360**.
    - Evaluates **angular error** between predicted and ground truth gaze vectors.
- **Performance Trends**:
    - Face-based models outperform eye-based models in **3D estimation** due to richer contextual features.

---

### Metrics Used in Benchmarks

|**Metric**|**Description**|
|---|---|
|**Angular Error (Degrees)**|Measures the difference between predicted and actual 3D gaze directions.|
|**Euclidean Distance (cm)**|Measures the 2D distance between predicted and actual gaze points (PoG).|
|**Cross-Dataset Generalization**|Evaluates how well models trained on one dataset perform on another.|

---

### Model Performance Highlights

- **Within-Dataset Best Performers**:
    - **CA-Net**: 4.27° angular error on MPIIFaceGaze.
    - **Gaze360**: 5.36° angular error on EyeDiap.
- **Cross-Dataset Adaptation**:
    - **CRGA [143]**: Achieved 5.37° angular error on ETH-XGaze to MPIIGaze.
    - **PureGaze [72]**: Generalized well across multiple domains.

---

### Conclusion

The benchmarks highlight that:

1. **Within-dataset accuracy** is consistently improving with hybrid CNN-Transformer models and multi-view training.
2. **Cross-dataset generalization** remains challenging but can be improved with domain adaptation methods.
3. **Dataset diversity** is critical for evaluating real-world applicability.

### Summary of Common Gaze Estimation Datasets

|**Dataset**|**Subjects**|**Total Annotations**|**Full Face**|**2D Gaze**|**3D Gaze**|**Brief Introduction**|**Links**|
|---|---|---|---|---|---|---|---|
|**Columbia** [184] (2013)|58|6K images|✓|×|✓|Collected in laboratory; 5 head poses and 21 gaze directions per head pose.|[Link](https://cs.columbia.edu/CAVE/databases/columbia_gaze)|
|**UTMultiview** [37] (2014)|50|1.1M images|×|✓|✓|Collected in laboratory; Fixed head pose; Multiview eye images; Synthesis eye images.|[Link](https://ut-vision.org/datasets)|
|**EyeDiap** [185] (2014)|16|94 videos|✓|✓|✓|Collected in laboratory; Free head pose; Additional depth videos.|[Link](https://idiap.ch/dataset/eyediap)|
|**MPIIGaze** [49] (2015)|15|213K images|×|✓|✓|Collected by laptops in daily life; Free head pose and illumination.|[Link](https://mpi-inf.mpg.de/mpiigaze)|
|**GazeCapture** [42] (2016)|1,474|2.4M images|✓|✓|×|Collected by mobile devices in daily life; Variable lighting condition and head motion.|[Link](https://gazecapture.csail.mit.edu)|
|**MPIIFaceGaze** [50] (2017)|15|~45K images|✓|✓|✓|Collected by laptops in daily life; Free head pose and illumination.|[Link](https://mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/gaze-based-human-computer-interaction/its-written-all-over-your-face-full-face-appearance-based-gaze-estimation)|
|**InvisibleEye** [147] (2017)|17|280K images|×|✓|×|Collected in laboratory; Multiple near-eye cameras; Low-resolution cameras.|[Link](https://mpi-inf.mpg.de/invisibleeye)|
|**TabletGaze** [186] (2017)|51|816 videos|✓|✓|×|Collected by tablets in laboratory; Four postures to hold tablets; Free head pose.|Link|
|**RT-Gene** [54] (2018)|15|123K images|✓|×|✓|Collected in laboratory; Free head pose; Annotated with mobile eye tracker; Use GAN to remove eye tracker in face images.|[Link](https://github.com/Tobias-Fischer/rt_gene)|
|**Gaze360** [43] (2019)|238|172K images|✓|×|✓|Collected in indoor and outdoor environments; A wide range of head poses and distances.|[Link](https://gaze360.csail.mit.edu)|
|**NVGaze** [149] (2019)|30|4.5M images|×|✓|×|Collected in laboratory; Near-eye images; Infrared illumination.|[Link](https://sites.google.com/nvidia.com/nvgaze)|
|**ShanghaiTechGaze** [121] (2019)|137|224K images|✓|✓|×|Collected in laboratory; Free head pose; Multiview gaze dataset.|[Link](https://github.com/dongzelian/multi-view-gaze)|
|**ETH-XGaze** [66] (2020)|110|1.1M images|✓|✓|✓|Collected in laboratory; High-resolution images; Extreme head poses; 16 illumination conditions.|[Link](https://ait.ethz.ch/projects/2020/ETH-XGaze)|
|**EVE** [67] (2020)|54|~4.2K videos|✓|✓|✓|Collected in laboratory; Free head pose; Free view; Annotated with desktop eye tracker; Pupil size annotation.|[Link](https://ait.ethz.ch/projects/2020/EVE/)|

