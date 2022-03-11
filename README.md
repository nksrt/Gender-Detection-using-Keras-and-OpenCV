# Gender-Detection-using-Keras-and-OpenCV

This project focusses on understanding human visual processing and identifying key features used to categorize between male and female and this is the basis for our classification.
The convolutional neural network (CNN) consists of several convolutional layers alternating with subsampling layers and ends with one or more fully connected layers in the standard multilayer perceptron (MLP).
A significant advantage of the CNN over conventional approaches in pattern recognition is its ability to simultaneously extract features, reduce data dimensionality, and classify in one network structure
Feature extraction and classification are performed within a single network structure through learning on data samples
Feature selection is also integrated into the training process by learning the weights held responsible for extracting features
Minimal preprocessing Required
Relatively easier to train since they have fewer parameters

Usage
#Set path for image input and run:
$ python train.py
//It will train the dataset of images and pre-trained the model// 

webcam
$ python detect_gender_webcam.py

Dataset Link: (Will upload asap)

Training
You can download the dataset I gathered from Google Images and train the network from scratch on your own if you're interested. You can add more images and play with the hyper parameters to experiment different ideas.

Additional packages :
scikit-learn
matplotlib
Install them by typing pip install scikit-learn matplotlib

Usage
Start the training by running the command

$ python train.py -d <path-to-dataset>

(i.e) $ python train.py -d ~/Downloads/gender_dataset_face/

Depending on the hardware configuration of your system, the execution time will vary. On CPU, training will be slow. After the training, the model file will be saved in the current path as gender_detection.model.

If you have an Nvidia GPU, then you can install tensorflow-gpu package. It will make things run a lot faster.
