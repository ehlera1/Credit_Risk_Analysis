# Credit Risk Analysis

## Overview

Partnering with Jill, we will use supervised machine learning to determine credit card risk using a dataset provided to us by LendingClub, a peer-to-peer lending service company. The purpose of this analysis is to help provide and a recommendaiton on whether we can use machine learning to help firms identify and screen high ristk applicants. 

---


## Results
### 1. Naive Random Oversampling
Per the below image we can see the following: 
 - The results classified 51,366 records as High Risk and the 51,366 as Low Risk
 - There was a ballanced accuracty sore of approximatley 64.39%
 - The High Risk precision rate was only 1% with a reacll of 69%
 - The Low Risk had a precision rate of 100% and a recall of 59% 

![NRO_2](https://user-images.githubusercontent.com/90698381/150699610-41c0cb69-2cf3-4d52-92e9-3492828d522e.png)

---

### 2. SMOTE Oversampling
Referencing the image below of or SMOTE Oversampling we can see the following: 
 - The results classified 51,366 records as High Risk and the 51,366 as Low Risk
 - There was a ballanced accuracty sore of approximatley 66.29%
 - The High Risk precision rate was only 1% with a reacll of 63%
 - The Low Risk had a precision rate of 100% and a recall of 69% 

![SMOTE_2](https://user-images.githubusercontent.com/90698381/150699621-3495fc95-b2b9-452c-845c-9707b6c4e671.png)

---

### 3. Undersampling
The below image we can see the following from our undersampling analysis: 
 - 246 classified as High Risk and 246 classifed as Low Risk 
 - There was a ballanced accuracty sore of approximatley 54.43%
 - The High Risk precision rate was only 1% with a reacll of 69%
 - The Low Risk had a precision rate of 100% and a recall of 40% 

![Undersampling_2](https://user-images.githubusercontent.com/90698381/150699626-82e7dd99-6541-4d13-a6db-4c33555c4e9a.png)

---

### 4. Combination (Over and Under) Sampling
The image following is referenceing our Combination Sampling:  
 - The results classified 68,460 records as High Risk and the 62,011 as Low Risk
 - There was a ballanced accuracty sore of approximatley 64.48%
 - The High Risk precision rate was only 1% with a reacll of 72%
 - The Low Risk had a precision rate of 100% and a recall of 57%

![COUS_2](https://user-images.githubusercontent.com/90698381/150699642-8f29c4a2-f01e-4f6b-8e9b-c38689c88652.png)

---

### 5. Balanced Random Forest Classifier
The following image for the Balanced Random Forest Classifier analysis: 
 - The results classified 51,366 records as High Risk and the 246 as Low Risk
 - There was a ballanced accuracty sore of approximatley 78.85%
 - The High Risk precision rate was only 3% with a reacll of 70%
 - The Low Risk had a precision rate of 100% and a recall of 87%

![BRFC_2](https://user-images.githubusercontent.com/90698381/150699657-f25b7727-ce4d-4482-a007-8c1d0d50f64b.png)

---

### 6. Easy Ensemble AdaBoost Classifier 
The following image is our analysis using the Easy Ensemble AdaBoost Classifier: 
 - The results classified 51,366 records as High Risk and the 246 as Low Risk
 - There was a ballanced accuracty sore of approximatley 93.17%
 - The High Risk precision rate was only 9% with a reacll of 92%
 - The Low Risk had a precision rate of 100% and a recall of 94%

![EASY_2](https://user-images.githubusercontent.com/90698381/150699666-95bb2f75-bb9b-416d-a199-87a38bb8a175.png)

---
In summary of reviewing all the models that we used for this analysis the Easy Ensemeble Classifer had the highest rate of accuracy at 93.17% with a precistion rate of 9% for high risk candiates. The recall was also highest using this model. It would be our recomendation that this model be used for preforeming this type of analysis as it gives the most accurate results. 
