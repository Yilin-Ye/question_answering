# Question Answering on Medical Flowsheet

## Knowledge Background

Basic package: **Pandas**, **Numpy**

Advanced framework & packages: **Transformer**, **Hugging Face**, **Pytorch**

## General
This file contains the code for exploratory data analysis and how I transformed the raw dataset into the format required by TAPAS.

## Question Designing
This file contains the code shows how I designed the medical question-answering training set for fine-tuning.

## Performance Metric
This file contains the code shows how I designed performance metric function to meausre the performance of my model before and after fine-tuning.

## Fine Tuning
I designed a simple fine-tuning pipeline to tune TAPAS based on my customized training set, achieved by pytorch.


## Paper Link & Paper GitHub Link
https://arxiv.org/abs/2004.02349

https://github.com/google-research/tapas


## Hugging Face Link
https://huggingface.co/docs/transformers/model_doc/tapas

## Data
Medical flow sheet dataset.\
Due to its sensitivity, it is not available to the public.
