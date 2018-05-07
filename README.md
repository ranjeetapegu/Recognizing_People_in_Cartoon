# Recognizing_People_in_Cartoon

Simple Convolutional Neural Networks (CNN’s) model works amazingly well in classifying the MNIST hand written digits or differentiating dogs and cats even with a small dataset of few thousand images. In this small fun project, I wanted to test how well the same simple techniques works if we were trying to classify famous persons from their cartoon images or caricature images. In this experiment, I will compare the accuracies obtained by three techniques: a training model with small image dataset from scratch, model with data–augmentation applied to the sample dataset and using vggface-network as pretrained network.

### Background
Convolutional Neural Networks has gain huge success in analyzing visual imaginary and creating state of art technique in many applications in field of machine learning and deep learning. Also with invention of new deep learning tools like Keras with a focus on enabling fast experimentation, it is very convenient to develop new neural network and try out different experiments. We have seen, very easily and with high accuracies we can classify the MNIST hand written digits; distinguish dogs and cats using the keras deep learning libraries. The goal of this fun project is to extend the same deep learning techniques to recognize people from their cartoon images. Data like in any experiment is the key in deep learning too. It is time consuming and very expensive to get the desired data. Thanks to various APIs and tools available for free usage making process of downloading data from web much relaxing and enjoyable experience. 

### Overview of Experiment
1.	Install all the prerequisite software and libraries mentioned above
2.	Download the training and test Dataset.
3.	Preprocessing of Data
4.	Creating Model 1: a simple Convolution Neural Network model: Stack of alternated Conv2D (with “relu” activation) and MaxPooling2D layers. Then flatten the 3D output to 1D and adding few dense layer on top. The final layer with 6 output and Softmax activation.
5.	Creating Model 2: a simple convolution neural network model + Data-Augmentation Techniques on the train images 

6.	Creating Model 3: Using VGGFACE as pretrained network + Feature Extraction + Data-Augmentation Techniques on the train images.

7.	Creating Model 4: Using VGGFACE as pretrained network + Fine-Tuning + Data-Augmentation Techniques on the train images 

8.	Comparing the output accuracies of all the models.



