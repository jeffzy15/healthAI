# SilverMind

### What it does?

It predicts and classifies images of pills. From the predicted pill image, it will look through the database of pills to find relevant information about the pill to answer queries from the user such as "What is the usage of this medicine?". Then, it will provide lifestyle advice according to the medicine they consume using OpenAI.

### How is it built?

It uses Keras from Tensorflow to build a Convolutional Neural Network (CNN). The model has a total of 12 layers, including convolutional, batch normalization, max pooling, dropout, and dense layers. Accuracy: **92%**.

### Running on your machine

#### 1. Getting the [dataset](https://www.kaggle.com/datasets/vencerlanz09/pharmaceutical-drugs-and-vitamins-synthetic-images) for images

Navigate through the folder and find the folder that contains the images.  <br /> 
**IMPT: Rename that folder as data for the code to work.**

#### 2. Installing libraries

Ensure all libraries are installed before running the code.


#### 3. API Key for OpenAI

Get your key from [OpenAI](https://platform.openai.com/account/api-keys) to use the notebook.

