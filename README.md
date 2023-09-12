# Project Name

Creating a simple QNA chatbot for answering doubts regarding a bakery business. It is a deep-learning chatbot created using python, TensorFlow, and nltk.

## Installation

To install the required version of TensorFlow, run the following command:

```bash
!pip install tensorflow==2.8.0
!pip install tflearn
```

## Usage

```python 
import tflearn
from tflearn.layers.core import input_data, fully_connected
from tflearn.layers.estimator import regression

# Define your neural network architecture
net = input_data(shape=[None, 784])  # Example input shape
net = fully_connected(net, 128, activation='relu')
net = fully_connected(net, 10, activation='softmax')

# Define the model and configure training
model = regression(net, optimizer='adam', loss='categorical_crossentropy')

# Train the model, evaluate, and make predictions as needed.
```

## No Contributions, Please

This project is intended for personal use, and I do not currently accept external contributions or pull requests. While I appreciate your interest in this project, I have chosen to maintain it as a personal or closed project.

Feel free to use the project as-is for your own purposes, but please understand that I will not be actively reviewing or merging contributions from external contributors.

Thank you for your understanding.


## License

[MIT](http://tflearn.org/license/)
