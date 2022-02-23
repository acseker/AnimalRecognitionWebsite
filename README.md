# Animal Recognition Website Application

This project is a website application of 16 different animal recognition.
The system contains two parts: designing website, training a Convolutional 
Neural Network (CNN) network, and making connection between website and trained CNN.

First, a basic webpage is designed, containing 16 different animal images to 
inform the user about the used animal classes.
There are also two buttons for uploading images and making prediction.
Webpage file is located in `templates`.

<img src="/images/image1.png" width="400">

Then, a CNN is trained with the dataset that contains 16 different animal images.
You can do a new training using `training.ipynb`.
Finally, the trained CNN and the designed webpage are connected each other 
to transfer the uploaded images.

The application runs as in the following:
* The user uploads an image to website.
* The trained CNN use it as input image and makes prediction.
* The predicted results returns to webpage for visualization.

<img src="./images/image2.png" width="400">

#Testing Images
In order to test your custom images, you need to make a new training or 
[download]() the pre-trained model. Make sure the model name is `saved_model.h5` if you make a new training.  

You can run the code by following commands:
    
    python website.py

