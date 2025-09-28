# List of open-access machine-learning (ML) models and associated tools for neonatal brain monitoring technologies

Submit a pull-request to update. 

## Template

- **Description**: 
- **Code**: 
- **Paper**: 
- **Tags**:


## EEG Seizure Detection

- **Description**: Multiple trained seizure detection methods. Proposed method of using a
  time--frequency representation to extract time-varying features coupled with an SVM, and other
  older seizure detection models.
- **Code**: [github | Matlab](https://github.com/ktapani/Neonatal_Seizure_Detection)
- **Paper**: [Tapani et al., Int J Neural Sys,
  2019](https://www.worldscientific.com/doi/abs/10.1142/S0129065718500302)
- **Tags**: EEG, term, seizure detection, SVM, qEEG, quantitative features

--- 

- **Description**: ConvNeXt architecture for a seizure detection model (not a trained model)
- **Code**: [github | Python](https://github.com/cergenx/ConvNeXt-Seizure)
- **Paper**: [Hogan et al., npj Dig Med, 2025](https://www.nature.com/articles/s41746-024-01416-x)
- **Tags**: EEG, seizure detection, term, CNN

--- 

- **Description**: ML method to detect seizures in neonatal EEG.
- **Code**: [github | Python | architecture
  only](https://github.com/dyisaev/seizure-detection-neonates) | [google drive | model
  weights](https://drive.google.com/drive/folders/1rdBADEDl0rj-0kphtSYUdWZYu_6GogL-)
- **Paper**: [Isaev et al., Proc Mach Learning Res, 2020](https://proceedings.mlr.press/v126/isaev20a.html)
- **Tags**: EEG, seizure detection, term, attention network, CNN

--- 

- **Description**: Code to build an explainable ML model for seizure detection.
- **Code**: [github | Python](https://github.com/Dinuka-1999/BraiNeoCare)
- **Paper**: [Udayantha et al., IEEE Conf System Man Cybernetics, 2024](https://arxiv.org/abs/2406.16908)
- **Tags**: EEG, seizure detection, term, explainable AI, XAI, CNN

--- 

- **Description**: ML method to detect seizures in neonatal EEG. Hybrid SVM and CNN trained model.
- **Code**: [github | Matlab](https://github.com/nstevensonUH/Neonatal-EEG-Analysis/tree/master/seizure_detection_CNN)
- **Paper**: [Stevenson et al., IEEE EMBC, 2019](https://ieeexplore.ieee.org/abstract/document/8857367)
- **Tags**: EEG, seizure detection, term, CNN, SVM

---

- **Description**: ML method to detect seizures in neonatal EEG. Small model designed for edge devices.
- **Code**: [github | Python](https://github.com/vishaln15/NeonatalSeizureDetection/tree/main)
- **Paper**: [Nagarajan et al., Int Conf AI Signal Proc, 2022](https://ieeexplore.ieee.org/document/9760524)
- **Tags**: EEG, seizures, term, edge device

--- 

- **Description**: ML model to detect seizures in neonatal EEG. CNN model.
- **Code**: [github | R and Python](https://github.com/artur-gramacki/Epileptic-Seizure-Detection) | [google drive | data](https://drive.google.com/file/d/1FwgR8GjZLwE3z8d36vL7XDAqloVtHgJa/view?usp=sharing)
- **Paper**: [Gramacki and Gramacki, Sci Reports, 2022](https://www.nature.com/articles/s41598-022-15830-2)
- **Tags**: EEG, seizures, term, CNN

---

- **Description**: ML model for seizure prediction over a short forecast window (~3 mins). Uses qEEG
  features and CNN models.
- **Code**: [github | Python](https://github.com/dbernardo05/neoSeer/tree/main)
- **Paper**: [Kim et al., PLoS Dig Health, 2025](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000890)
- **Tags**: EEG, seizure prediction, term

---

### EEG Burst and interburst detection

- **Description**: ML method to detect inter-burst intervals in preterm EEG. Developed and tested on
  a cohort of infants <30 weeks gestational age. Uses SVM and set of qEEG features.
- **Code**: [github | Python version](https://github.com/otoolej/py_burst_detector) | [github | Matlab version](https://github.com/otoolej/burst_detector)
- **Paper**: [O'Toole et al., Med Eng Phys, 2017](https://doi.org/10.1016/j.medengphy.2017.04.003)
- **Tags**: EEG, preterm, interburst intervals, IBI

---

- **Description**: ML method to detect bursts and inter-bursts in term EEG during quiet
  sleep. Trained and tested on a cohort of healthy, normal newborns.
- **Code**: [github | Matlab](https://github.com/sumitraurale/interburst_detector)
- **Paper**: [Raurale et al., EMBC-2020](https://doi.org/10.1109/EMBC44109.2020.9176147)
- **Tags**: EEG, term, normal neonates, sleep, quiet sleep, interburst interval, IBI

---

- **Description**: ML method to detect short-duration bursts of activity in preterm (<30 weeks GA) EEG.
- **Code**: [github | Python](https://github.com/BrianMur92/Preterm_transient_burst_detector)
- **Paper**: [Murphy et al., EMBC-2020](https://doi.org/10.1109/EMBC44109.2020.9175154)
- **Tags**: EEG, preterm, bursts, 

---

## EEG Maturational Age

- **Description**: EEG Maturational Age ML estimator, using support-vector regression (SVR) models.
- **Code**: [github | Matlab](https://github.com/nstevensonUH/Neonatal-EEG-Analysis/)
- **Paper**: [O'Toole et al., Clin Neurophys,
  2016](https://www.sciencedirect.com/science/article/abs/pii/S1388245716300244) and [Stevenson et
  al., Sci Reports, 2017](https://www.nature.com/articles/s41598-017-13537-3)
- **Tags**: EEG, preterm, maturational age, gestational age, SVR

---

## EEG Background grading 

- **Description**: ML method to classify background EEG activity using qEEG features and a ML model.
- **Code**: [github | Matlab](https://github.com/smontazeriUH/Neonatal-EEGBackground-Classifier)
- **Paper**: [Montazeri et al., Front Human Neurosci, 2021](https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2021.675154/full)
- **Tags**: EEG, grading, term, SVM

---

- **Description**: ML method to classifiy background EEG activity using spectrograms and an CNN model.
- **Code**: [github | Python](https://github.com/leahtwomey/Long_term_EEG_Grading_Using_DSP_ML/tree/main)
- **Paper**: [Twomey et al., Sensors, 2025](https://www.mdpi.com/1424-8220/25/10/3007)
- **Tags**: EEG, grading, term, CNN

---

- **Description**: ML method to classify background EEG activity using an average over 3 trained
  CNN models. Winning entry of a data-science competition.
- **Code**: [github | Python](https://github.com/smontazeriUH/INFANT-Data-Science-Challenge)
- **Paper**: [Magarelli et al., preprint, 2025](https://arxiv.org/abs/2509.09695)
- **Tags**: EEG, grading, term, CNN,

---

- **Description**: ML method to classify background EEG activity using a ConvNeXt model. Submission
  of a data-science competition.
- **Code**: [github | Python](https://github.com/fabiom91/ConvNeXt_AI_Competition_Platform)
- **Paper**: [Magarelli et al., preprint, 2025](https://arxiv.org/abs/2509.09695)
- **Tags**: EEG, grading, term, CNN

---

- **Description**: ML method to classify background EEG activity using a ConvNeXt model. Submission
  of a data-science competition.
- **Code**: [github | Python and Matlab](https://github.com/Minimnim/INFANT_ML_challenge)
- **Paper**: [Magarelli et al., preprint, 2025](https://arxiv.org/abs/2509.09695)
- **Tags**: EEG, grading, term, CNN

---

- **Description**: ML method to classify background EEG activity using a ConvNeXt model. Submission
  of a data-science competition.
- **Code**:  [github |
  Matlab](https://github.com/tamaraceranic/Support-Vector-Machines-SVM-with-quantitative-features-EEG-qEEG-)
- **Paper**: [Magarelli et al., preprint, 2025](https://arxiv.org/abs/2509.09695)
- **Tags**: EEG, grading, term, CNN

---

## Associated tools

- **Description**: NEURAL. Curated set of quantitative features for neonatal EEG.
- **Code**: [github (Matlab version)](https://github.com/otoolej/qEEG_feature_set) | [github @BrianMur92 (Python version)](https://github.com/BrianMur92/NEURAL_py_EEG_feature_set)
- **Paper**: [arXiv:1704.05694](https://arxiv.org/abs/1704.05694)
- **Tags**: EEG, qEEG, feature set

---

- **Description**: Quantitative features for preterm EEG
- **Code**: [github | Matlab]()
- **Paper**: [Stevenson et al., Sci Reports, 2017](https://www.nature.com/articles/s41598-017-13537-3)
- **Tags**: EEG, preterm, qEEG, quantitative EEG, feature set

---

- **Description**: Generates cerebral oxygenation-like signals (rcSO2).
- **Code**: [github | Matlab code](https://github.com/otoolej/synth_NIRS_signals)
- **Paper** : [O'Toole et al., EMBC-2018](https://doi.org/10.1109/EMBC.2018.8513523) and [Ashoori et
  al., EMBC-2021](https://doi.org/10.1109/EMBC46164.2021.9630560)
- **Tags**: NIRS, rcSO2, preterms

---

- **Description**: Standard features (e.g. spectral power ratios) of heart rate variability.
- **Code**:  [github | Matlab code](https://github.com/otoolej/hrv_features_neonates)
- **Paper**: used in e.g. [Garvey et al., Pediatric Research, 2021](https://doi.org/10.1038/s41390-021-01412-x)
- **Tags**: ECG, heart rate variability, ECG, term, quantitative features

---

- **Description**: Method to extract sparse, transient-like signals from the cerebral oxygenation
  signals. Based on singular spectral analysis and signal rotation using the cosine transform.
- **Code**: [github | Matlab code](https://github.com/otoolej/transient_decomp_ssa)
- **Paper**: [Ashoori et al., EMBC-2021](https://doi.org/10.1109/EMBC46164.2021.9630560)
- **Tags**: NIRS, rcSO2, preterms

---

- **Description**: Generic method to detect bursts: high-amplitude coupled with
  high-frequency. Includes envelope derivative operator (EDO) and nonlinear energy operator (NLEO).
- **Code**: [github | Python version](https://github.com/otoolej/envelope_derivative_operator) |
  [github | Matlab version](https://github.com/otoolej/nonlinear-energy-operators)
- **Paper**: [O'Toole et al., EMBC-2014](https://doi.org/10.1109/EMBC.2014.6944325)
- **Tags**: EEG, bursts, feature, quantitative, qEEG

---

- **Description**: Downsampling routines for neonatal EEG
- **Code**: [github | Matlab and Python](https://github.com/otoolej/downsample_open_eeg)
- **Paper**: [O'Toole et al., Sci Reports, 2023](https://www.nature.com/articles/s41597-023-02002-8)
- **Tags**: EEG

---

- **Description**: Artefact removal pipeline in EEGLab.
- **Code**: [github | Matlab](https://github.com/vpKumaravel/NEAR)
- **Paper**: [Kumaravel et al., Dev Cog Neurosci, 2022](https://doi.org/10.1016/j.dcn.2022.101068)
- **Tags**: EEG, artefacts, EEGLab

---

