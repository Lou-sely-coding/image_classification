## Image Classification

The task was to classify 10000 images into one of 10 categories. As a challenge, this needed to be done by creating ‘visual words’ for each of the images, 
and  then calculating the probability of a visual word (each feature) belonging to each cluster of the k-means algorithm. 
These probabilities form a histogram for each feature, and then for each image. 
In the end, the histograms for all training images are compared to the histograms of all test images, 
and the closest ‘match’ decides which label will be assigned to the test images.

For this assignment we also wrote our own k-mean algorithm. 
