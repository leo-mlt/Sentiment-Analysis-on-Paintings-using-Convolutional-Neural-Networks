# Sentiment-Analysis-on-Paintings-using-Convolutional-Neural-Networks

## Overview on the project

The focus of the project is to try to predicting human’s emotion looking at a painting.
Psychological studies have already demonstrated that humans’ emotion reflections vary with different visual stimuli, such as images and videos. 
Inspired by these studies, computer scientists began to predict the emotional reactions of people given a series of visual contents. However, compared to semantic-level image analysis, analyzing images at affective-level is more difficult, due to the two challenges of the complexity and subjectivity of emotions. Image emotion is related to complex visual features from high-level to low-level for both global and local views. Low-level visual features from the local view, such as color, shape, line and texture, were used to classify image emotions. There are some studies about the role some components that can determine the emotions inspired in the persons. For instance, Joshi et al. indicated that image emotion is highly related to image aesthetics for artistic works, Machajdik and Hanbury suggested that image emotion can be significantly influenced by semantic content of the image. They combined high-level image semantics from the global view with Itten’s art theory on relevance of colors to recognize image emotion.
Given this overview of the scenario, we want to understand if a Articifial Neural Network, and more specifically a Convolution Neural Network (CNN), which is specialized
on the classification and analysis of the images, is able to predicts the emotion related
to paintings

## Datasets 

- **WikiArt Dataset**: this is a dataset in which are collected around 81,000 painting made by different painters who have been part different artistic currents. The
dataset has a dimension of 25.4 Gb and can be downloaded on this [link](https://drive.google.com/file/d/1vTChp3nU5GQeLkPwotrybpUGUXj12BTK/view)
- **Artemis Dataset**: this is a dataset in which different persons, for each paint, expresses her/his emotion looking to the paint and brief description of her/his mood. The dataset has a dimension of 68 Mb and can be downloaded at this [link](https://www.artemisdataset.org/#dataset)

## Implementation Details
The project was implemented first in a local pc with GPU Support (RTX GeForce 3060, 6GB RAM) and then it is loaded on github
