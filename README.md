## Deep Learning- I’m Something of a Painter Myself
In this project we solved the Kaggle competition https://www.kaggle.com/c/gan-gettingstarted/data

The monet directories contain Monet paintings. We used these images to train our model.
The photo directories contain photos. We added Monet-style to these images.

This project has **one more constrain**- the original Monet directory in this challenge contains 300 Monet paintings sized 256x256 for
training.
We were allowed to use **only 30 paintings** in the training as part of this
competition.
#### How we chose 30 painting:
ALG():
- go over 300 Monet images
- select the closest Monet to others by
 RGB values
- remove the closest from list
- continue
- if closest not found- take any


#### How to run:

* Training notebook - https://colab.research.google.com/drive/1qEZWQeRYLgFiyhtc3Po7lq2vJ8__erlh?usp=sharing
* Inference notebook - https://colab.research.google.com/drive/19fyswUV9e2EjkqD2FHcsmPyJ3rmhFIAb?usp=sharing

Training notebook already displays information after running.
It also includes access to Drive where it saved the model.
In order to run, press 'Runtime' and then 'run all'.
It may take a while
Similarly for the 2 notebooks.


