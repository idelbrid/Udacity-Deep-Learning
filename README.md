# Udacity Course: Deep Learning
This repo contains ipython notebooks (and scripts?) for assignments that I am completing as part of the Udacity course in Deep Learning.

As of 1-31-17, assignments through 6 are finished, except for the 6.3. This task is to construct a sequence-to-sequence model that reverses the input string. The current implementation in `Tensorflow Deep Learning Assignment 6-Copy1.ipynb` is broken or does not optimize correctly. It will learn 1 character to 1 character, but for sequences of length 2 and up, it simply learns to use only spaces or only "e"s, likely the majority class. My hypotheses are these: 1. The Tensorflow is screwed up somehow; 2. The signals are not making it through the model due to bad initial weights, and only the logistic layer's biases optimize. 

The final project of this course may be added as it progresses or developed into a new repo.
