# SelfOrganizingMapMNIST
This is the project for the exam Data Mining at the University of Florence for the master in Data Analytics, Management and Security.

## Project Objectives 
The Self Organizing Map is a type of artificial neural network trained using unsupervised learning for dimensionality reduction problems. This ANN produces a low dimensional representation of the input space of training examples.

This implementation focused on 
* developing a specific termination training
* 2d heatmap visualization of the SOM
* testing system with a graphical representation and data tables for the neuron classification

## Tools
* TensorFlow
* Mnist Dataset (handwritten digits)
* Self Organizing Map

## Dataset
The dataset used is the MNIST dataset for handwritten digits.

<img src="https://i2.wp.com/dataaspirant.com/wp-content/uploads/2017/05/Mnist-database-hand-written-digits.png?w=530" width="300">

The network has been trained and tested respectively:

| Training size | Testing size |
| ------------- | ------------- |
| 20000 | 5000 |
| 50000  |5000 |
| 20000 | 20000 |

## Results

* The termination mechanism developed works really well and to understand how it works you can read the paper in this repository.
* The heatmap representation of the SOM gives an idea of the imput space with its dimension reduce to a 2d space.
* The results in the tables are confirmed with the graphical representatio and the SOM implemented works best with the dimensions 14x14 with 20000 images as training and 16x16 with 50000 images as trainig.




