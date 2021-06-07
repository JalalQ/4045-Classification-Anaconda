# Introduction

In this predictive analysis problem, I worked on classification of electronic components to determine which electronic components should be procured by an electronic component suppliers. Due to the non-disclosure agreement (NDA) which I have signed with the company, I am not authorized to share the original data-set.

As part of this project, I held meeting with the business managers of the company to better understand the business requirements and value they expected me to achieve from the dataset which was shared with me. Based on these meetings, I then proposed to use classification analysis on the dataset. Some of dataset had class imbalance problem.

- [x] For the dataset with balance classes, I first audited the features and evaluated the impact of these features on the classes. Based on this analysis, features with missing values and those which were not impacting the prediction of the classes were removed.
- [x] Then various classifiers were trained, and the majority voting ensemble classifier was choosen for final classification. It achieved an accuracy of 80% on the validation dataset. 
- [x] For dataset with class imbalance problem, oversampling was used. While the classification model had an accuracy rate of 67%, a high recall rate of 86% was achieved.
- [x] An executive summary of the key findings of the analysis is provided in **"Final Presentation.pdf"** file.
