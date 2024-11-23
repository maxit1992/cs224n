# Assignment 2

## Introduction

This assignment reviews the mathematics behind Word2Vec and builds a neural dependency parser using PyTorch. The assignment has 3 parts. In Part 1,it explores the partial derivatives involved in training a Word2vec model using the naive softmax loss. In Part 2, it goes through two general neural network techniques (Adam Optimization and Dropout). Part 3 implements and train a dependency parser using the techniques from Part 2, before analyzing a few erroneous dependency parses.

## Deliverables
- Written answers to conceptual theoretical questions. [LaTeX](/a2_written/) / [PDF](/deliverables/a2_written.pdf)
- Code implementing a neural dependency parser. [Source code](/code/) / [ZIP](/deliverables/assignment2.zip)

## Requirements

To continue using cs224n environment from assignment 1 for this assignment, make sure to have all the dependencies listed in local_env.yml by running: 

#### 1. Activate the environment:

    conda activate cs224n

#### 2. Install docopt

    conda install docopt

#### 3. Install pytorch, torchvision, and tqdm

    conda install pytorch torchvision -c pytorch
    conda install -c anaconda tqdm

To create a new environment for this assignment instead, run:

#### 1. Create an environment with dependencies specified in local_env.yml (note that this can take some time):
    
    conda env create -f local_env.yml

#### 2. Activate the new environment:
    
    conda activate cs224n_a2
    
#### To deactivate an active environment, use
    
    conda deactivate

## Run

#### To run the neural dependency parser training, execute:

    python /code/run.py