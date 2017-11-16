# <center>Incremental Deep Learning

## Overview

The idea behind Incremental Dynamic Learning networks is that information is not always learned at once, up front. As information is encountered, we train on the new data. Adding the new information to our existing knowlege base. Humans, are said to be able to recognize an image in 13 milliseconds after seeing it.The new image is added to their existing learned information and they do not have to retrain on all images they have ever seen.

## Example

As an example of how this can be used in the real world, I will use field biologists for my use case:

Imagine groups of field biologists all out exploring the animal and plant world as a part of their daily efforts. They are out there, armed with their mobile phones and devices ready to catalog new and existing spieces. What if they were to photograph their discoveries and forward them to a central location where they can be used to train a neural network to classify the images. This same network can be used by non-experts to identify animals and plants they encounter and would like to undertand what they have just photographed.

Instead of training the network over and over sending in batches of all the images to be classified, what if the network learned as data was presented to it? That is the focus of this paper, to see what level of accuracy can be achived over time while the network is trained using only one image at a time.

## Assumptions

It is assumed that the network will behave quite poorly when first starting out. The goal is to ramp up the accuracy as images are presented so that even at earlier stages, the network can be used to give reasonable approximations. Over time, as new variations of existing classifications are presented, the network will be expected to increas it's accuracy.

## Acknowlegements 

It's been a long journey for me over the last year being exposed to Machine Learning and Deep Learning. Most of what I do on a daily basis is borrowed from the problems I worked through during the two courses I took from [Udacity](https://www.udacity.com). Udacity certainly has provided me with a great deal of knowlege on these subjects and I an forever greatful of their existance.

I also would like to thank [Franceso Mosconi from Catalit LLC](https://www.linkedin.com/in/framosconis/) for opening up my Deep Learning world to [Keras](https://keras.io/) and all the power provided by this easy to use extension of [TensorFlow](https://www.tensorflow.org/). 

Lastly, I have to thank [Google](http://www.google.com) for providing such an easy-to-use powerful Deep Learning platform called TensorFlow and making it free for the world to use. Without such open distribution, this technology would only be available to a few instead of the many.

I thank you all for giving me the tools I need to explore this facinating new technology and allowing me to flourish on and off the job. 
