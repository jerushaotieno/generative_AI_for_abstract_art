# generative_AI_for_abstract_art

## Introduction

Creating a generative AI algorithm for generating beautiful and thought-provoking art is a complex task that often involves deep learning models. One popular approach for this is using Generative Adversarial Networks (GANs). GANs consist of a generator and a discriminator, where the generator creates new data (in this case, images) and the discriminator evaluates how realistic the generated data is.

For this project, I used a simple GAN implementation in TensorFlow to generate abstract art.

## Task

Generate abstract art that is both beautiful and thought-provoking.

## Generative AI algorithm

Generative Adversarial Network (GAN)

## Code

The developed code is a basic GAN implementation using TensorFlow and Keras. It generates abstract art images by training a generator to create images that can fool a discriminator. The generator and discriminator are neural networks, and the GAN is trained in a loop over epochs.

## Output

The output of this code is a series of generated images saved at specified intervals during training (after every 5000 epochs). These images exhibit abstract and potentially thought-provoking patterns and colors.

## How the output meets the objectives of the task

The objective is to create art that is both beautiful and thought-provoking. The GAN is designed to learn patterns from a given dataset (or a random noise distribution) and generate novel images that resemble the training data. The generator's objective is to create images that can convince the discriminator they are real, leading to the generation of visually appealing and abstract art.
