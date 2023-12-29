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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .image-collage {
      display: grid;
      grid-template-columns: repeat(3, 1fr); /* Adjust the number of columns as needed */
      gap: 10px; /* Adjust the gap between images */
    }

    .image-collage img {
      width: 100%;
      height: auto;
      border-radius: 8px; /* Optional: Add rounded corners to images */
    }
  </style>
</head>
<body>

<div class="image-collage">
  <img src="https://github.com/SMSajadi99/Nerual-Network/blob/main/assinments/4/Method01/16x16-1500/face.jpg" alt="Image 1">
  <img src="https://github.com/SMSajadi99/Nerual-Network/blob/main/assinments/4/Method01/16x16-1500/bw_face.jpg" alt="Image 2">
  <!-- Add more images as needed -->
</div>

</body>
</html>


Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
 

 ### Photo compression by framing the photo and subtracting the average from the total (using tensorflow library)

 


 ### Standard PCA method (this method is without neural network)
