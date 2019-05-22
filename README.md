# dog-breed-classifier
A solution to udacity deep-learning nano degree dog-breed-classifier project.

### Info
Convolution Neural Network is used to identify an estimate of the canine’s breed from more than 130 dog breeds. 
Given an image the project detects a human or a dog. 
When a Human is detected the algorithm outputs the most similar dog breed which resembles the human. 
When a Dog is detected the algorithm outputs the most similar dog breed which resembles the dog.

The project uses Open CV cascade classifier to detect human faces.

This project creates CNN from scratch and achieves an test accuraccy of 14% with 20 epochs.
With the help of transfer learning using VGG16 architecture the test accuracy rose up to 84%.


### Resources
Link to udacity dog-breed-classifier repository can be found [here.](https://github.com/udacity/deep-learning-v2-pytorch)
