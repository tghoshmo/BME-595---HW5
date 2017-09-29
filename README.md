# BME 595 : HW5
## Tarutal Ghosh Mondal 
### Report

* Part A
  * Figure 1: PyTorch’s nn Package, MNIST Data, Loss vs. Epoch
  ![image1](https://user-images.githubusercontent.com/31314634/31004189-533117b0-a4c1-11e7-8cb1-fb11f9311cdb.png)
  * Figure 2: PyTorch’s nn Package, MNIST Data, Accuracy vs. Epoch
  ![image1](https://user-images.githubusercontent.com/31314634/31004190-53323776-a4c1-11e7-89cd-b37e165b4daa.png)
  * Figure 3: PyTorch’s nn Package, MNIST Data, Training Time vs. Epoch
  ![image1](https://user-images.githubusercontent.com/31314634/31004191-53822880-a4c1-11e7-9fcd-bbc327f38bed.png)
  * Figure 4: LeNet-5, MNIST Data, Loss vs. Epoch
  ![image1](https://user-images.githubusercontent.com/31314634/31004198-5c414b04-a4c1-11e7-8b19-ade717a43cac.png)
  * Figure 5: LeNet-5, MNIST Data, Accuracy vs. Epoch
  ![image1](https://user-images.githubusercontent.com/31314634/31004197-5c40dd04-a4c1-11e7-901b-448c63f4a5f2.png)
  * Figure 6: LeNet-5, MNIST Data, Training Time vs. Epoch
  ![image1](https://user-images.githubusercontent.com/31314634/31004199-5c41b328-a4c1-11e7-8fd2-fd907b187082.png)
  
* Comments
  * Comparing plots 1 with 4, 2 with 5 and 3 with 6, it can be inferred that there is no significant difference between PyTorch’s nn package and LeNet 5 architecture. 
  * Convergence of loss function, accuracy, training time show similar trend. 
  * However, LeNet-5 affords quicker convergence compared to PyTorch’s nn package in the sense that higher accuracy can be attained with fewer iterations.
  
* Part B
  * Figure 7: LeNet-5, CIFAR-100 Data, Loss vs. Epoch
  ![image1](https://user-images.githubusercontent.com/31314634/31004205-61f6072e-a4c1-11e7-92dd-2ae6361c4907.png)
  * Figure 8: LeNet-5, CIFAR-100 Data, Accuracy vs. Epoch
  ![image1](https://user-images.githubusercontent.com/31314634/31004207-61f634d8-a4c1-11e7-884e-f05fe3f7065f.png)
  * Figure 9: LeNet-5, CIFAR-100 Data, Training Time vs. Epoch
  ![image1](https://user-images.githubusercontent.com/31314634/31004206-61f5f95a-a4c1-11e7-8e93-68905d3ce94e.png)

* Comments
  * Overall accuracy of classification is significantly lower than that of MNIST data. This can be improved by using a better model architecture.
  * It was observed that, validation loss as well as classification accuracy first decreases with number of epoch. But after a point they start increasing.  
  * view() and cam() functions are included as requested.
  
