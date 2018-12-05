# WorldMachineLearningSummit_2018
Repo for [World Machine Learning Summit](https://1point21gws.com/machinelearning/bangalore/index.html) - "Image Segmentation using Deep Learning"


Instructors and Overview
-----------

- [Mohit Tare](https://github.com/MohitTare)- Deep Learning Engineer at Dell
- Saurabh Jha -  Deep Learning Architect at Dell

This repository will contain the teaching material and other info associated with our workshop
at [World Machine Learning Summit](https://1point21gws.com/machinelearning/bangalore/index.html) held on 6th December 2018

We have the workshop divided into 3 parts
1. Introduction to PyTorch
2. Exploring Medical Images
3. Semantic Segmentation using Deep Learning


Obtaining the Tutorial Material
------------------

1. If you have a GitHub account, it is probably most convenient if you clone or
fork the GitHub repository. You can clone the repository by running:

```bash
git clone https://github.com/deepSattva/WorldMachineLearningSummit_2018

```

2. If you are not familiar with git or don’t have an
GitHub account, you can download the repository as a .zip file by heading over
to the GitHub repository (https://github.com/deepSattva/WorldMachineLearningSummit_2018) in
your browser and click the green “Download” button in the upper right.


Please note that we may add and improve the material until shortly before the
tutorial session, and we recommend you to update your copy of the materials one
day before the tutorials. If you have an GitHub account and cloned the
repository via GitHub, you can sync your existing local repository with:

```bash
git pull origin master
```

If you don’t have a GitHub account, you may have to re-download the .zip
archive from GitHub.

Installation Notes
------------------

1. Using Anaconda Distribution 

A relatively painless way to install all the requirements is to use a Python distribution
such as [Anaconda CE](https://www.anaconda.com/download/), which includes
the most relevant Python packages for science, math, engineering, and
data analysis; Anaconda can be downloaded and installed for free
including commercial use and redistribution.
The code examples in this tutorial should be compatible to Python 3.6-3.7

2. Manually installing additional packages

This tutorial will require recent installations of

- [PyTorch](https://anaconda.org/soumith/pytorch) ```conda install pytorch torchvision -c pytorch```
- [Scikit Image](https://anaconda.org/anaconda/scikit-image) ```conda install -c anaconda scikit-image ```
- [Seaborn](https://seaborn.pydata.org/)```pip install seaborn ```
- [nibabel](http://nipy.org/nibabel/) ```pip install nibabel ```
- [nilearn](https://nilearn.github.io/) ```pip install nilearn ```
- [pydicom](https://pydicom.github.io/pydicom/stable/getting_started.html) ```pip install -U pydicom ```
- [medicaltorch](https://medicaltorch.readthedocs.io/en/stable/index.html) ``` pip install medicaltorch ```
- [tensorboardX](https://github.com/lanpa/tensorboardX) ``` pip install tensorboardX ```

Installation of PyTorch will take time and that is the main Library used in the workshop so its highly recommended to install it before you attend the workshop
The last one is important, you should be able to type:

    jupyter notebook

in your terminal window and see the notebook panel load in your web browser.
Try opening and running a notebook from the material to see check that it works.


### Additional instructions
Although not required, we also recommend you to update the required Python
packages to their latest versions to ensure best compatibility with the
teaching material. Please upgrade already installed packages by executing

- `pip install [package-name] --upgrade`  
- or `conda update [package-name]`


Data Downloads
--------------

1. The data can be downloaded from [here](https://drive.google.com/drive/folders/1KN-iIR5qcykmkUY8eqWXaldu4ujfRNsb?usp=sharing).
2. Make a new directory called `Data` inside the repo parent directory and copy rest of the data directories there 


Citation- 
The data uploaded above is taken from below site and uploaded just for ease of access 
 - https://github.com/muschellij2/Neurohacking_data
 - https://challenge2018.isic-archive.com/
 Note: The full ISIC dataset can be downloaded easily by using the ISIC Archive dowload package from [here](https://github.com/GalAvineri/ISIC-Archive-Downloader)

Acknowledgments
--------------
  - https://medium.com/@taposhdr/medical-image-analysis-with-deep-learning-i-23d518abf531
  - https://datashare.is.ed.ac.uk/bitstream/handle/10283/2216/NiftivsAnalyze_MVH_140714.pdf?sequence=1&isAllowed=y
  - https://github.com/yuanqing811/ISIC2018
  - https://github.com/milesial/Pytorch-UNet/tree/master/unet
  


