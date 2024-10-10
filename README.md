# Skin-Mole-Analysis---Border-and-Color
Due to the large size of the original notebooks (approximately 150MB each), the notebooks have been split into smaller sub-notebooks for easier management and loading. Each main notebook has been divided into 3-4 sub-notebooks, the content remains organized and accessible. (Segmentation, calculating Box counting dimension, converting to Lab, XYZ, HSV and YCbCr color space, analysis of the different channels and statistical analysis of the acquired results).

The hausDim function is written by Alceu Ferraz Costa. It is converted to python for this analysis. 
## Features
- **Segmentation of moles**: Extract the mole region from the background.
- **Calculating Box-counting dimension**
- **Statistical Analysis**: Calculate statistical differences between benign and malignant moles based on box-counting dimensions.
- **Color Space Analysis**: Feature extraction from different color spaces to analyze properties of skin moles.
- **Statistical Analysis**: Calculate statistical differences between benign and malignant moles based on color characteristics.

## Color Spaces Used
- HSV (Hue, Saturation, Value)
- Lab (L*, a*, b*)
- XYZ (X, Y, Z)
- YCbCr (Y, Cb, Cr)

## Usage
To run the analysis:

Clone the repository.
Open the desired Jupyter notebook(s) in your local environment.
Follow the instructions in each notebook to reproduce the analysis. 
Be careful with file paths. 

## Dependencies
Make sure to have the following libraries installed:

numpy
pandas
matplotlib
scikit-image
opencv-python
