# 3D_Medical_Image_Classification

The following repo uses 3D Convolution Neural Network to Detect if the following CT Scans of the patient shows Viral Pneumonia or not. 3D covolution was used in this case because the images had a depth factor which cannot be captured with a simple 2D Conv.

## 3D Convolution
Convolutions are carried out via a three-dimensional filter in a 3D CNN.
In contrast to a 2D CNN, which only allows for sliding in two dimensions, the kernel can move in three directions.

### An example of 3D Convolution NN
![image](https://user-images.githubusercontent.com/85514219/223844078-cde8df64-91f7-4885-abbd-d89a47122626.png)

## Model Training

The models were trained on 2 occasions:
1. 100 epochs - Initial Training
2. 20 epochs - Seeking Improvemnet

Both the models are made available. Retrain it as per your requirement.

## Data
Since it was an experiment, the repo used a smaller version of the Dataset consiting of only 200 samples in total. A larger dataset is available which consists of 1000 samples.

## DEpendencies
1. TensorFlow
2. Keras
3. Nibable (A library used for Neuro-Imaging cases)
