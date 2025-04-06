---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "On the Impact of Data Sampling Rates on Event Detection Accuracy in Load Signatures using a Shapelet based Approach"
summary: "Shapelet for Event Detection"
authors: [Abdul Hakmeh]
tags: [Machine Learning]
categories: []
date: 2019-08-08T13:39:15+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "final results on  phase B of BLUED"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/abdulhakmeh/shapelet-based-event-detection"
url_pdf: ""
url_slides: "https://github.com/abdulhakmeh/shapelet-based-event-detection/blob/main/Slides.pdf"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
## Abstract

Non-intrusive load monitoring (NILM) is one of the practical applications of the smart electricity grid. NILM provides a comprehensive road-map to detect and determine operation circumstances of an individual appliance from an aggregate load. It can also provide the energy management system with information about appliance-level power consumption, analytical statistics, and detection of energy-hungry appliances to ensure the efficient use of the resources. The event detection is one of the NILM phases that is responsible for detecting state-changes of the appliances.
 
 In this project, a study is made to measure the impact of data sampling rate on the detection accuracy obtained through an event detection algorithm. Therefore, a machine learning based shapelet approach for electrical appliance use detection is implemented. The fast shapelet approach detects the occurrence of an event that is caused by switching on/off of an electrical appliance. A general architecture is introduced to evaluate the performance through feeding the algorithm with re-sampled data and comparing the obtained accuracy with the sampling rate. Different metrics are used to ensure a comprehensive evaluation; F1-score, confusion matrix, and classification accuracy.



## Data set

To evaluate our algorithm the BLUED dataset is used. The BLUED includes one week of the current and the voltage measurements for a family house in Pennsylvania, Pittsburgh. The data collection were taken in October 2011 from nearly 50 electrical devices in the house. The dataset presents the changes in the operating status of each appliance (turn  on/off). The measurements were taken by using two separate systems; one is at the main distribution panel to capture the current and voltage, and the other system is used to register the time stamps for each event. The reason behind choosing the BLUED is that this dataset in its original form provides raw data of the current and the voltage.

## Results
 The results of the experiment have shown that it is possible to detect appliances events with downsampled data using a shapelet based approach. Furthermore, it would have been as well possible that the downsampling improves the accuracy, but the evaluation of the event detection on noisy downsampled data have statistically verified that the lowering of the sampling rate is directly proportional to the accuracy of the detection in a linear form. 





