# Project Report

## Writeup

### Provide a write-up / README document including all rubric items addressed in a clear and concise manner. The document can be submitted either in either Markdown or a PDF format

You are reading the write-up.

### The write-up conveys the an understanding of the network architecture

TODO: Include description and figure

### The write-up conveys the student's understanding of the parameters chosen for the the neural network

TODO: List all parameters and explain

### The student has a clear understanding and is able to identify the use of various techniques and concepts in network layers indicated by the write-up

TODO

### The student has a clear understanding of image manipulation in the context of the project indicated by the write-up

TODO

### The student displays a solid understanding of the limitations to the neural network with the given data chosen for various follow-me scenarios which are conveyed in the write-up

## Model
### The model is submitted in the correct format

TODO

### The neural network must achieve a minimum level of accuracy for the network implemented

The model performs OK in follow mode, but takes a long time to lock on to the hero. This means that the model does not recognise the hero from many different distances and angles. But as soon as the model locks on, the follow mode is solid.

The resulting IoU (Intersection of union) score is 46%. Over the required threshold, but not by much. The detection of the hero at distance ruins the score and performance.

A video from the follow mode can be found [here (docs/misc/FollowMe.mp4)](./docs/misc/FollowMe.mp4)


## Improvements
TODO: Capture more pictures
TODO: Train on more images (patrol is bad)
TODO: Tensorflow (to be able to train faster)
