# Learning Diffeomorphism based Data Augmentation

This is my Master's capstone/final project   

In this project we aim to propose a new data augmentation for kidney tumors using Diffeomorphism.

In following milestone presentations you can find following information:

1) Overview presentation - What is the diffeomorphism and how it is related to the new data augmentation technique that we aim to develop. Also this project presents some related work.
2) Milestone 1 - Overview of the project and example of diffeomorphism, Architecture of the project, Information on the dataset that contains Kidney scans of 300 patients1, and also converted 3D scans to 2D images.
3) Milestone 2 - A short overview of what my project, how we build masks of tumors, and sample pairs of those masks using KNN, and then a short description of what VAE model is and layers of my model, and this presentation also includes sample results.

train_vanilla.py -> Trains the model for augmenting dataset

Vanilla_VAE.py -> VAE model used, defined it's layers

Constants.py -> Defined constants used all the files
