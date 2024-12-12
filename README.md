# Time Matters: Understanding the Drivers of Time-of-Day Drug Sensitivity in Human Cells 

## Introduction

This document accompanies the Python and MATLAB scripts for the paper titled “Time Matters: Understanding the Drivers of Time-of-Day Drug Sensitivity in Human Cells”. 

## Abstract

The circadian clock plays a pivotal role in regulating various aspects of cancer, influencing tumor growth and treatment responses. There are significant changes in drug efficacy and adverse effects when drugs are administered at different times of the day, underscoring the importance of considering the time of day in treatments. Despite these well-established findings, chronotherapy approaches in drug treatment have yet to fully integrate into clinical practice, primarily due to a lack of understanding regarding the underlying mechanisms driving time-of-day drug sensitivity. In this study, we employed a combined mathematical and experimental approach to systematically investigate the factors influencing time-of-day drug sensitivity in human cells. Our results elucidate how circadian and drug properties independently shape time-of-day profiles, providing valuable insights into the temporal dynamics of treatment responses. Understanding how drug efficacy fluctuates throughout the day holds immense potential for the development of personalized treatment strategies aligned with an individual’s internal biological clock, revolutionizing cancer treatment by maximizing therapeutic benefits. Moreover, our framework offers a promising avenue for refining future drug screening efforts, paving the way for more effective and targeted therapies across diverse tissue types.
 
## Installation

To use the scripts, ensure you have the following prerequisites:
Version: Python 3.x or higher. MATLAB_R2021b or higher
Necessary libraries and packages : 
Install the following libraries (from Python):
* numpy
* matplotlib
* scipy
* pandas
* seaborn
* pyboat
* warnings
* re
Install the following toolboxes (MATLAB):
* Statistics and Machine Learning Toolbox
* Simulink
* Bioinformatics Toolbox
 
## Usage
To run the scripts will need the data from https://itbfiles.biologie.hu-berlin.de/index.php/s/Ws3LmoPD4xAK7Zp?path=%2F.
Save them in separate folders corresponding to the figures number.
1. For Fig2 scripts:
-	fitting_lumicycle_data.py requires the file lumicycle_data_breast_U2OS_5to142h.xlsx (from folder Fig2_3)
-	circadian_prop_exp.py requires the file Circadian_properties_lumicycle.xlsx (from folder Fig2_3)
-	For Fig3 script: 
-	drug_effect_tod_experim.py requires the file Circadian_properties_lumicycle.xlsx (from folder Fig2_3)
2. For Fig 4 script: 
-	survival_drugs_age.py requires the file 081122_Drug_Stability.xlsx (from folder Fig4_5_6)
3. For Fig5 script:
-	exp_drc_time_eval.py requires the file 041922_Dose_Response.xlsx (from folder Fig4_5_6)

