# Anyone_sprint2

This project builds and extends on the foundation of the Sprint1 (NBA data) project. This time, however, instead of analyzing the data directly from the API, you will need to use the new tools in your arsenal like various regressions, feature engineering, modeling and of course the trusty NumPy from Sprint 1.

## Goals of this project

- Learn how to define a prediction task
- Selecting evaluation metrics and baseline models
- Perform feature engineering and standarization
- Training and using predictive models: Univariable and Multivariate Linear Regression, Classification
- Understand how Gradient Descent works by implementing a Linear Regressor in python

## Install

You can use `Docker` to easily install all the needed packages and libraries:

```bash
$ docker build -t sprint2 -f Dockerfile .
```

### Run Docker 

```bash
$ docker run --rm -it -p 8888:8888 -v $(pwd):/home/app/src sprint2 bash 
```

## Run Project

It doesn't matter if you are inside or outside a Docker container, in order to execute the project you need to launch a Jupyter notebook server running:

```bash
$ jupyter notebook --ip 0.0.0.0 --port 8888 --allow-root
```

Then, inside the file `AnyoneAI_Project2.ipynb`, you can see the project statement, description and also which parts of the code you must complete in order to solve it.
