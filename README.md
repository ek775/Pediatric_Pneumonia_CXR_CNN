# Pediatric_Pneumonia_CXR_CNN
Phase 4 project for Flatiron School


![image](https://user-images.githubusercontent.com/73248688/206806614-86c8071c-2cd3-4b91-a4ae-f57e2a6b211e.png)

**Authors**: Eliot Kmiec, Stefano Caruso

## Overview

For this project we performed image classification on pediatric chest x-rays by using data from Mendeley Lab . This dataset contained X-ray images of patients with lower respiratory tract infections caused by both viruses and bacteria. Our hypothetical stakeholder for this project was Doctors without borders, and we were tasked with looking to find patterns in healthy patients and those infected with pneumonia. Our job would be identify and predict which patients have the illness or not. 

Then it's about modeling: We built numerous models ultimately finding the most accurate results. Then we tried different hyperparameters to get the best model with best data accurancy and recall lower the false negatives to lower the chances we miss a patient with pneumonia.

93% accuracy binary cnn model
84% accuracy multiclass cnn model, 0.94 AUC
98% recall binary cnn model 




## Business Problem

Detecting illness and decrease time for interpretation of chest x-rays. Utilizing "human in the loop" both machine learning and human analyze on the same x-ray images. Speed up the diagnosis with limited resources, without sacrificing accuracy/safety. 


## Data

Mendeley, over 5000+ x-ray images of patients analyzed 




## Methods

Load images, generator to convert into pixel values. Create both binary and multi class models to detect the illness and classify. Models were tuned based on their validation performance. An AWS EC2 server was used to assist in computations for modeling. Returns probabilities of each type of pneumonia to assist in diagnosis. 




## Limitations

Additional resouces such as computational power would have allowed us to train models faster and assess more diverse hyperparameters to maximize our model performance. 


## Conclusions




## Next steps

Create an Application for the Machine Learning model to annotate images for the radiologist to review and approve.


## For More Information

Please review our full analysis in [our Jupyter Notebook](Final_Notebook.ipynb) or our [presentation](Pediatric Pneumonia Image Detection Project.pdf).

For any additional questions, please contact **Eliot Kmiec eliotkmiec@gmail.com , Stefano Caruso stefanocaruso456@gmail.com**

## Repository Structure

```
├── README.md                                                     <- The top-level README for reviewers of this project
├── Final_Notebook.ipynb                                          <- Narrative documentation of analysis in Jupyter notebook
├── Pediatric Pneumonia Image Detection Project.pdf               <- PDF version of project presentation
└── images                                                        <- images folder used for project
└── chest_xray                                                    <- data folder used for this project
```
