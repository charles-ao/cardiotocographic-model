# cardiotocographic-model

Cardiotocography is a recording of the fetal heart rate obtained by ultrasound and is used in pregnancy to assess fetal well‐being. We therefore want to use these variables to predict the target variable (NSP), which is the Fetal State Class code - or in other words, the diagnosis.
There are three values this can take:
• N = Normal (1)
• S = Suspect (2)
• P = Pathologic (3)

The Objective is to build a machine learning model which can predict the diagnosis based on the cardiotocographic data. This model should aid clinicians in making an accurate diagnosis. Artifical Neural network will be applied to build this model to support clinicians in screening pregnancies to identify those which potentially have issues so that they can receive further medical attention.

The Dataset contains the following variables:

BPM
  Beat per minutes
APC
  Accelerations per second
FMPS
  Fetal movement per second
UCPS
  Uterine contractions per second
DLPS
  Light declaration per second
SDPS
  Severe declaration per second
PDPS
  Prolonged declaration per second
ASTV
  % of abnormal short term Variability
MSTV
  Mean of short term Variability
ALTV
  % of abnormal long term Variability
MLTV
  Mean of long term Variability
Width
  Width of FHR Histogram
Min
  Min Width of FHR Histogram
Max
  Max Width of FHR Histogram
NSP
  Fetal State Class code
    N=normal (1);
    S=Suspect (2);
    P=Pathologic (3)
