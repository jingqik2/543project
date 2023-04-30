# Processed IMDB WIKI Dataset

This GitHub repository contains a preprocessed IMDB WIKI dataset.

<p align="center">
  <img src="https://user-images.githubusercontent.com/34741145/51108233-75bac680-1817-11e9-8b79-6a1ee05d8aa4.png" />
</p>


## Introduction
IMDB WIKI dataset is the largest dataset of human faces with gender, name and age information. In this project, I preprocessed the entire dataset so that it can be used easily without any problems.


## IMDB WIKI Dataset
IMDB WIKI dataset is the largest publically available dataset of human faces with gender, age, and name. It contains more than `500 thousand+` images with all the meta information. All the images are in `.jpg` format. 

For more information about the dataset please visit [this website](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/).

## The Problem
The dataset is great for research purposes. It contains more than `500 thousand+` images of faces. But the dataset is not ready for any Machine Learning algorithm. There are some problems with the dataset. 

  - All the images are of different size
  - Some of the images are completely corrupted
  - Some images don't have any faces
  - Some of the ages are invalid
  - The distribution between the gender is not equal(there are more male faces than female faces)
  - Also, the meta information is in `.mat` format. Reading `.mat` files in python is a tedious process.


  - `Numpy=1.15.4`
  - `Scipy=1.2.0`
  - `pandas=0.23.4`
  - `cv2=4.0.0`

## Acknowledgments
I really thankful to these peoples for providing this amazing dataset
  - [IMDB-WIKI – 500k+ face images with age and gender labels](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/)
  - [yu4u/age-gender-estimation](https://github.com/yu4u/age-gender-estimation)

# 543project
