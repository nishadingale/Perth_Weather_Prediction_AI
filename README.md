# Rain Prediction in Perth using MLP Neural Network

This project was a part of guided projects from Coursera. Link of the project below. 
https://coursera.org/share/a2c5a3e8e32b000dc72ba0a25b2cc3be

### What did i do in this project?
Used dataset from the Australian Government that was provided in the guiuded project itself.

The aim was to build a neural network in order to predict whether it will rain the next daya based on the data historical collected.
The dataset has more than 20 parameters that determine the weather next day.

Initial step consisted of data exploration and cleaning the data by removing non-relavant columns and "na" values.
Key step was to transform wind direction into cyclical attributes using the Numpy array with the Sin and Cosine functions.
This enables us to ensure that the information within directions are not lost in transformation.

The categorical attributes of "Yes" and "No" whether it will rain tommorow were transformed to 1 or 0 values. This is our target class.

Next step was to standardize the data with respect to the training set. This makes the data have a mean of zero and a standard deviation of 1.

To check the baseline performance,used an input of 25 and 2 layered model with 50 neurons each using MLP Neural network architechture. This yielded 87 percent accuracy.

Used GridsearchCV for optimizing the parameters, and a 2 neuron single hidden layer model yielded best accuracy of 90%.




 

