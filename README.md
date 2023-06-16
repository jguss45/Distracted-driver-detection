# Computer Vision for Distracted Driving Detection

## Objective
The goal of this notebook is to utilize neural networks to accurately classify driver activities related to distracted driving. The model will classify activities into the following categories:

- c0: Safe driving
- c1: Texting - right
- c2: Talking on the phone - right
- c3: Texting - left
- c4: Talking on the phone - left
- c5: Operating the radio
- c6: Drinking
- c7: Reaching behind
- c8: Hair and makeup
- c9: Talking to passenger

## Process Overview
This task will be approached in the following steps:

1. Transfer learning with the VGG16 base model will be applied as the initial approach.
2. A convolutional neural network (CNN) will be developed from scratch, utilizing the Adam optimizer.
3. Finally, the results of both approaches will be evaluated and compared.

## Dataset
The dataset used in this notebook can be accessed from the following link:
[Dataset Link](https://drive.google.com/file/d/1l1pN5ZQ6gELeWR8H1uZr0V05hP3gfpg_/view?usp=sharing)

By utilizing computer vision techniques and neural networks, this project aims to contribute to the development of effective systems for detecting and preventing distracted driving behaviors.

## Results
Model 1: A neural network created using transfer learning with the VGG16 model achieved an accuracy of 0.8801. Transfer learning allowed us to leverage the pre-trained VGG16 model's knowledge and parameters, resulting in a high level of accuracy.

Model 2: A convolutional neural network created from scratch using the Adam optimizer achieved an accuracy of 0.8136. While this model was trained from the ground up, it achieved a slightly lower accuracy compared to the transfer learning approach.

## Conclusion

In conclusion, the experiment comparing a custom-built neural network with a transfer learning approach using the VGG16 model demonstrated that transfer learning significantly reduces the effort required to achieve comparable performance, making it a valuable technique for leveraging pre-trained models in tasks with limited training data.
