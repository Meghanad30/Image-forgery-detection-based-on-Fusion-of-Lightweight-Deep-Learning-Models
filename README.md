# Image-forgery-detection-based-on-Fusion-of-Lightweight-Deep-Learning-Models
This project aims to find the manipulated pictures by automating the method of feature extraction instead of feature engineering through the manual process.The use lightweight models in favour to prevent overfitting of the CNN architectures and can be easily deployed on resource constrained hardware and can learn enriched representations.
The method first converts the RGB image into a grayscale image on the basis of chrominance components. The features extracted are subsequently used with PCA to increase the efficiency of the image classification using SVM. To detect the image forgery, the histogram of orientated gradients  based model is used. A CNN model with a blocking strategy was used for image forgery detection. In this method, the image is divided into blocks namely tight blocks and marginal blocks.
The blocks were fed into CNN that is recurrent in nature for the forgery detection with SVM as the classifier model. One more CNN model is used in to detect the copy and move image forgery. It uses the Siamese neural network for the forgery detection with 3 convolutional layers, 2 max-pooling layers and 2 fully connected layers. A deep learning model based on Autoencoder is also used for the detection of the forged images . It uses two stages stacked on top of each other.
In the future, the fusion decision can be improved with other weight initialization strategies for image forgery detection.
Libraries used:
Tkinter
Matplotlib
Numpy
Sklearn
Seaborn
Keras
