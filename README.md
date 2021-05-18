<p>
  <a href="https://avatars.githubusercontent.com/u/30424551?v=4"><img width="150" align='right' src="https://avatars.githubusercontent.com/u/30424551?v=4"></a>
</p>



# Volkan Sonmez's Machine Learning Projects

© 2021 - current, Volkan Sonmez, www.pythonicfool.com

This is a repository of teaching materials, code, and data for my data analysis and machine learning projects.

Each repository will (usually) correspond to one of the posts on my [web site](http://www.pythonicfool.com/).

Be sure to check the documentation (usually in IPython Notebook format) in the directory you're interested in for the notes on the analysis, data usage terms, etc.

You are free to:

* **Share**—copy and redistribute the material in any medium or format
* **Adapt**—remix, transform, and build upon the material

for any purpose, even commercially. Just make sure to mention the source that you copied in your own material. 

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

* **Attribution**—You must give appropriate credit (mentioning that your work is derived from work that is © Volkan Sonmez and, where practical, linking to http://www.pythonicfool.com/), and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

**No additional restrictions**—You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

**Notices:**

* You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation.
* No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.

<p>


* ## Neural Networks

### Two_Layer_Neural_Network
This is a simple 2 layer Neural Network made for image recognition. The model is run with cifar-10 dataset.
Batch size is randomly picked and training is done with 1000 iterations to overfit the data intentionally. 
Forward propagation function uses two inverted drop outs, leaky relu, softmax methods. 
The loss function uses negative log likelihood method. Regulation is not used since drop out is used 2 times.
Updating the network parameters is done by Adam's update and are saved to .txt file
The expected accuracy is max 47% on the test set around 600-800 iterations
