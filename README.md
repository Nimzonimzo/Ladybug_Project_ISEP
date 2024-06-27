# Ladybug Classification Project

School project conducted in collaboration between Thomas FERRANDIS and Steven Bradley, focusing on the automatic classification and spot counting of ladybugs, with a focus on Harmonia axyridis species.

This project involves analyzing images of ladybugs to classify them into different categories based on their visual features.

European and Asian ladybugs have distinct visual differences. European ladybugs typically have a larger number of black spots on a red background, usually around 7 and often with some spots merging together. In contrast, Asian ladybugs tend to have fewer and more defined spots, often with distinct black M-shaped markings on a red or orange background. It's important to note that Asian ladybugs may display more variability in spot patterns and colors compared to the European Ones.


## Overview

This collaborative project aims to automate the study of ladybug populations. The goal is to develop a machine learning approach that can automatically detect the ladybug species and count the number of spots on an image.

We were given a dataset of 100 ladybugs images and their associated vectors and we had to find a way to sort and predict their type (European or Asian.) Initially, the images undergo preprocessing steps such as background removal using image segmentation techniques. Once the backgrounds are removed and the image is filtered, we count the numbers of spots on the shell and use a decision tree to attempt to predict the kind of ladybug we are facing.

The images are also subjected to the K-means clustering algorithm after to group them based on similarities. Each cluster representing a distinct visual pattern observed across the ladybug images.
By categorizing ladybugs into clusters, the project aims to provide insights into the diversity of ladybug appearances in the dataset.



## Objectives
1. **Species Identification:** Implement a machine learning model to automatically identify ladybug species, with a focus on distinguishing Harmonia axyridis from other species.
2. **Spot Counting:** Develop algorithms to count the number of spots on ladybug images, providing valuable data for population analysis.
3. **Automation:** Create an automated pipeline for processing ladybug images, from data input to species identification and spot counting.

## Technologies Used
- Python (OpenCV, scikit-learn, matplotlib, etc.)
- [Jupyter Notebook](https://jupyter.org/) - Used for interactive and collaborative development.
- [Machine Learning Libraries] - Utilized for training and deploying the ladybug classification model as well as the decision tree.

## Screenshots

### Clustering
![Screenshot_4](https://github.com/BonelessCode/Ladybug_Project_ISEP/assets/59204911/768afd53-af27-4514-8e96-f6f2fd973578)
![Clusters](https://github.com/BonelessCode/Ladybug_Project_ISEP/assets/59204911/b14a9a15-391f-4aa9-888d-1bfc04d51501)
![Cluster](https://github.com/BonelessCode/Ladybug_Project_ISEP/assets/59204911/6ed3bf52-a8be-4e4c-8c45-1da58a3152c2)

### Spot Couting / Species identification
![Screenshot_1](https://github.com/BonelessCode/Ladybug_Project_ISEP/assets/59204911/7027e6a9-cc9d-41bb-b352-d1d7eadb85ad)
![1](https://github.com/BonelessCode/Ladybug_Project_ISEP/assets/59204911/33be55e6-a3e4-4dc2-8917-0b64d8e7b46b)
![Screenshot_2](https://github.com/BonelessCode/Ladybug_Project_ISEP/assets/59204911/7024a44e-7d7a-4142-83ff-c938f8102f3f)
![2](https://github.com/BonelessCode/Ladybug_Project_ISEP/assets/59204911/3b4f7020-869b-4e91-9f2b-5bcd273c3418)
![Screenshot_3](https://github.com/BonelessCode/Ladybug_Project_ISEP/assets/59204911/ff287426-dd63-454b-9e97-ff093356c638)
![3](https://github.com/BonelessCode/Ladybug_Project_ISEP/assets/59204911/2212cfb0-f490-462a-99b3-ec69a61d1f11)











