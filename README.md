# Image Interpolation

## A brief description of project or code -  
In this project, we are performing an image interpolation using three different image interpolation techniques (nearest neighbour, bilinear and bicubic interpolation). We have taken 3 different kind of images (Low level detail, medium level detail and high level detail). We are analyzing the robustness of the image interpolation techniques by performing the image interpolation on clear images and noise data/images as well . For noisy images, we are considering the different types of noises like Salt and pepper noise, Gaussian noise etc. This will give us insight onto how image interpolation techniques perform or behave in presence of specific noisy image data. To evaluate the final results, we are using PSNR (Peak signal to noise ratio) metric and also doing visual side by side comparison to see which technique is perfroming better.
  
## How to run the code (installation, dependencies, etc.) - 
Here we have jupitor notebooks (.ipynb) for each interpolation technique. Just simply run the code in "Microsoft vscode" or any other .ipynb platform of your choice.

## Special instructions or details on how to use the code - 
Nearest neighbour.ipynb - This file contains all the experiments related to nearest neighbour interpolation.
Bicubic_Interpolation.ipynb -  This file contains all the experiments related to Bicubic interpolation.
Bilinear_Interpolation.ipynb - This file contains all the experiments related to Bilinear interpolation.
Raw Data - This folder contains three original images which we are using in this project.  
