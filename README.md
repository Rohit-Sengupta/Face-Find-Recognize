# Face-Find-Recognize
This repo consists of two scripts, the first script is the Face-Seperator(Used for image augmentation and preprocessing) and the second script is Face is where we find and recognize faces


Face-Seperator(Needs to be used and run first for recognition data):

This script is used to create and process images for training data, it uses python and open-cv to take and 
store images of the user, please look left and right when storing images so the model has a good reference of your face, script also works with random faces image data to move, process and covert them to be used as training data


Faces:

-This script first takes a random image and tests the haars casacade to see if it the script and dependencies are all functioning properly

-Next we prepare the dataset to train the Deep learning CNN model

-After that we make the model architecture and train the model on the prepared dataset

-Finally we test the model live to see how well it works


