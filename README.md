# Vasculomics-DeepLearning
This project consists in the development of an explainable AI algorithm to classify Brain Arteriovenous Malformations using Arterial Spin Labelling Sequences (ASL). The dataset is composed of 928 images, containing pathologic and healthy examples.
Four different models are trained and evaluated, and finally GradCAM is used as an explainability method.

The final objective is to develop a trained model which is capable of detecting the presence of AVM in pediatric images with high accuracy, and which also provides logical explanations which are validated by radiologists and can contribute to their workflow.

# Content
In this repository two notebooks can be found:
-	The "Vasculomics_preprocessing" file there is the notebook where all the preprocessing of the images, from an original DICOM file, which has been carried out to obtain two final files, one with the pathologic images and one with the healthy ones.
-	In the "Vasculomics_DL" file there is the code related to loading the dataset, model definition and training, application of explainability methods and model validation

In oder to run the previous notebooks, you will need to have previously downloaded the following files:
- A zip folder with the dataset, structured in two NumPy files; “npy_avm.npy” with the images labeled as “AVM” and “npy_normal.npy” with the ones labeled as “healthy”. This data can be found in a zip file in the download link: X. 
-	A zip folder named "models" with all the models already trained. This data can be found in a zip file in the download link: X. 

# Notes
To execute the code, you need to have a platform that accepts the IPYNB extension. There is also the option to open the file automatically on Google Collaboratory. Access the notebook of interest and at the top you will see the button "Open in Colab" which takes you directly to the platform.

It is recommended to save the two folders in the working directory with the same names.
