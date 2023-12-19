# Image Interpolation

## A brief description of project or code -  
In this project, we are performing an image interpolation using three different image interpolation techniques (nearest neighbour, bilinear and bicubic interpolation). We have taken 3 different kind of images (Low level detail, medium level detail and high level detail). We are analyzing the robustness of the image interpolation techniques by performing the image interpolation on clear images and noise data/images as well . For noisy images, we are considering the different types of noises like Salt and pepper noise, Gaussian noise etc. This will give us insight onto how image interpolation techniques perform or behave in presence of specific noisy image data. To evaluate the final results, we are using PSNR (Peak signal to noise ratio) metric and also doing visual side by side comparison to see which technique is perfroming better.

The primary objectives of this project encompass a comprehensive analysis and performance 
evaluation of three distinct interpolation techniques—Nearest neighbor, Bilinear, and Bicubic—
across two key scenarios: clean/noise free images with varying levels of detail (low, medium, 
and high) and noisy input images. The project endeavors to evaluate the impact of noise on 
interpolation outcomes, investigating the suitability of each technique for noisy input images.
Also, the project seeks to analyze how the noise removal techniques (Mean, Geometric 
mean, Harmonic mean, Median and Gaussian) enhance the quality of subsequent interpolation results in case of noisy input images. Then, a comparative analysis will 
be conducted to ascertain the performance of interpolation techniques for noisy and noise free 
conditions. Through these objectives, the project aims to provide insights into the strengths and 
limitations of interpolation methods. The main workflow of the project is shown below Fig.1o

![image](https://github.com/amnrepo/DIP/assets/151793630/dd2d742c-1d37-416a-8d83-9c7d19df7355)  
## How to run the code (installation, dependencies, etc.) - 
Here we have jupitor notebooks (.ipynb) for each interpolation technique. Just simply run the code in "Microsoft vscode" or any other .ipynb platform of your choice.

## Special instructions or details on how to use the code - 
Nearest neighbour.ipynb - This file contains all the experiments related to nearest neighbour interpolation.

Bicubic_Interpolation.ipynb -  This file contains all the experiments related to Bicubic interpolation.

Bilinear_Interpolation.ipynb - This file contains all the experiments related to Bilinear interpolation.

Raw Data - This folder contains three original images which we are using in this project.  
