<p>
  <a href="https://avatars.githubusercontent.com/u/30424551?v=4"><img width="150" align='right' src="https://avatars.githubusercontent.com/u/30424551?v=4"></a>
</p>



# Volkan Sonmez's Machine Learning Projects

© 2018 - current, Volkan Sonmez, www.pythonicfool.com

This is a repository of teaching materials, code, and data for my data analysis and machine learning projects.

Each repository will (usually) correspond to one of the posts on my [website](http://www.pythonicfool.com/).

You are free to:

* **Share**—copy and redistribute the material in any medium or format
* **Adapt**—remix, transform, and build upon the material

Under the following terms:

* **Attribution**—You must give appropriate credit (mentioning that your work is derived from work that is © Volkan Sonmez and, where practical, linking to http://www.pythonicfool.com/), and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

<p>


* ## Neural Networks

### Two_Layer_Neural_Network
This is a simple 2 layer Neural Network made for image recognition. The model is run with cifar-10 dataset.
Batch size is randomly picked and training is done with 1000 iterations to overfit the data intentionally. 
Forward propagation function uses two inverted drop outs, leaky relu, softmax methods. 
The loss function uses negative log likelihood method. Regulation is not used since drop out is used 2 times.
Updating the network parameters is done by Adam's update and are saved to .txt file
The expected accuracy is max 47% on the test set around 600-800 iterations
