1. We create a disparity matrix to identify the closest (most similar) pixels in two perspectives of a single image captured by two different cameras from 2 positions. 
2. Once we find the most similar pixel - we find the horizontal displacement of the pixel between the left and the right perspectives.
3. Things that are closer will have higher displacement as compared to things that are further away.
4. We cluster the points that we find in the matrix to obtain a undefined number of objects in the image.
5. We assign the cluster values to the pixels and obtain the different depth and the corresponding objects at those depths in the image.


