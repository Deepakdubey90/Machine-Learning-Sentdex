# Intro - Machine Learning 

> This repository is for people starting with machine learning with **Python** trying to understand the basic mathematics. In this particular repository you can find the tutorials from [sentdex](https://www.youtube.com/user/sentdex)
> **Jupyter Notebooks** allow you to play with training data (Quandl etc.), different algorithm configurations and see results on the fly directly in **your browser**.
> Resources will be given at the very bottom of this document!

The purpose of this repository is to give you a holistic understanding of the machine learning concepts

## TLDR

![TLDR](Images/SupVsUnsup.jpeg)

The main difference between the two types is that supervised learning is done using a so called **ground truth** 
which means we have prior knowledge of what the output values for our samples should be. 

The goal of supervised learning is to learn a function that, given a sample of data and 
desired outputs, best approximates the relationship between input and output observable in the data. 

Unsupervised learning, on the other hand, does not have labeled outputs, so its goal is to infer the 
natural structure present within a set of data points.

## Supervised Learning

In supervised learning we have a set of training data as an input and a set of labels or "correct answers" for each training set as an output. 
Then we're training our model (machine learning algorithm parameters) to map the input to the output correctly (to do correct prediction). 
The ultimate purpose is to find such model parameters that will successfully continue correct input→output mapping (predictions) even for new input examples.



## Prerequisites

#### Installing Python

Make sure that you have **[Python installed](https://realpython.com/installing-python/)** on your machine. You can check your Python version by running:

```bash
python --version
```

You might want to use [venv](https://docs.python.org/3/library/venv.html) standard Python library
to create virtual environments and have Python, `pip` and all dependent packages to be installed and 
served from the local project directory to avoid messing with system wide packages and their 
versions.

#### Installing Dependencies

Install all dependencies that are required for the project by running:

```bash
pip install -r requirements.txt
```

#### Launching Jupyter Locally

You can run all projects by installing Jupyter locally. But if you want to launch [Jupyter Notebook](http://jupyter.org/) locally you simply type in the following command into the terminal:

```bash
jupyter notebook
```
After this Jupyter Notebook will be accessible by `http://localhost:8888`.

## Datasets

The list of datasets that is being used for Jupyter Notebook demos may be found in [data folder](Data).