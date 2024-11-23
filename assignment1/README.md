# Assignment 1

## Introduction

Word Vectors are often used as a fundamental component for downstream NLP tasks, e.g. question answering, text generation, translation, etc., so it is important to build some
intuitions as to their strengths and weaknesses. This assignment explores two types of word vectors: those derived from co-occurrence matrices, and those derived via GloVe.

## Requirements
Make sure to setup at least Python version 3.8. If not, the easiest thing to do is to install the Python 3 version of Anaconda (Miniconda for a reduced version). It will work on any operating system.

After installing conda, close any open terminals, open a new terminal and run the following command:

#### 1. Create an environment with dependencies specified in env.yml:
    conda env create -f env.yml

#### 2. Activate the new environment:
    conda activate cs224n
    
#### 3. Inside the new environment, install IPython kernel so we can use this environment in jupyter notebook: 
 
    python -m ipykernel install --user --name cs224n

#### To deactivate an active environment, use
    conda deactivate

## Running

#### Assignment 1 is a Jupyter Notebook. With the above done you should be able to get underway by typing:

    jupyter notebook exploring_word_vectors.ipynb
    
To make sure we are using the right environment, go to the toolbar of exploring_word_vectors.ipynb, click on Kernel -> Change kernel, you should see and select cs224n in the drop-down menu.
