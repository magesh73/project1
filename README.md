# Assignment 1B


What are Channels and Kernels (according to EVA)?
--

Kernels interchangebly known as Filter/Mask is a square matrix or image. that is slided on the original image to extract features, kernel usually have matrix size 1X1, 2X2, 3X3 which is run across the orignal image top to bottom and left to right to extract features.

Channels represnts Red,Green,Blue color in image, it can be compared to our eyes which have red blue green rods, which acts as recepotors when we see phyiscal objects, same way images constitute RGB colors called channels`

Why should we only (well mostly) use 3x3 Kernels?
--

In DNN when input image is convoluted using kernel, it produces feature maps, number of feature map increases with size of the kernel and the depth of the network, also larger the kernel size the number of parameters and computation power required increases, so keeping the size small helps to keep the parameter’s size small, by decreasing the feature maps while retaining the salient features


How many times do we need to perform 3x3 convolution operation to reach 1x1 from 199x199 (show calculations)
--
Code and Output in the image
-
![alt text](https://user-images.githubusercontent.com/11686582/56873564-c49c0d00-6a50-11e9-9794-a51042fb4e2a.png)



