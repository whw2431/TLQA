# Timeline based List-Question Answering

## Table of Contents
- [Introduction of the project](#introduction-of-the-project)
- [Usage](#usage)
- [Example](#example)

## Introduction of the project
Timeline based List-Question Answering (TLQA) is a detailed subarea within the broader field of List-Question Answering which focuses on generating lists of items in response to queries and also in chronological order. We explore various implementations of TLQA, evaluating closed-book models and Retrieval-Augmented Generation (RAG) models with different scoring metrics, and also introduce time relevence into our systems. We integrate few-shot prompting and fine-tuning techniques to enhance the model's performance and compare their differences in detailed examples based on the testing results. Our experiments reveal that while these methods improve TLQA tasks, letting the models answer the question as the required format successfully, challenges remain due to the computational limitations of current models. 
## Usage

You can run the Jupyter notebook separately depending on what you want to achieve. The contents of our code are organized as follows:

- `Closed_book` folder: Contains all the model code and prediction results for the closed book setting.
- `RAG` folder: Contains all the model code and prediction results for the RAG (Retrieval-Augmented Generation) setting.
- `Evaluation.ipynb`: Contains the evaluation of all predictions.


## Example
**Question**: *List all positions Oleksandr Turchynov, also known as Oleksandr Valentynovych Turchynov, held from 2010 to 2020*  
**[Answer]**:  
    - President of Ukraine (2010, 2011, 2012, 2013, 2014)  
    - Prime Minister of Ukraine (2014, 2015, 2016, 2017, 2018, 2019, 2020)
