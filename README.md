# Deep-CNN-for-Image-Colorization
Developed a Deep Convolutional Neural Network to convert a grayscale image to a coloured image.

First, a colored image is converted to grayscale and that is then converted back to RGB color. As this initial conversion loses information of the original image, we first execute K-means clustering to obtain the 4 main colors(cluster centers). 
Then, the pixels closest to these cluster centers are given that pixel value. For this, a Deep CNN was trained where the output of the CNN are the 4 pixel values which correspond to the cluster centers. 


