# skin_cancer_detection

Implementation of classification algorithm on Skin Cancer Images.
Visual Classification is a new promising method of determining the threats of diseases and illnesses that can be optically detected on the surface of the skin or through CT Scans and XRays. In practice, automated detection of these deformities through image analysis is more effective and time efficient than manual diagnosis, cutting costs and resources as well.
The goal of this project is to classify the type of skin cancer in an image using Transfer Learning. 

The Skin Cancer Detection application was implemented as a final project for ITCS 5152 - Computer Vision Course at University of North Carolina at Charlotte during Spring 2021.

# Dataset

HAM10000 dataset - Large collection of multi-sources dermatoscopic images is available which can be used for training or testing the algorithm:
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T

# Required Libraries 
To run the program , following libraries are required:
```
* Numpy 
* Pandas 
* PyTorch
* Matplotlib
* PIL 
* Seaborn for Visualizations.
```

# Implementation 

The first step for implementing the algorithm is to collect the data , preprocess the images to remove unwanted artifacts such as hair, noise. The next step is to segment the image and extract the skin lesions .The extracted lesion is normalized and sent to the RESNET model for learning the features by training and later predict the labels for images.

# Results 

The performance of the trained model and results can be found in the project.ipynb file.
