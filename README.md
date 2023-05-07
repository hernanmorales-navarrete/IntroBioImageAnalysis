# BioImage processing using Python

This class is an introduction to image analysis of biological images (i.e. microscopy images).

We will use python 3.x (as python2 is not supported anymore). Similarly, we will mainly use jupyter notebooks (.ipynb) for the courses taught at this course.

- Jupyter notebooks are very useful tools for learning programming because they provide a nice visual and interactive interface.
- You can see the results of your code live, instead of waiting till your script (.py) finishes running in a terminal.


To be able to use python and jupyter notebooks in your laptop, there are several options:

### OPTION 1: Google Colab (see https://colab.research.google.com/):

**Important Note: We highly recommend this option for participants with little programming experience.**

One option is to use Google Colab, for which you would need a Google account, which can be a personal gmail account or an institutional email account supported by Google (e.g. all Yachay Tech accounts are Google accounts). The advantage of using Google Colab is that all libraries are installed in a Linux server remotely, so we don't need to worry about compatibility issues, different operating systems, etc. The disadvantage is that Colab provides limited memory and computing resources as everything runs in a cloud, so you can only use it to process small datasets.

#### How do I test Google Colab?

1. Log into your Google account.

2. Open this notebook: [https://github.com/ciencialatitud0/EPIC_2/blob/main/Day0/my_first_notebook.ipynb](https://github.com/ciencialatitud0/EPIC_2/blob/main/Day0/my_first_python_notebook.ipynb)

3. Clic on "Open in Google Colab".

4. Run all the cells in this notebook. You can place the image of the worked example (which you can find here: https://github.com/ciencialatitud0/EPIC_2/blob/main/Day0/Cotopaxi_volcano.jpeg) or any other image into your "Colab Notebooks" folder in Google Drive.

5. If you see a plot of sin(x) vs. x and the image of the Cotopaxi volcano, your local Google Colab works.

- Please create a local copy of the code and required files by cloning the repository:
$ git clone https://github.com/hernanmorales-navarrete/IntroBioImageAnalysis.git

- If you use GoogleColab (see https://colab.research.google.com/):
	- Upload the notebooks and the image data (tiffs and jpgs)
	
- With Anaconda/Miniconda:
	- Create environment:
	$ conda create -n py38 python=3.8 anaconda -y
	- Activate the environment:
 	$ conda activate py38	
 	- Install a few extra libraries:
 	$ conda install scipy scikit-image tifffile
 	- Open a jupyter notebook
 	$ jupyter notebook


### 1. Introduction to Digital Images
- Brief intro to digital images

	* [Intro_DigitalImages.ipynb](Intro_DigitalImages.ipynb)
	* GoogleColab:
 		[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hernanmorales-navarrete/IntroBioImageAnalysis/blob/main/Intro_DigitalImages.ipynb)
 
 
### 2. BioImage Analysis with Python

- It is a step by step pipeline for segmenting cells in 2D fluorescence microscopy images (with labeled membranes)
	* [Image_analysis_tutorial.ipynb](Image_analysis_tutorial.ipynb)
	* GoogleColab:
	[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github//hernanmorales-navarrete/IntroBioImageAnalysis/blob/main/Image_analysis_tutorial.ipynb)


## Disclaimer
- These materials have been adapted from the original versions: 
    - "Python BioImage Analysis Tutorial:" https://github.com/WhoIsJack/python-bioimage-analysis-tutorial
    - "Python Workshop - Image Processing" : https://github.com/karinsasaki/python-workshop-image-processing
