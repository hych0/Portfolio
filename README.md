# Portfolio
#### Python Machine Learning Projects
- [Regression](#custom-anchor)
  - [CO2RR Catalyst Screening](#custom-anchor1)
  - [Linear Regression](#custom-anchor2)
- [Classification](#custom-anchor3)
- [Image Recognition](#custom-anchor4)
  - [MNIST](#custom-anchor5)
  - [Cifar10, Cifar100](#custom-anchor6)
- [Natural Language Processing](#custom-anchor7)
#### Data Analysis Project
- [Web App of a Catalyst Experimental Dataset](#custom-anchor8)
#### C++ Project
- [Using singly-linked structure to implement stacks and queues](#custom-anchor9)

------------------------------
# Python Machine Learning Projects
----
## <a name="custom-anchor"></a>Regression
### <a name="custom-anchor1"></a>1. CO2RR Catalyst Screening
### [Code](https://github.com/hych0/CO2RRCatalystScreening/blob/main/Main_CO2RR_CatalystScreening.ipynb)

- Implemented “Machine-Learning-Augmented Chemisorption Model for CO2 Electroreduction Catalyst Screening"[1] using TensorFlow, Keras, Scikit-learn, and matplotlib.
- Produced results that show 17.5% improvement in RMSE compared to literature values.
- Produced result:
<img width="615" alt="Screen Shot 2022-09-24 at 3 55 38 PM" src="https://user-images.githubusercontent.com/74970802/192116151-741adb29-1d98-45dc-9100-9d1bf8e69e08.png">

- Literature:
<img width="521" alt="Screen Shot 2022-09-24 at 3 56 19 PM" src="https://user-images.githubusercontent.com/74970802/192116172-153726fd-84a9-46e4-bd84-6072797d6ef3.png">

##### [1] Xin, Hongliang, et al. “Machine-Learning-Augmented Chemisorption Model for CO2 Electroreduction Catalyst Screening.” The Journal of Physical Chemistry Letters, vol. 8, no. 18, 2015, pp. 3528–33, https://doi.org/10.1021/acs.jpclett.5b01660

-------------
### <a name="custom-anchor2"></a>2. Linear regression of a noisy sinewave using a set of gaussian basis functions
### [Code](https://github.com/hych0/DeepLearning/blob/main/DeepLearning1.pdf)
- Used automatic differentiation and stochastic gradient descent to train a set of gaussian basis functions to perform linear regression on a noisy sinewave.
<img width="788" alt="Screen Shot 2022-09-24 at 3 59 12 PM" src="https://user-images.githubusercontent.com/74970802/192116269-d0e9a643-1099-4c9b-95c4-ca7c66627fce.png">

## <a name="custom-anchor3"></a>Classification
Binary classification on the spirals dataset using a multi-layer perceptron
### [Code](https://github.com/hych0/DeepLearning/blob/main/DeepLearning2.pdf)
- Utilized L2 regularization on a multi-layer perceptron model to classify a spirals dataset.
<img width="793" alt="Screen Shot 2022-09-24 at 4 01 10 PM" src="https://user-images.githubusercontent.com/74970802/192116345-df89e635-3d7d-4133-8c74-cbaccfb4bb04.png">

## <a name="custom-anchor4"></a>Image Recognition
## <a name="custom-anchor5">MNIST classification 
### [Code](https://github.com/hych0/DeepLearning/blob/main/DeepLearning3.pdf)
- Acheived >95.5% test accuracy.
- Utilized L2 regularization and dropout to generalize the model and avoid overfitting.
<img width="788" alt="Screen Shot 2022-09-24 at 4 04 01 PM" src="https://user-images.githubusercontent.com/74970802/192116424-26e36284-404e-42f9-bd5c-f35887ee23de.png">

## <a name="custom-anchor6">Cifar10, Cifar100
### [Code](https://github.com/hych0/DeepLearning/blob/main/DeepLearning4.pdf)
- Acheived 92.2% accuracy on Cifar10 and 88.4% (Top-5 accuracy) on Cifar100.
- Utilized L2 regularization and dropout to generalize the model and avoid overfitting.
<img width="632" alt="Screen Shot 2022-10-05 at 4 32 11 PM" src="https://user-images.githubusercontent.com/74970802/194202718-9972c0f2-9e1a-4b0b-ae5c-b249fffb3f69.png">

## <a name="custom-anchor7">Natural Language Processing
### [Code](https://github.com/hych0/DeepLearning/blob/main/DeepLearning5.pdf)
- Acheived 92% accuracy on AGNews dataset.


------------------------------
# Data Analysis Project
------------------------------
## <a name="custom-anchor8"></a>Web App of a Catalyst Experimental Dataset
### [Web App](https://hych0-wgsr-web-app-1eg9of.streamlitapp.com/)
An interactive web app of a water gas shift reaction (WGSR) catalyst experimental dataset.

<img width="335" alt="Screen Shot 2022-09-24 at 4 13 25 PM" src="https://user-images.githubusercontent.com/74970802/192116681-01d2f45b-306f-4e11-bace-fbd472ab60d9.png">

<img width="732" alt="Screen Shot 2022-09-24 at 4 14 08 PM" src="https://user-images.githubusercontent.com/74970802/192116693-40c38170-b42b-448b-a49f-8f01e59084cc.png">

<img width="696" alt="Screen Shot 2022-09-24 at 4 14 24 PM" src="https://user-images.githubusercontent.com/74970802/192116699-f7be7d53-784a-4950-ba8d-c18d1c47bb71.png">

------------------------------
# C++ Project 
------------------------------
## <a name="custom-anchor9"></a>Using singly-linked structure to implement stacks and queues
### [Code](https://github.com/hych0/DataStructuresAndAlgorithms/blob/master/DSA%231/DSA%231.cpp)
- Created a C++ program that utilizes singly linked list structure to implement stacks and queues.
- It reads in a text input and outputs the results from parsing and executing the commands in the text input.
- Input: "commands1.txt"
- Output: "output1.txt"
