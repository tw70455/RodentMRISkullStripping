% Rodent Brain-mask Segmentation tool


Detail description: 
The ‘RodentMRISkullStripping’ is a python module designed to provide an automatic rodent skull stripping. This module is a deep-learning-based framework, U-Net, to automatically identify the rodent brain boundaries in MR images. The whole framework is implemented using Keras with TensorFlow as the backend.


Plese install the following package before using RodentMRISkullStripping:
1) numpy, tensorflow, and keras
ex: conda install numpy tensorflow keras

2) SimpleITK
ex: conda install -c https://conda.anaconda.org/simpleitk SimpleITK

3) scikit-image
ex: conda install -c conda-forge scikit-image


Instruction:
1) install RodentMRISKullStripping
'pip install rbm'
2) Update the rbm
'pip install --upgrade rbm'
4) Give the input and output folder, you should put all the image in NIfTI format in the input folder .
'rbm -s 0.1 <input> <output>'
 For -s, the rbm will resample the input image resolution to 0.1*0.1 or 0.05*0.05
