# stereogram-vision

## Repository goal

The purpose of this repository is to create a dataset of stereograms and train a neural network to recognize hidden images using computer vision techniques.

## Project Stages: 

- **Dataset Collection** — gather stereograms with hidden images and a control group without hidden content.
- **Data Annotation** — label each image as 1 (has hidden image) or 0 (no hidden image).
- **Model Training** — train a neural network  to classify.
- **Real-World Testing** — validate the model on unseen, real stereograms from public or user sources.

## **1. Create a dataset stage.**

To form a balanced dataset, 1000 images will be used, divided equally between two classes:

— **500 images with a hidden 3D image (class 1)**,
— **500 images without hidden content (class 0).**

In the future, it is also planned to expand the dataset by generating synthetic stereograms, which will increase the variety of data, improve the generalizing ability of the model and test it on controlled examples.
