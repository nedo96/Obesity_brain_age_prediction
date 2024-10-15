# Obesity_brain_age_prediction

The following notebooks have been used to analyze pre-processed neuroimaging data in the article 
"Obesity accelerates brain ageing: a multimodal imaging study". 
In particular, resting state fMRI-derived measures (intra- and inter-connectivity), Gray Matter volume, 
and White Matter integrity measures have been used to predict age and the obesity status using a 
machine learning approach.

The first notebook, BrainAge_Obesity_fMRI, processes fMRI text files and calculates correlations of brain activity across cortical parcels. It then extracts inter- and intra-connectivity measures and uses these types of data separately to predict both age and obesity status. 

The second notebook, BrainAge_Obesity_WM_GM, uses WM integrity values from 48 ROIs and GM volumes 
