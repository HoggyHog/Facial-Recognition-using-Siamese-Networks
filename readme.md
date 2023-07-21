#INTRO

This repo contains the code base and the images related to my self project - Facial Recognition App using Contrastive Learning, 
by making positive and negative samples of the images and using a L1 Distance on the embeddings returned from a model based on the research paper given below. And then finally passing it through a binary classifiere and training it in a supervised manner.

Model based on the research paper -> https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf

##REPO DESCRIPTION

FACIAL RECOGNITION APP.ipynb -> entire code base of the project with comments to help follow along

lfw -> folder container images of celebrities to help make the negative images

data-> working folder which will contain 3 subfolders of
	anchor -> images of target
	pos-> images of target
	neg -> images of other people

application_data-> going to be using this for validation of the model
