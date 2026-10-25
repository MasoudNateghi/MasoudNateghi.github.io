---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

Please find a complete list of publication records in my [Google Scholar](https://scholar.google.com/citations?hl=en&user=CBhZKN8AAAAJ) profile. 
## 1. Prenatal Care Monitoring via Fetal ECG

An estimated 15% of pregnancies during labor involve severe complications, contributing to nearly two million stillbirths annually. Fetal ECG is an emerging non-invasive and accessible technology used to monitor fetal heart rate (HR) which is an indirect proxy of fetal well-being. Fetal ECG provides access to both fetal and maternal modalities including maternal ECG, maternal HR, uterine contractions, and respiration. The maternal and fetal cardiovascular systems are physiologically distinct but functionally connected through the placenta, and fetal HR continuously adapts to maternal cardiovascular function, uteroplacental perfusion, uterine contractions, fetal autonomic regulation, fetal movement, fetal oxygenation, and medications.
Fetal ECG has been widely used for FHR extraction and less attention has been devoted to integrating fetal ECG morphology and maternal modalities for fetal-maternal health assessment.
Specifically, three fundamental questions remain unanswered:

(1) To what extent does maternal physiological activity contribute to FHR during pregnancy and labor?<br>
(2) Does incorporating maternal physiological information improve assessment of fetal well-being and prediction of pregnancy outcomes beyond FHR alone?<br>
(3) Does FECG morphology provide additional clinically relevant information beyond heart rate dynamics?<br>

To address this gap, we developed Kalman Filter-based Granger Causality (KF-GC) framework. This generic framework allows causal inference in Granger sense (predictibility) from non-stationary timeseries data. As a usecase we applied this framework investigate if there is any coupling between the two timeseries. The results show a clear coupling which changes direction in transition from pregnancy period to labor.

The framework is inteded to extended by incorporating additional maternal physiological modalities to investigate their dynamic coupling with fetal cardiovascular activity. We then aim to apply the expanded framework on a larger cohort of 12,000 subjects from Zambia, Ghana, and India with diverse pregnancy outcomes to investigate whether multimodal maternal–fetal coupling biomarkers can improve the prediction of adverse pregnancy outcomes.

![Prenatal care monitoring via fetal ECG](/images/kfgc.png)

- [Kalman Filter-Based Granger Causality — GitHub](https://github.com/alphanumericslab/kalman-granger-causality)<br>
- [A Kalman Filter–Based Framework for Granger Causality Assessment: Application in Tracking Maternal–Fetal Heart Rate Coupling](https://doi.org/10.1109/TBME.2026.3710372), *IEEE TBME*, 2026


## 2. Cardiovascular Biomarker Discovery in Chronic Kidney Disease
Chronic kidney disease (CKD) is associated with an increased risk of cardiovascular complications and mortality. One of the contributing factors is autonomic nervous system dysfunction, particularly sympathetic nervous system overactivity, which can alter cardiovascular regulation and increase cardiovascular risk. Understanding these physiological abnormalities requires the analysis of multiple cardiovascular signals, including ECG, continuous BP, and muscle sympathetic nerve activity (MSNA).

To investigate cardiovascular and autonomic dysfunction in patients with CKD, we developed an **automated, end-to-end signal processing framework** for analyzing ECG, continuous BP, and MSNA recordings. The framework integrates signal preprocessing, quality assessment, fiducial point detection, and extraction of a comprehensive set of cardiovascular biomarkers, including heart rate variability, blood pressure dynamics, cardiac baroreflex sensitivity.

In parallel, we have developed an **interactive web-based interface** that allows researchers and clinicians to upload physiological recordings, execute standardized processing pipelines, visualize signals and extracted biomarkers, and conduct reproducible analyses without requiring extensive signal processing or programming expertise. 

![](/images/ckd1.png)
![](/images/ckd2.png)

## 3. Multimodal Signal Processing for Mental Health Assessment
Depression is one of the most prevalent mental health disorders worldwide, affecting millions of individuals and significantly impacting their quality of life. Conventional depression assessments primarily rely on clinical interviews and self-reported questionnaires, which may be influenced by subjective interpretation and individual reporting differences. Physiological signals, on the other hand, can provide complementary, objective information about the neural, cardiovascular, and autonomic processes associated with mental health conditions.

This research was conducted as part of the **DARPA-funded [PRESCRIBE](https://cra.com/new-mental-health-screening-tool-from-charles-river-analytics-will-aid-in-warfighter-health-and-readiness/) project**, led by Charles River Analytics in collaboration with Emory University, Georgia Tech, and Tufts University. As part of this collaborative effort, we designed and conducted a psycholinguistic experiment involving simultaneous acquisition of multiple physiological modalities, including EEG, ECG, PPG, EDA, respiration, SCG, continuous blood pressure, and eye-tracking measurements. Participants were exposed to linguistic stimuli with varying emotional content while their physiological responses were continuously recorded. 

Our research focuses on extracting clinically meaningful biomarkers from cardiovascular and neural signals to investigate their associations with depression risk and severity. We applied signal processing and machine learning techniques to ECG and PPG recordings for depression prescreening, while also investigating EEG event-related potentials (ERPs) to identify neural signatures associated with depression severity. Our broader goal is to develop objective, accessible, and individualized approaches to mental health assessment by integrating information from multiple physiological modalities.

![](/images/prescribe1.png)

- [Prescreening Depression Using Wearable Electrocardiogram and Photoplethysmogram Data from a Psycholinguistic Experiment](https://doi.org/10.1088/1361-6579/adf6fe), *Physiological Measurement*, 2025.
- [Decoding Depression: Event Related Potential Dynamics and Predictive Neural Signatures of Depression Severity](https://doi.org/10.1016/j.jad.2025.119893), *Journal of Affective Disorders*, 2025.

## 4. Cuff-based Blood Pressure Systematic Bias Analysis and Correction

## 5. Kalman Filtering and Dynamical Modeling of Physiological Systems


