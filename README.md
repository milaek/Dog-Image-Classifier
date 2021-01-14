# Dog Image Classifier
 A project for Udacity's AI Programming with Python Nanodegree course. This project uses various image classifiers to identify images with dogs as well as their breeds. Base code for the classifier and tests written by Udacity.


# Motivation
Written as part of the AI Programming with Python Nanodegree Program provided by Udacity.

# Installation
Please either:

	- Install all packages listed in requirements.txt, which can be found in the subfolder environment_needs

	- Use the environment provied, located in the subfolder environment_needs as environment.yaml

# How to use
##Pre-Established Photos:
###Non-Windows OS
    Open your terminal
    Navigate to the directory which contains the program files
    Type and run the following:
        sh run_models_batch.sh
###Windows OS
    Download and install Anaconda
    Open Anaconda
    Navigate to the directory which contains the program files
    Type and run the following:
        run_models_batch.bat

In both cases, the readout will be put into three .txt files within the program folder titled name_pet-images.txt , with name replaced by the model used.

##Upload your own Photos:
Process the desired images so that:

-Images are in jpeg format with extension jpg

-Images are approximately square in shape (their height and width are approximately the same number of pixels).

-Images are labeled as the animal/object/dog breed (and a number if desired) with _ replacing any spaces

-Copy or move the images into the folder titled uploaded_images in the program's folder

To run the program some slightly different commands are needed, detailed below
###Non-Windows OS
    Open your terminal
    Navigate to the directory which contains the program files
    Type and run the following:
        sh run_models_batch_uploaded.sh
###Windows OS
    Download and install Anaconda
    Open Anaconda
    Navigate to the directory which contains the program files
    Type and run the following:
        run_models_batch_uploaded.bat

In both cases, the readout will be put into three .txt files within the program folder titled name_uploaded.txt , with name replaced by the model used.



# Credits
Credit for Classifier code and project idea to Udacity and the AI Programming for Python Nandegree.
