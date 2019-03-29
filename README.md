# Extended MNIST Letter Recognition

An implementation of EMNIST Letter Recognition using Keras, labelled by-class.

Structure of the Neural Network: 
Conv2D (64, (3,3)) -> Conv2D (64) -> MaxPooling(2,2) -> Conv2D() -> MaxPooling() -> Dropout() -> Conv2D() -> MaxPooling() -> Flatten() -> Dense() -> Dropout() -> Dense(activation = 'Softmax').


You can find the dataset here : 

https://www.kaggle.com/crawford/emnist
