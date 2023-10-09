# Getting started notes

Source: https://course.fast.ai/Lessons/lesson1.html

Learn much better with a context in place then fill in the detials later on.

Understand later and get good at deploying models first.

Sports:
    See the whole picture. 
    Start playing sport.
    Get into the micro skills.
    
Classic image processing
- Build a feature list
- Logistic regression model application

Key idea: Neural networks build the features instead of humans 

Key idea: "Deep learning" refers to the multiple layering of features on top of each other

AI boom is the result of automatic creation of "features" instead of hand coding the things to look for

Image classifiers can be applied to a wide range of inputs types if the input is made into an image

Key idea: To deploy and use a model you don't need math, lots of data or computer knowledge

fast.ai is a syntax sugar over pytorch (standardise good practices in general)

More pure pytorch as things get deeper and we learn more about the machinary

DataBlock is a group of input and validation input that can be loaded in parallel to run on a GPU

A "learner" combines a model and the data we are going to use and the model.

resnet - a model (.pth) file. A starter network that already knows a lot about images and their structures

tuning a model is changing it weights

predict(image path) -> a classification

loss - a number that tells you how good your results are so that you can use that to improve the weights

Using jupyter notebooks for other stuff
    - [ ] https://quarto.org/
    - [ ] https://rise.readthedocs.io/en/stable/

