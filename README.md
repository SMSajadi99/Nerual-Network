# Nerual-Network

# Assignment 
+ HomeWork 01
  
    + HomeWork 01 (optional)
+ HomeWork 02


## Home Work 04 (Image compression and reconstruction with Neural Network)
In this exercise, we want to try to compress a photo with 3 methods and reconstruct it with a neural network :)

1. [Photo compression by framing the photo and subtracting the average of each frame (using sklearn library)](https://github.com/SMSajadi99/Nerual-Network/blob/main/README.md#photo-compression-by-framing-the-photo-and-subtracting-the-average-of-each-frame-using-sklearn-library)
2. [Photo compression by framing the photo and subtracting the average from the total (using tensorflow library)](https://github.com/SMSajadi99/Nerual-Network/blob/main/README.md#photo-compression-by-framing-the-photo-and-subtracting-the-average-from-the-total-using-tensorflow-library)
3. [Standard PCA method (this method is without neural network)](https://github.com/SMSajadi99/Nerual-Network/blob/main/README.md#standard-pca-method-this-method-is-without-neural-network)

 ### Photo compression by framing the photo and subtracting the average of each frame (using sklearn library)

In this method, we try to create boxes in the shape and in the same box, we create boxes whose average is placed instead of the matrix of the same box, and Sklearn library tries to reconstruct it.

The main photo is as follows:

![Image Collage](https://github.com/SMSajadi99/Nerual-Network/blob/main/assinments/4/Method01/16x16-1500/face.jpg)

The Gray photo is as follows:

![Image Collage](https://github.com/SMSajadi99/Nerual-Network/blob/main/assinments/4/Method01/16x16-1500/bw_face.jpg)


In the table below, the parameters that should be required for training the network are given:

Max Iter | Hidden Layer Sizes | Test Size | Random State
--- | --- | --- | ---
5000 | 400,200 | 0.05 | 42

Now we try to display the results and outputs with 3 different boxes:

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
 

 ### Photo compression by framing the photo and subtracting the average from the total (using tensorflow library)

 


 ### Standard PCA method (this method is without neural network)
