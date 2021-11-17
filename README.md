# Metis-Deep-Learning-Project

## Saving the Bees, An image recognition approach

### Need
Bees are dying at an alarming rate. Yet, honey bees pollinate more than one third of our food supply and around 90% of all wild plants. Apiaries and beekeepers are fighting to keep their colonies alive and stave off biological and environmental stressors. As a tool for beekeepers to evaulate the status of their hives, I will build a supervised classification model using deep learning to determine a bee's health condition and provide insight to the threats that are challenging the crucial pollinator's existence. 

### Data 
The dataset I will be using to build this model is [The BeeImage Dataset: Annotated Honey Bee Images](https://www.kaggle.com/jenny18/honey-bee-annotated-images?select=bee_data.csv). This dataset contains 5,173 images of bees each one annotated with location, date, time, subspecies, health condition, caste, and whether or not the bee is carrying pollen. I will be classifying the bees by their health condition: 
   1. healthy
   2. presence of few varroa (small hive beetles)
   3. presense of varroa
   4. ant problems
   5. hive being robbed 

### Tools
* Sklearn for base modeling
* Keras for deep learning modeling
* Weights and biases for tracking workflow and model experiments
* Matplotlib and Bokeh for visualizing 

### MVP 
An MVP for this project could be a Keras Sequential model to classify a bee's health condition based on an image of it. 
