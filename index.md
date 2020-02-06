## Adam Honts Blog

### Green Index Project

During the summer of 2017 I worked with Dr. Istvan Lauko and Jacob Beihoff on a project that gathered google street view images that spanned the streets of Milwaukee County. We created image processing code that analysed each of the images to find the pixels that contained green vegetation. The code used is based on the analysis of a green vegetation range of color, and variation around pixels that are within that color range. Vegetation pixels contain a high amount of variance due to shadows. This helps distinguish them between artifical objects such as street signs, automobiles, buildings, etc. We took the number of pixels that contained green vegetation and divided that by the total number of pixels in the image to create a "green index" for all of Milwaukee County. The resulting distribution was mapped and can be seen at the website below.

[MKE County Green Index Website](https://mke-green-index.netlify.com/)<br />
[Image Processing Code](https://github.com/hadam1993/MKECountyGreenIndex)

### Tutorial On How To Use Pytorch For Recognizing Handwritten Digits

The Tutorial located in the repository https://github.com/hadam1993/MNIST_Tutorial was created to help others who are learning how to create Neural Networks using Pytorch. There is an emphasis on using your own data in this tutorial. The same methods to load your data into Pytorch can be reused for any image data that you want to use for your future projects involving Neural Networks. 
