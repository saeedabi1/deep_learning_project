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


## Why Attention Mechanism?

The problem with this method is that, when the model attempts to generate the caption next word, that word usually only describes a part of the image. 
It is not capable of capturing the essence of the whole input image. 
Using the entire representation of image to condition the generation of each word can not generate different words effectively for different parts of the image. 
This is why an Attention mechanism can be helpful.

## Data

To address this problem, there are many open source datasets available, such as 
** Flickr 8k (containing 8k images)
** Flickr 30k (containing 30k images)
** MS COCO (containing 180k images), etc. 

But we have used the Flickr 8k dataset for this case study which you can access from here. 

** Training a model with a large number of images on a system that is not a very high end PC / Laptop may not be feasible either.

** This dataset contains 8000 images with 5 captions each (as we already saw in the Introduction section that an image can have multiple captions, all of which are relevant at the same time). 
** These images are bifurcated as follows: Training Set — 6000 images, Dev Set — 1000 images, and Test Set — 1000 images.



