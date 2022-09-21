# trainingDataAugmentation
1. Jupyter notebook scripts of augmenting the manually labeled Au tetrahedra and patchy nanoprism TEM images.  
2. The augmented training datasets of Au tetrahedra and patchy nanoprism used in the publication.   

Date: 09/2022   
For more information about the project, algorithms, and related publications please refer to the [Chen Group website](https://chenlab.matse.illinois.edu/).

Reference
---------------
If you find our approach useful, please cite: L. Yao, H. An, S. Zhou, A. Kim, E. Luijten, Q. Chen, "Unveiling the synthesis‒nanomorphology relationships of heterogeneous nanoparticles, hybrids, and 3D polymer films using generalizable shape fingerprints and unsupervised learning", nanoscale (2022)

Getting started
---------------
1. The augmented training datasets in TIFF format are zip-compressed and stored under folder "training data/".  
2. The manually labeled images, coresponding labels, and the augmentation codes are under folders "tetrahedra/" and "patchy nanoprism/".  
3. The jupyter notebook codes (augmentation.ipynb) can be opened by jupyter notebook in Anaconda. The require packages include JupyterLab, TensorFlow, OpenCV, and Pillow. The codes are tested with Python 3.7 without GPU.  
4. The code reads labels and images under folder "manual label/" and output labels and images into folders "label/" and "train/".  

Note
---------------

Revisions
---------------
