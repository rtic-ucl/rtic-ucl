---
title: Synthetic CT generation from cone beam CT for radiotherapy treatment plan evaluation and adaptation
date: 2023-06-23

authors: 
  - adam-szmul
  - jamie-mcclelland
author_notes:
  - Research Fellow
  - Principal Investigator
tags:
  - CT 
  - CBCT
  - Synthetic CT
  - Deep learning

profile: true

image:
  placement: 1
  focal_point: "Smart"
  preview_only: false
  alt_text: cycleGAN
---

Over the course of radiotherapy treatment the patient's body might change. For successful treatment we need to ensure that the treatment is delivered as it was intended on planning CTs. The changes to the patient’s body might result in less effective treatment or side effects of the treatment.




My research is on enabling adaptive radiotherapy, which adjusts the planned treatment to the patient’s anatomy changes which have happened since it was planned. During the treatment the patients are scanned again by devices (Cone Beam CT (CBCT)) integrated in the radiotherapy delivery devices. Those show patient’s anatomy exactly how it looks just before the treatment. However they are usually of too low quality to use them to adapt previously prepared plan. 




We use machine learning methods to improve the quality of those scans, generating synthetic CTs based on them with their quality and characteristics closer to the planning CTs. Those synthetic CTs can be used to check if the plan is still accurate and can be safely delivered to the patient or whether the plan should be adjusted. With the improved quality of the images the radiotherapy plan could be adjusted for the patient's anatomy changes while they are already on the treatment bed.  

...
