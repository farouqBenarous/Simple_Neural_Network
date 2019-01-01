# Simple_Neural_Net

Simple neural network using pure python 

# Helpfull Informations about the code 
you can run the code using python3 demo.py

Activation function : Sigmoid (of course you can change it you just have to go to NeuralNetwork class nd change it )

Coast reducing Algorithm : BackPropagation

NeuralNetwork Class contain four functions  

 1)- __sigmoid  activation function to do the forward Propagation 

2)- __sigmoid_derivative  to do the BackPropagation 

3)- think takes as parameter your input and returns the new weights , and of course it uses  the sigmoid 

4)- train it took as parametre the dataset(input + output ) and the number of iterations  : so first it will calculate the     output
based on the inputes after that it will calculate the error rate (the correct output in the dataset - output that we got  )
  and then it will calculate the adjusment that we have to do in order to get the correct output (using __sigmoid_derivative)
  and Finaly Update the weights 
