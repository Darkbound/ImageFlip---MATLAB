ImageFlip
=========

This MATLAB code is reading the image resulting in a 3 dimensional matrix which is then divided into 3 new matrices, one for each color.
Each matrix is then rearranged, we take columns with a width of 100 pixels and flip them the result gives a new column of 100 pixels,
but now columns from 1 to 50 have swapped their place with columns from 51 to 100, we do the same with the rows. The result is, the same image,
but shuffled, with squares of 50x50 pixels.
