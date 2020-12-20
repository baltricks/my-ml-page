---
title: When my ML learning starts
description: An exiting book - My Coding Environment -  What I've learned until now
---

## An exiting book

In late 2020 I came across *Deep Learning for Coders with fastai and PyTorch: AI Applications Without a PhD* by Jeremy Howard & Sylvain Gugger and I was directly inspired and excited to dive into deep learning. Deep Learning, Machine Learning, AI and all the other terms of artifical intelligence had been very unclear to me - even though I'd been working for many years as a software developer. But with this book I got the feeling that the door to this domain is now opened to me. Opened by authors with long lasting experience in coding and teaching AI. 

## My coding environment

Following the book coding should take place in Jupyter Notebooks. After looking around for the different ways to get own Jupyter Notebooks running I decided to start with Google Colab for my Notebooks. Although there are some issues to keep in mind:

1. Colab Notebooks differ from the typical Jupyiter Notebook GUI
2. Google doesn't garantee access to GPUs (which is highly recommended when training your models). So you can run temporarily into performance problems.
3. The Colab platform doesn't support Voila, which will be used for publishing purposes

From the [books website](https://course.fast.ai/) you can start any of the books chapters (the book itself is written in Jupyter Notebooks). From there you can copy or create new Notebooks and store them in Google Drive. The only prerequisite is a Google Account. That's all.

From this point you can start adding and running your own (or copied) code and text blocks in your notebooks.

> When rebuilding the first samples from the book I had to add following imports:
> 
    from fastai.vision.widgets import widgets, PILImage

With this setting I was able to run the first prepared samples (image classifier and others) coming with the book.

## What I've learned until now

Each chapter of the book ends with a questionnaire which helps you checking your learning progress.

What I've learned:

- Natural language procession (NLP), computer vision, medicine, biology and image generation are currently the main areas of deep learning
- A brief historical survey (from the first artificial neurons to neuronal networks)
- Understand **machine learning** as another way (other than writing a program) to let computers do their task - by learning from their experience (= **training**)
- Training
  - Requires training data
  - A model can only learn from input data
  - It creates only predictions (based on the input)
  - Training data must be labeled (correctly)
- The two main types of models are
  - **Classification**: the model makes a prediction about a class or category
  - **Regression**: the model makes a quantified prediction
- Input Data is divided into different data sets:
  - a **training set** used as training input
  - a **validation set** (or development set) to measure the accuracy of the model
  - and optional a separate **test set** to test the model with never seen data
- An **epoch** is a complete pass through the training data
- A **metric** measures the accuracy of a model
- The **loss** is the measured accuracy
- Too long training could lead to **overfititng** which means that the model memorizes the training data more than the general patterns 
- There are **weight parameters** in a neuronal network (or model) and **hyperparameters** determing the training process.
- **Pretrained models** can be used for faster training. Training such a model with new data is called **fine-tuning**.







