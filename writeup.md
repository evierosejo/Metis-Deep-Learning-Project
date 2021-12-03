# Classifying Bee Images using Keras
Evelyn Johnson

## Abstract
This project aims to classify images of bees by their health condition using Keras neural network models. Bees are essential. It is estimated that honey bees perform about 70 percent of the world’s pollination which supplies about 90% of the world’s nutrition, mainly in the form of fruits and vegetables, and account for 1 in every 3 bites of food. However, they are in danger. Scientists suspect bee colony collapse arises in three ways: parasites, pesticides and infections. Due to widespread use of pesticides, the bee’s natural defense mechanisms against the varroa mite have been weakened. Hives are also susceptible to thefts from ants and other insects. These affects are compounded by the climate crisis which decreases biodiversity through pesticide, deforestation, and natural weather events, limiting the availability of flowers. Traditionally beekeepers would determine their hives strength and health by looking inside the hive where many indicators lie. However, this can be time-consuming and disruptive to the colony. Detecting colony health from looking at bees outside of flying around the hive would give beekeepers a more complete understanding of the hive itself without disrupting it. The goal of this project is to classify bees in these categories, paving the way for more intelligent hive monitoring or beekeeping in general.

## Design
This project originates stems from the Kaggle dataset, [The Bee Image Dataset: Annotated Honey Bees](https://www.kaggle.com/jenny18/honey-bee-annotated-images). I began with a simple baseline model and then went onto to develop a CNN and VGG16 model with tuned hyperparameters. 

## Data
I acquired 4136 annotated bee images using OpenCV and pandas. The majority of the bees were classified as healthy, specifically 3384 of them. More than a quarter were classified to be infected with Varroa mites with another 11% experiencing issues with ants and the remaining bees either had a missing queen or their hive was being robbed. 

## Algorithms

*Feature Engineering*
- Transformed images into numpy arrays
- Annotating bee images using 
- Keras image preprocessing 

*Models*
- Baseline
- Simple CNN
- VGG16 with imagenet weights

**Final Neural Network Model using transfer learning with VGG16:** Weighted with Imagenet
   - Training Accuracy: 0.9888
   - Training Loss: 0.0294
   - Val Accuracy: 0.9070
   - Val Loss: 0.5878

**Holdout** 
   - Accuracy: 0.9237
   - F1: 0.9211

## Tools
- OpenCV, Numpy and Pandas for data manipulation
- Scikit-learn for metrics
- Google Colab for cloud computing
- Keras for modeling
- Matplotlib and Visualkeras for visualization

## Communication
In addition to the slides and visuals presented, I am looking to post a blog on Medium. 
