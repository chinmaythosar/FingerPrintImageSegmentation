# FingerPrintImageSegmentation
FingerPrint Image Segmentation using Unsupervised Machine Learning

This notebook takes an input fingerprint image and produces a segmented output of the same.

Segmentation includes the use of a vector of kernels. Different kernels with different features help to segment the image more efficiently. Finally the vector arrays are passed through K-clustering (Unsupervised Learning) to produce an output of '0's and '1's to give the final segmented output image. 0s and 1s can sometimes be interchanged depending on the image.

Note: When a pixel is to be viewed as fingerprint, the original pixel value from the image is displayed.
