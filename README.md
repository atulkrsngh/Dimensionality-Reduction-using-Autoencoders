# Dimensionality-Reduction-using-Autoencoders
Autoencoders for dimensionality reduction and noise removal from both tabular and image data

We can use an autoencoder for dimensionality reduction by separating it out into 2 parts:  
Encoder  
Decoder  

Encoder can successfully reduce dimensionality of the original data by taking combinations of the original features.    

Used autoencoders in MNIST dataset for :   
Attempting to recreate input images in the output with less dimensions  
Removing noise from input images to accurately reproduce output  

In the autoencoder for tabular data :  
The table is the average consumption of 17 types of food in grams per person per week for every country in the UK  

The table shows some interesting variations across different food types, but overall differences aren't so notable due to huge number of dimensions.  
Used autoencoder to get some insights of the data after reducing the dimensions. 
