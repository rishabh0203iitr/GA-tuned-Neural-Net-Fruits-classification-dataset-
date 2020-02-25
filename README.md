# Genetic Algorithm tuned Deep Neural Network

Using Genetic Algorithm to optimize the weights in a deep neural network for Fruits-Classification dataset

### Prerequisites

Before running the code install the following python libraries

* numpy
* pymoo
* deap

```
pip install numpy
pip install pymoo
pip install deap
```

### Training the Model

The neural network is developed entirely by using only numpy library. The initial population of the weights are generated randomly, and the fitness of all the models is calculated. The best population is selected according to the fitness function and crossover and mutation is susequntly applied to get new population.


### Results

The Neural Network reaches 99% training accuracy.
![Accuracy Graph](https://github.com/rishabh0203iitr/GA-tuned-Neural-Net-Fruits-classification-dataset-/blob/master/accuracy%20graph.PNG)

This can be further improved by adding Convolutional layers to the network which will enhance its feature extraction capabilities.

### Authors

* **Yash Vardhan Sharma** 
* [Rishabh Sharma](https://github.com/rishabh0203iitr)

### Acknowledgments

* Ahmed Ghad
* Ali Ghodsi
