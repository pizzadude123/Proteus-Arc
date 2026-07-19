<p align="center">
<img width="70" height="100" alt="Screenshot 2026-05-29 at 1 46 25 PM" src="https://github.com/user-attachments/assets/62f761c2-2625-40c8-a44c-9f52cb1f7ced" />
</p>

# Proteus Arc: The OpenSource Real-Life Deployable EEG Model for Diagnosing Alzheimer's. 

<b>Note:</b> Throughout time, new versions of Proteus Arc are constantly created and iterated upon to make for a better model. 

| Category | Description |
|-----------|-----------|
| **Model Type** | GCN |
| **Architecture** | Standard Data Processing(Needs Adjustment) + GCN-Based Edge Relationship Identifier |
| **Task** | Alzheimer's Severity Classification |
| **Classes** | Healthy, Mild, Moderate, Severe |
| **Outputs** | classification into one of the four classes |
| **Dataset Compatibility** | Any standard EEG dataset, aswell as any questionaire with the given questions |
| **Expected Accuracy** | 88–95% average classification accuracy (dataset dependent) -> This was as of the first iteration(v1) |
| **Interpretability** | Identifies dominant edge-to-edge connections influencing predictions |
| **Deployment Goal** | It is lightweight, will be fast, and will help serve communities worldwide |


# Introduction:

Proteus Arc is an Alzheimer's Organization where our goal is to use algorithm's that work on noninvasive and cheap methodologies to diagnose Alzheimer's in an Accessible Manner. The 2 segments are EEG with an 80% Diagnosis Weightage, and AI Questionaire Segment(has questionaire data from the patient as input) with 20% Diagnosis Weightage. 

# Details:

Vision: To increase accessibillity for Alzheimer's diagnosis across India(and potentially internationally), and to provide more knowledge to the field for creating progress to a cure with a propietary data extraction engine which will provide new insights. This algorithm is set to deploy around October-November, where we will use it and scale across old age homes with our execution segment to provide supportative diagnosises that indicate a high/low possibillity of Alzheimer's. 

Problem: In India alone, 6-7 million people have Alzheimer's Disease. Despite this massive figure, only 10% of people know that they have it. This wastes years of people's times with loved ones, and heavily reduces the amount of data on AD which is a bottleneck that hinders progress towards a cure. 

# Datasets:

1. https://openneuro.org/datasets/ds004504/versions/1.0.9
Andreas Miltiadous, Katerina D. Tzimourta, Theodora Afrantou, Panagiotis Ioannidis, Nikolaos Grigoriadis, Dimitrios G. Tsalikakis,
Pantelis Angelidis, Markos G. Tsipouras, Evripidis Glavas, Nikolaos Giannakeas, and Alexandros T. Tzallas (2026).
A dataset of EEG recordings from: Alzheimer's disease, Frontotemporal dementia and Healthy subjects. OpenNeuro. [Dataset] doi: doi:10.18112/openneuro.ds004504.v1.0.9
2. https://www.kaggle.com/datasets/nigarmahmoudshafiq/nigar-eeg-alzheimers-dataset-v1 (to be implemented)
3. https://www.mdpi.com/2306-5729/8/6/95 (to be implemented)

# Preprocessing:
[ DESCRIPTION TO BE ADDED ] 


# mL Algorithm: 
This algorithm has 2 components. The first is the primarily GCN-based model for the EEG test. The second one will be an AI model that analyzes patients voice/text
responce to questions given on a questionaire by a clinician. The weight of the GCN is 80%, while the weight of the AI model is 20%. 


