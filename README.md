### Building a Deep autoencoder for Data compression
***
* **Data** : MNIST  
* **Neural-Network**
  * **Encoder** : 2 layers (input included)
  * **BottleNeck** : 30 features
  * **Decored** : 2 layers (output included)

Total 5 layers (3 hidden layer, 1 input, 1 output)

***Training Info***
  * Optimizer : ADAM (gradient descent)
  * Initializer : Xevier
  * Epoch : 100 (Batch:100)

***Result***
* 784 feature compressed to 30
* 96.17% compression
<br>
<img src='https://i.ibb.co/pJXLCZb/download.png'>
<br>

read [Autoencoder Notebook](https://github.com/ashish-2005/Autoencoder/blob/master/Autoencoder.ipynb) for complete procedure
