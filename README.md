# scbcn17 Customer Segmentation Workshop
This workshop will be part of the [Software Craftsmanship 2017 conference](http://softwarecraftsmanshipbarcelona.org) in Barcelona, October 2017.

## Workshop Description
Let's learn about useful Machine Learning algorithms, invoking them from common data science libraries.

The workshop session starts with a brief introduction to ML (slides to be released after the workshop) and the different approaches we can apply. After that we will use this repository to practice exploring a real dataset, cleaning and optimizing the data, and using ML algorithms to find hidden insights.

No need to know about maths, machine learning, nor python; this is an introductory but profitable workshop!

## Requirements
You will need [docker](https://www.docker.com/) already installed in your machine.

We'll use a *docker container* that contains a data science stack, [jupyter/scypy-notebook](https://hub.docker.com/r/jupyter/scipy-notebook), so you don't need to install anything locally.

This container comes with the tools we need for this workshop:
- **jupyter**: A web IDE that edits notebooks
- **python3**: The language that will use as interface 
- **numpy** and **pandas**: Python libraries to work with matrices and datasets
- **matplotlib**: Python ploting library to display data
- **scikit-learn**: Library with lots of Machine Learning algorithms

## Dataset
The workshop uses a [dataset released by ulabox](https://github.com/ulabox/datasets) in september 2017, that includes real purchases on ulabox website.

## Preparing and running this workshop
1. docker pull jupyter/scipy-notebook
2. git clone git@github.com:ulabox/datasets
3. git clone git@github.com:liopic/scbcn17-customer-segmentation
4. cp datasets/data/*.csv scbcn17-customer-segmentation/
5. cd scbcn17-customer-segmentation
6. ./jupyter.sh
7. Open the link in your browser and open the Workshop.ipynb file

