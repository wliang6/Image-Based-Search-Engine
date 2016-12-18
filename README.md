# Image-Based-Search-Engine

We define the descriptor for the images with shape, texture or color. The image
descriptor used is a color histogram which has red, green, blue channels. We will index the dataset by applying the descriptor to each image in the dataset to extract features. Indexing an image allows us to output a feature vector which is the numerical value of the image. With the feature vectors, we can compare the similarity of two images by using a distance metric such as the chi-squared distance. This is done between the query image and each individual images in the dataset which will then rank the images based on the similarity distance. Lastly, with the rankings, we can check the results to see if the corresponding images are ranked closest to the query images.

Check Report.pdf for additional details. 
