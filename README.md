# Finance images Generation

In this project, we will define and train a Deep Convolutional GAN on a dataset of finance images. Our goal is to get a generator network to generate *new* finance images that can be used as the cover page for a finance magazine, or simply include them in a finance article. 

The project will be broken down into a series of tasks from **loading in data to defining and training adversarial networks**. The generated images look like below: 

<img src='image/output_image.png' width=20% />


## Get the Pre-processed Data

We will be using google searched images in [finance](), [investment](), and [currency]() to train our adversarial networks. Each of the finance images has been resized down to 64x64x3 NumPy images. Some sample data is shown below.

<img src='image/input_image.png' width=20% />

You can download this data from the zip file, and extract them in the home directory of this notebook for further loading and processing. After extracting the data, you should be left with a directory of data `processed_images/`
