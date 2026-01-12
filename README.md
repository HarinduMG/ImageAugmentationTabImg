# ImageAugmentationTabImg
a code I used to create images with data from tabular forms into a single image, used in medical context

## Explanation 

Code reads a template that has already been made using greyscale values, and replaces those regions with data from tabular data, saving the image as a single file. Code should be able to hande any rectangular regions as long as the colors match. Any shape that is not rectangular would not work properly

## Warning

The main code for the function shown in the notebook which was CPU based, has been converted through AI to a GPU based code for speed. The GPU based code runs much faster and can easily convert thousands of images to the required format.
