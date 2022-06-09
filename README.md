# TensorFlow-TanH-Issue

https://colab.research.google.com/drive/1w9k6KdyhwKhrDfO97xP8qqmc3zxn9Wvw?usp=sharing


The tanh activation function is supposed to give an output in range [-1,1] but in this instance the output would sometimes have value in range [-9.999...,9.9999...]. Below I have attached a link to a repo where you can see the model architecture, the input and the output of the same, the model is also saved and uploaded in the same repo. The notebook was ran in colab and local environment where I faced similar result

tf version 2.8.2
