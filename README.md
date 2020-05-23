# Photo Caption Generation using Global and Local Attention

## Author(s): 
Poornapragna Vadiraj, Varun Bhaseen, Mirsaeid Abolghasemi

Deep Learning CMPE 258 - Term Project - Professor Vijay Eranti - Spring 2020

## Introduction:

Attention mechanisms are broadly used in present image captioning encoder / decoder frameworks, where at each step a weighted average is generated on encoded vectors to direct the process of caption decoding. 
However, the decoder has no knowledge of whether or how well the vector being attended and the attention question being given are related, which may result in the decoder providing erroneous results. 
Image captioning, that is to say generating natural automatic descriptions of language images are useful for visually impaired images and for the quest of natural language related pictures. 
It is significantly more demanding than traditional vision tasks recognition of objects and classification of images for two guidelines. 
First, well formed structured output space natural language sentences are considerably more challenging than just a set of class labels to predict. 
Secondly, this dynamic output space enables a more thin understanding of the visual scenario, and therefore also a more informative one visual scene analysis to do well on this task.

## Issues with Traditional Methods of Image Captioning:

During generating the next word of the caption, this word is usually describing only a part of the image. 
Capturing the essence of the entire input image is unable
Using the full representation of the image “h” to help in the process of generating each word cannot produce different words for different parts of the image. 
Using Attention mechanism to solve these problems, by focusing on certain important features that may be present in the image.
Eg: HAARCascade

![alt text](https://github.com/saeedabi1/deep_learning_project/blob/master/pictures/pasted%20image%200.png?raw=true)


