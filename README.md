# AIDI1002_final_project
Final project for course AIDI1002 Machine Learning Programming, team members: Hugo Garcia $ Jesal Patel

Research Paper 
https://arxiv.org/abs/2210.00586
Github repository used: https://github.com/aliborji/GFW


The original paper performs a comparison between 3 image generated models, Stable Diffusion, Midjourney and DALL-E 2, and score their performance using the FID score methodology in human faces.

It uses 4 different datasets, 1 of real faces images, and 1 for image generated faces for each of the models

The purpose of this project is to expand the exposure of the original work into animal images to compare the performance of the open-source model Stable Diffusion to generate cat images and human faces

This project uses real images obtained from Google Image https://storage.googleapis.com/openimages/web/index.html
Instructions to download images can be located in https://sharmaji27.medium.com/easiest-way-to-download-data-from-the-open-image-dataset-553dccfb92d8

To replicate this results use the datasets contained in this repository and store them in your local device
A Hugging face Access token is necessary to access to the Stable Diffusion model, once created, write it in cell 3 of StableDiffusion_Gen.ipynb

In order to replicate the results of the original paper, find the datasets used in https://drive.google.com/file/d/16BXO1fgN08UGLLeA5ZNU9bhwAkcAOdci/view
and run the code in Scoring_LOCAL.ipynb, this is a light version of the code used in the original paper, adapted to be used in a Jupyter notebook environment and local device storage
