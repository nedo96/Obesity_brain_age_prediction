# Obesity_brain_age_prediction

The following notebooks have been used to analyze pre-processed neuroimaging data in the article 
"Obesity accelerates brain ageing: a multimodal imaging study". Analyses were executed using Google Colab.
In particular, resting state fMRI-derived measures (intra- and inter-connectivity), Gray Matter volume, 
and White Matter integrity measures have been used to predict age and the obesity status using a 
machine learning approach. Two notebooks were used:

* **BrainAge_Obesity_fMRI**: the first notebook, uses resting state fMRI, preprocessed as described in the referenced article. It then extracts inter- and intra-connectivity measures and uses these types of data separately to predict both age and obesity status. 

* **BrainAge_Obesity_WM_GM**: the second notebook, utilizes white matter integrity and gray matter values, preprocessed as described in article. It then performs separate predictions on these data types to estimate both age and obesity status.
