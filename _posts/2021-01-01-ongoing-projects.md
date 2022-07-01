---
title:  "Ongoing Projects"
layout: post
---

# Hierarchical Classifier

When working in the medical domain, the unbalancing and scarcity of images is one of the main issues. Fortunately, many medical datasets have an intrinsic hierarchical structure. For example, bone fracture classification. The idea of this work is to propose some simple solutions which can be applied to any existing network when using a hierarchical dataset. Very briefly, a specific form of regularization, together with a hierarchical loss, was defined to maximize the prediction at each level of the hierarchy. Finally, a new metric was introduced to better understand the performances of a hierarchical classifier. This work is conducted in collaboration with UTC Sorbonne University under the supervision of [Prof. Yves Grandvalet] (https://scholar.google.com/citations?user=ZX9LE3QAAAAJ&hl=en).

# Computer Assisted Maxillofacial Surgery

Implementation of a Deep Learning based application to assist specialists in surgery pre-planning. As a first step, we are implementing an algorithm that could classify a person into three classes: Mandibular Prognathism, Mandibular Progenism, and Mandibular Laterodeviation. The particularity of this work is that it is trained of different view of the patient (frontal, lateral, ¾) but should return a prediction given just one of the three views, in order to be used in everyday clinical routine. This work is being carried out in collaboration with the Maxillofacial unity of the Molinette Hospital, in Turin – Italy.


# Surgical Video Stream Event Predictor

After defining the concept of the Intelligent Operating Room in a [literature review paper](https://onlinelibrary.wiley.com/doi/10.1002/rcs.2136), we start to implement this conceptualization by implementing an event predictor which can detect anomalies together with giving spatial information to the surgeon. 
We started our work focusing on the blood accumulation problem. We trained a CNN-LSTM to predict the moment when the cavity is filled with blood and it is required intervention from the surgeon. In parallel, the same network is also trained for the segmentation and localization of different objects. This work is carried out with the Urology unity of the San Luigi Hospital, in Orbassano (To) – Italy.

![Blood Accumulation](../assets/blood_accumulation.PNG)
