# Classifying handwritten Digits using neural network

* The neural network we will build classifies the handwritten digits in their 10 classes (0, .., 9). 
* It does so based on internal parameters that need to have a correct value for the classification to work well. 
* This "correct value" is learned through a training process which requires a "labeled dataset" with images and the associated correct answers.

Cell "Parameters"
The batch size, number of training epochs and location of the data files is defined here. Data files are hosted in a Google Cloud Storage (GCS) bucket which is why their address starts with gs://

Cell "Imports"
All the necessary Python libraries are imported here, including TensorFlow and also matplotlib for visualizations.

Cell "visualization utilities"
This cell contains uninteresting visualization code.

Cell "tf.data.Dataset: parse files and prepare training and validation datasets"
This cell used the tf.data.Dataset API to load the MNIST dataset form the data files. It is not necessary to spend too much time on this cell. If you are interested in the tf.data.Dataset API, here is a tutorial that explains it: TPU-speed data pipelines.
