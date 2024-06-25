# Handwritten-digit-recognition-system


This project is a handwritten digit recognition system using machine learning. It employs a dataset of handwritten digits for training and testing. Implemented in Python with TensorFlow and Keras, the project involves setting up a development environment with Python and VS Code.

The code loads and preprocesses the dataset of handwritten digits. A simple neural network model is built using Keras Sequential API, with an architecture including a Flatten layer and two Dense layers. The model is compiled with Adam optimizer and categorical crossentropy loss.

Training is performed on the dataset for 10 epochs, after which the model's accuracy is evaluated on the test set. A function is created to preprocess new handwritten digit images. Users can input their own handwritten digit as an image file (digit.png), which the model then predicts.

The prediction result is displayed along with the input image. This project demonstrates basic image processing and neural network concepts, showcasing how to build, train, and use a simple machine learning model. It includes visualization of sample images and predictions.

Providing a practical introduction to deep learning for beginners, the project can be extended to recognize more complex handwritten text. It emphasizes that machine learning skills can be learned by anyone with dedication, regardless of their background.
