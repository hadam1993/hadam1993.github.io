## Adam Honts Projects and Tutorials

### Green Index Project

During the summer of 2017 I worked with Dr. Istvan Lauko and Jacob Beihoff on a project that gathered google street view images that spanned the streets of Milwaukee County. We created image processing code that analysed each of the images to find the pixels that contained green vegetation. The code used is based on the analysis of a green vegetation range of color, and variation around pixels that are within that color range. Vegetation pixels contain a high amount of variance due to shadows. This helps distinguish them between artifical objects such as street signs, automobiles, buildings, etc. We took the number of pixels that contained green vegetation and divided that by the total number of pixels in the image to create a "green index" for all of Milwaukee County. The resulting distribution was mapped and can be seen at the website below.

[MKE County Green Index Website](https://mke-green-index.netlify.com/)<br />
MKE County Green Index Website was created by Scott Ruprecht<br />
[Image Processing Code](https://github.com/hadam1993/MKECountyGreenIndex)

### Tutorial On How To Use Pytorch For Recognizing Handwritten Digits

The Tutorial located in my repository [MNIST_Tutorial](https://github.com/hadam1993/MNIST_Tutorial) was created to help others who are learning how to create Neural Networks using Pytorch. There is an emphasis on using your own data in this tutorial. The same methods to load your data into Pytorch can be reused for any image data that you want to use for your future projects involving Neural Networks. 

### NLP Projects

I am currently in a class for my Industrial Mathematics Degree which is focused on projects using Deep Learning. My group is focused on deep learning projects for Natural Language Processing. For example our first project was doing sentiment analysis using DistilBERT for it's classification encoding and then passing that encoding into a Shallow Neural Network to predict the movie review's sentiment (Negative or Positive). The projects code can be found on my repository [Industrial Math](https://github.com/hadam1993/Industrial_Math)

### Climate Change Competition

I am part of a Climate Change Competition with a group of 2 other graduate students, Joe Paulson and Andrew Wheaton, and a friend Scott Ruprecht, where we are creating a web visualization tool for climate data in North America. We are using Functional Data Analysis to cluster daily data collected from Jan 1st 1970 to Dec 31st 2017, that has the variables Min Temp, Max Temp, and amount of precipation. Results can be found at this [website](https://adamhonts.z14.web.core.windows.net/)
