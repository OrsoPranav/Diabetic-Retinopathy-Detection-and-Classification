# Diabetic-Retinopathy-Detection-and-Classification

This was part of our college courses' data science project. Diabetic retinopathy, a complication of diabetes mellitus that affects the retina, is the leading cause of preventable blindness. Early detection and timely treatment are crucial for preventing vision loss.

![image](https://github.com/user-attachments/assets/c4127443-7fa6-44a3-8e2c-9f4d2efaa6a6)

In total, the dataset we have chosen, https://www.kaggle.com/datasets/tanlikesmath/diabetic-retinopathy-resized, comprises 35216 images. This dataset includes pictures of both the left and right eye retinas of the subjects under consideration.

![image](https://github.com/user-attachments/assets/d3b17662-3a94-49f4-9cc1-235a9a6cda62)

The distribution of images is as follows: No diabetic retinopathy: 25810 images Mild diabetic retinopathy: 5292 images Moderate diabetic retinopathy: 2443 images Severe diabetic retinopathy: 873 images Proliferative diabetic retinopathy: 708 images Our project was divided into 3 phases:

1. Visualization
2. Preprocessing
3. Model Making
Visualization: 
Statistics:

![image](https://github.com/user-attachments/assets/0b122b3f-6d8a-42f1-873f-d9a693c9b0cf)

PCA Visualization:

![image](https://github.com/user-attachments/assets/14995632-1d56-4fc8-8d10-84eb333ba8f7)

Scatter Plot of Image Pixel Values:

![image](https://github.com/user-attachments/assets/9c24aae7-514d-4943-9f4c-716591a1599d)

Pixel Intensity Plots:

![image](https://github.com/user-attachments/assets/ccb2dde1-e073-4140-a550-75fd0c3db516)

3D Pixel intensity plots:

![image](https://github.com/user-attachments/assets/e7179979-6cf8-443a-8d5e-88dc37f51109)

Preprocessing: 

CLAHE ( CONTRAST LIMITED ADAPTIVE HISTOGRAM EQUIVALENCE ):

![image](https://github.com/user-attachments/assets/72b71b08-e8a2-4a17-b3ba-2ed83cf68edf)

KRISH CROPPING ( OWN DISCOVERY, WE PERFORMED 8 DIFFERENT KERNEL'S CONVOLUTIONAL OPERATIONS ON IMAGES ):

![image](https://github.com/user-attachments/assets/b11907be-df0e-48f0-b69f-dddae5b1fe54)

CANNY EDGE DETECTION:

![image](https://github.com/user-attachments/assets/5781c620-0e57-4a7b-bf67-cff5c7be0155)

GAUSSIAN CIRCLE CROP ( OWN DISCOVERY, KEPT CIRCLE AS SAME SIZE FOR ALL IMAGES FOR CONSTANCY ):

![image](https://github.com/user-attachments/assets/91ec2753-46bb-475a-8f4b-96443b3c0bf4)

Modelling: Checked Multiple models including DENSENET121:

![image](https://github.com/user-attachments/assets/f4151c48-fce9-4bc0-a9bd-97a4c92c8cb6)

INCEPTIONV3:

![image](https://github.com/user-attachments/assets/b238ac2f-9658-4b78-9818-47aab63b86ee)

MOBILENET:

![image](https://github.com/user-attachments/assets/d4579b3e-9247-43e9-bae1-0aa3135c82d2)

EFFICIENTB3:

![image](https://github.com/user-attachments/assets/48327cb1-2193-4eb2-aca5-8964f8af7780)

Based on all our approaches, we got high accuracy with MobileNet architecture with (Gaussian Blur and Circle Crop) Preprocessing ! Technique.
