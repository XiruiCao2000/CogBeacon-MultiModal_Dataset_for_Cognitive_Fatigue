# DATASET IS UNDER REVIEW AND WILL BECOME AVAILABLE SOON

# CogBeacon-A-Multi-Modal-Dataset-for-Modeling-Cognitive-Fatigue
CogBeacon is a multi-modal dataset designed to target the effects of cognitive fatigue in human performance. The dataset consists of 76 sessions collected from 19 male and female users performing different versions of the Wisconsin Card Sorting Test (WCST); a popular cognitive test in experimental and clinical psychology designed to assess cognitive flexibility, reasoning and specific aspects of cognitive functioning. During each session we record and fully annotate, user's EEG functionality, facial keypoints, real-time self-reports on cognitive fatigue, as well as detailed information of the performance metrics achieved during the cognitive task (success rate, response time, number of errors etc.). Along with the dataset we provide a baseline Machine Learning analysis towards predicting cognitive fatigue and our multi-modal implementation of the WCST, to allow other researches expand or modify the functionalities of the CogBeacon data-collection framework. To our knowledge, this is the first multi-modal dataset specifically designed to assess cognitive fatigue.



## CogBeacon Data Collection Platform can be found @ [The WCST Interface](https://github.com/MikeMpapa/CogBeacon-WCST_interface/)

## Dataset Detail

### EEG Data:
The EEG Data was recorded using the [Muse EEG headset](https://choosemuse.com/). The headset has four electrodes, two over the prefrontal lobe and two behind the ears. The data set consists of:
* **Raw EEG :** at a sampling frequency of 220 Hz
* **Absolute Frequency Bands (A):** $\gamma$, $\beta$, $\alpha$, $\theta$ and $\delta$ at sampling frequency of 10 Hz. The absolute band power for a given frequency range is the logarithm of the sum of the Power Spectral Density of the EEG data over that frequency range.


2 - line description
filename structures
Signals : name frequency, formulas

### Facial:
2- line description- 68 keypoints + 4 corners for bounding box
frame rate
extraction algorithm 
filename structure

### Fatigue self report:
2 line description: ie. how it was obtained
filename structure

### User Performance:
2-line description
explain csv columns

### Source code + ML analysis:
link to: datasets used for ML analysis (balanced+unbalanced)
+analysis code: feature extraction +modeling, dataset creation
