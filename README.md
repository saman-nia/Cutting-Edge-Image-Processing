# The-first-assignment-for-IPA
IPA 2017 Lab Exercise 1: 
I have done two major tasks including:

Image Transformations:

   Write functions to do each of the following to an input grayscale image of 'Lena':
      1. map a grayscale image to its 'negative image', in which the lightest values
         appear dark and vice versa.
      2. map the image to its 'mirror image', i.e., flipping it left to right.
      3. add or subtract a random value between [0,255] to every pixel in a
         grayscale image, then clip the resulting image to have a minimum value
         of 0 and a maximum value of 255.
      4. take the Lena image and break it into 16 * 16 non overlapping
         blocks. For each of the block compute the histogram and visualize them in a 
         4 by 4 grid (it should fit in a page).
         How would you compute the histograms if the image would have been in
         color? Are histograms invariant to translation, rotation and scale? For
         each of the blocks compute the mean value and show the image of size
         16 * 16 pixels produced (low resolution image).

 Canny Edges Detector:

   For this assignment you should implement Canny's edge detection algorithm as
   described in the class. Your implementation should take as input a grayscale
   image and the edge detection parameters. These are the partial derivative for the gaussian
   convolution and the gradient magnitude thresholds. The output should be a
   binary image.
   You should implement gaussian convolution as a sequence of horizontal and
   vertical convolutions (separability of the filter).
   The output of should NOT have fat edges! You should implement the hys-
   theresis mechanism that uses two thresholds. Your implementation of hysthere-
   sis should be efficient. You should submit what each part of your code does,
   and a comparison of the results with the already existing implementation. Show
   some results and discuss the effects of parameters. Please write a lot of com-
   ments in the source code, explaining what is going on.
