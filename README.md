# Anomaly-detection-on-metal-
Detection Anomaly on Metals using the CV technique.

The dataset should be preprocessed. the images should be normalized to 0-1
This detection is done by first converting images  to the thermal images.
Analysing  frequency  in the image. where if there is defect on image there is an non uniform distribution of frequency.
k-means is used in clustring the clusters based on the frequencys. defects/non defects cluster's 
Validating the frequency of defect sample dataset then giving it as thershold frequently for the defect image.
Then this will plot a histgram graph of the frequency/gray scale. Accesing the value of frequency from the graph it can classify the defects and non defects 
