# Investigation-on-Neural-Network-for-RSSI-based-localization
A neural network model is used for investigation of localization accuracy.  
The concept of neural network is used for indoor localization, In our previous work a embedded and Machine learning approaches we have studied, this work is the extension of the previous work in order to obtained a better performance of the model, so Matlab is used to train the neural network model where we have investigated a different algorithm for training and testing, which describes below, We have trained the model on 10 hidden neurons with 4x768 input and 2x768 output matrix.
The RSSI value is collected with median of 12 samples for each reading. The data is splitted in three sections as: 
 
## 1. Training 
These are presented to the network during training, and the network is adjusted according to its error.
## 2. Validation
These are used to measure network generalization, and to halt training when generalization stops improving, 15% of the data is taken for validation.
## 3. Testing 
These have no effect on training and so provide an independent measure of network performance during and after training, 15% of the data is taken for testing.


## NN Model with input and output for Levenberg-Marquardt and Bayesian regularization algorithms. 
![image](https://user-images.githubusercontent.com/32608510/39860696-d98c4772-545b-11e8-83dc-21bc89c39ef0.png)

## 2. Training of model using Levenberg-Marquardt backpropagation 
![image](https://user-images.githubusercontent.com/32608510/39859628-15fc5340-5458-11e8-948a-d345500c950a.png)

## 2.2 Error Histogram  
![image](https://user-images.githubusercontent.com/32608510/39860649-b11cc69a-545b-11e8-999e-c8fc21e0f9bf.png)

## 2.3 Regression plot
![image](https://user-images.githubusercontent.com/32608510/39860672-c2929d78-545b-11e8-8fb2-495aed22b6e5.png)

## 2.4 Mean Square error with number of epochs 
![image](https://user-images.githubusercontent.com/32608510/39860688-d0386462-545b-11e8-9305-2cb87cb70d62.png)


## 3. Training of model with Bayesian regularization 

## 3.1 Error Histogram 
![image](https://user-images.githubusercontent.com/32608510/39861337-edc2baee-545d-11e8-95f3-a5ed0e5c750b.png)

## 3.2 Regression plot
![image](https://user-images.githubusercontent.com/32608510/39861376-0a93e0d0-545e-11e8-90c6-87c44a368571.png)

## 3.3 Mean Square error with number of epochs 
![image](https://user-images.githubusercontent.com/32608510/39861348-f791bb7e-545d-11e8-9a2f-e0ebeeba2a3c.png)
