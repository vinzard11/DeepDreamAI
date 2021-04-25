# DeepDreamAI
A model that uses inceptionV3 and it's weights as the base to generate creepy pictures given some input.
* It's a vision algorithm developed by google to generate Hallucination like effect on an image.
* It does so by using the inception model which is trained on hundreds of thousands of animal pictures.
* So, our network will try to extract animal features in any given image.
* Using this, instead of reducing the gradient we boost it to see some eye-catchy results. 


### MATH 
-------------
* In the ![code](https://github.com/vinzard11/DeepDreamAI/blob/main/code/DeepDreamAI.ipynb) of this repository you can find a function called deepdream.
* Basic idea is that we calculate the gradient of loss with respect to input pixels and instead of gradient descent we perform gradient ascent.

### Data
------------
* I've inputed the 2 images given in the following ![directory](https://github.com/vinzard11/DeepDreamAI/tree/main/Input_images).
* blended them and moved ahead with the algorithm to produce some interesting results.

![output video](https://github.com/vinzard11/DeepDreamAI/blob/main/mars_eiffel_vid.mp4)
