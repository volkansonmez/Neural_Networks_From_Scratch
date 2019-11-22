# Neural Networks

### Two_Layer_Neural_Network
This is a simple 2 layer Neural Network made for image recognition. The model is run with cifar-10 dataset.
Batch size is randomly picked and training is done with 1000 iterations to overfit the data intentionally. 
Forward propagation function uses two inverted drop outs, leaky relu, softmax methods. 
The loss function uses negative log likelihood method. Regulation is not used since drop out is used 2 times.
Updating the network parameters is done by Adam's update and are saved to .txt file
The expected accuracy is max 47% on the test set around 600-800 iterations
