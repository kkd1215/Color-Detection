# Color Detection

In this color detection project, we are going to build an application through which we can automatically get the name of the color by clicking on them. So for this, we will have a data file that contains the color name and its values. Then we will calculate the distance from each color and find the shortest one.

# The Dataset

Colors are made up of 3 primary colors; red, green, and blue. In computers, we define each color value within a range of 0 to 255. There are approximately 16.5 million different ways to represent a color. In our dataset, we need to map each color’s values with their corresponding names. We are using a dataset that contains RGB values with their corresponding names.

The [colors.csv](https://github.com/kkd1215/Color-Detection/blob/main/colors.csv) file includes 865 color names along with their RGB and hex values.

# Libraries used :
1. [OpenCV](https://opencv.org/)

    OpenCV-Python is a library of Python bindings designed to solve computer vision problems. OpenCV-Python makes use of Numpy, which is a highly optimized library for numerical operations with a MATLAB-style syntax. All the OpenCV array structures are converted to and from Numpy arrays.

2. [Numpy](https://numpy.org/)
    NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices. It is an open source project and you can use it freely. NumPy stands for Numerical Python.

3. [Pandas](https://pandas.pydata.org/)
    Pandas is mainly used for data analysis. Pandas allows importing data from various file formats such as comma-separated values, JSON, SQL, Microsoft Excel. Pandas allows various data manipulation operations such as merging, reshaping, selecting, as well as data cleaning, and data wrangling features.

# Instructions to use :

Just run the jupyter notebook and input the path of the image
