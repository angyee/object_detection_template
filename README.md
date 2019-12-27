# Tensorflow Custom Object Detection Template

#### Easy to use notebooks for preprocessing data locally to training on the cloud with colab

This repository is an easy to template for using Tensorflow Object Detection API on custom datasets. The preprocessing can be done with the provided notebook locally and then training can be done easily on colab.

## Required Libraries

- Tensorflow 1.15
- object_detection
- opencv

It is best to create a separate python/conda environment

## Usage

1. `git clone https://github.com/theneuralbeing/object_detection.git`
2. [Read this]() for gathering and annotating data
3. Run the [Preprocess_Data.ipynb]() notebook on your computer
4. After your data is ready, you can start training on colab. To do so [click here]() to directly open the training notebook on colab. The colab notebook contains all the further steps.
5. After training, the trained inference graph will be downloaded to your computer and you can use the [`inference_webcam.py`](). (the steps for inference are also mentioned in the colab notebook)