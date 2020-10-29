# Detection_Image_defects_or_changes_using_Python_and_OpenCV
# STEPS :
1. load the two input image(original and defected).

2. Convert the images to grayscale image (i.e., from RGB to gray).

3. Compute Structural Similarity Index (SSIM) between two images.

4. Threshold the difference image, followed by finding contours to obtain the regions of the two input images that differ.

5. loop over the contours also loop to get the largest contour should be the new detected difference).

6. Resultant image where defect detected
