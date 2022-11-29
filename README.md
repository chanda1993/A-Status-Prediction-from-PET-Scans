# Prediction Of Aβ State from Brain Amyloid PET Images Using Machine Learning Algorithm

# Abstract

Background: Analyzing brain amyloid positron emission tomography (PET) images to access the occurrence of β-Amyloid (Aβ) deposition in Alzheimer’s patients requires a lot of time and effort from physicians, and also the variation of each interpreter may differ.  For this reason, a machine learning model was developed using a convolutional neural network (CNN) as an objective decision to predict the Aβ positive and Aβ negative status from brain amyloid PET images.

Method: A total number of 7,344 PET images of 144 subjects were used in this study. The 18F-florbetaben (18F-FBB) PET was administered on all participants, and the criteria for differentiating Aβ positive and Aβ negative state was based on brain amyloid plaque load score (BAPL) that depended on the visual assessment of PET images by the physicians. We applied the CNN algorithm trained in batches of 51 PET images per subject directory from two classes: Aβ positive and Aβ negative states based on the BAPL scores. 

Results: The binary prediction of the model average performance matrices was evaluated after 40 epochs of five trials based on test datasets. The model accuracy for predicting Aβ positivity and Aβ negativity was 82.00±0.02 in the test dataset. The sensitivity and specificity were 97.00±0.02 and 97.00±0.02 with an area under the curve (AUC) of 90.00±0.03.

Conclusion: Based on this study, the designed CNN model has the potential to be used clinically for screening amyloid PET images.
