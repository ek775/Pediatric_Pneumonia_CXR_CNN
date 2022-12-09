# Pediatric_Pneumonia_CXR_CNN
Phase 4 project for Flatiron School


![image](https://user-images.githubusercontent.com/73248688/206806614-86c8071c-2cd3-4b91-a4ae-f57e2a6b211e.png)

**Authors**: Eliot Kmiec, Stefano Caruso

## Overview

For this project we are going to analyze by using data from Mendeley Lab . This dataset contained a huge amount of information on patients with X-ray results containing peumonia, some where viral or bacteria infections. We set our stakeholders as Doctors without boarders looking to find patterns in healhty patients or infected with pneumonia. Our job would be identify and predict which patients have the illness or not. Then it's about modeling: We built numerous models ultimately finding the most useful results. Then we tried different hyperparameters to get the best model with best data accurancy and recall lower the false negatives to lower the chances we miss a patient with pneumonia.

93% accuracy binary cnn model
84% accuracy multiclass cnn model, 0.94 AUC
98% recall binary cnn model 




## Business Problem

Detecting illness and lower the death rate. Utilizing "human in the loop" both machine learning and human analyze on the same x-ray images. Speed up the diagnosis with limited resources, without sacrificing accuracy/safety. 


## Data

Mendeley, over 5000+ x-ray images of pateints analyzed 




## Methods

Load images, generator to convert into grayscale. Create both binary and multi class models to detect the illness. Predict if ill or healhty. 




## Limitation

Additional resouce such as computational power would have allowed us to train models faster and more diverse hyperparameters to maximize our scores.


## Conclusions




## Next steps

Create a Application for the Machine Learning model to annotate images for the radiologist to review and approve.


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
