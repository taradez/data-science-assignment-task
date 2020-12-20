# Guide to my solution

My solution consists of two parts:
1. The notebook `start_here.ipynb` contains a walk through the analysis and explains a lot of the reasoning behind decisions that I made on the way.
2. There is also a python package `upday` along with a few unit tests and scripts. The scripts isolate the core functionality. More of the reasoning about this is in the notebook.

Requirements for my solution are in the `requirements.txt` file. You can install all requirements into your virtual environment by running
```
pip install -r requirements.txt
```
I didn't make the package installable and I assume that the `upday` folder is in your python search path.
Furthermore, I received data as a separate link. All scripts assume that the data file is at `./data/data_redacted.tsv`.

If you want to play with the `predict.py` script, there is an example article file to get you started.

# Assignment Task for Data Scientists

## Introduction
You are a Data Scientist working at upday, a news aggregator and recommender.

The engineering team at upday is gathering on a regular basis articles from all the Web. In order to provide a proper filtering functionality in the app, the articles need to be categorized.

You have at your disposal a pre-labelled dataset that maps different articles and their metadata to a specific category.

It's up to you now to help the company providing a solution for automatically categorizing articles.

## Assignment

The repository contains a dataset with some english articles and some information about them:

* category
* title
* text
* url

The purpose of the task is to provide a classification model for the articles.

## Instructions

You should make a pull request to this repository containing the solution. If you need to clarify any point of your solution, please include an explanation in the PR description.

What we expect:

* Results from your data exploration and an explanation about the solution you adopted.
* Documentation of the results of your model, including the choice of model(s), metrics adopted and the final evaluation.
* The training and evaluation code, ideally as separate scripts.

The solution should just perform better than random, also we expect you to use a model that is not just rules-based.

How to present the documentation and the code is up to you, whether to provide python scripts, jupyter notebooks or via a different mean. 


## Bonus

Show off your engineering skills. What steps would you take to productionize the model? 

We have listed some ideas below, but we would love to see the steps you would take. 
* Wrap your model into an API and document your instructions on how to test it
* Or.. Create a Docker image (or surprise us!) that can be used to run your code
* Or.. Include some unit tests in your training code
