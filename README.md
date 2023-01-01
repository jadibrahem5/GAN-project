# GAN-project
Gan is a research based project  to autonomously generate new architectural design imagery in the style of Zaha Hadid To do this, a W-GAN algorithm has been trained. It is a powerful algorithm to learn then recreate the unique patterns, styles, and geometries inherent in 2000 images of her original work


The number of original images collected was very small for the training process, so we had to use data processing algorithms to increase the number of training samples by applying Data Augmentation techniques


One of the obstacles we faced while building the model is the lack of a dataset that contains all of zaha's work
Since it was difficult to compile the images manually, so we created a python script that depends on the libraries
Selenium, PIL, and an add-on in Google chrome is Google Webdrive
script opens a Google Chrome window and searches for all images to which the specified class belongs
pre-recorded and downloaded.
