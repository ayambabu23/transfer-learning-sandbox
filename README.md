# My Transfer Learning Sandbox
Use MNIST dataset (handwritten English numbers) to train a model and transfer learn that to read Chinese numbers. The MNIST dataset is pretty large and readily available and so using it to train the first few layers of the model especially would allow the algorithm to detect some of the edges, their relative position, etc. The smaller Chinese MNIST dataset would be used largely to train the last few layers, as the last few layers is where the decision making usually happens.
