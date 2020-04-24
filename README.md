I used Google Colab in RNA & Deep Learning topics. In this case, the development of a monolayer neural network programmed in
Python-Google Colab which learns the hydrodynamic performance of a yacht.

The data was obtained from https://archive.ics.uci.edu/ml/datasets/Yacht+Hydrodynamics# Loaded in Excel and divided. 
70% was used for network training, and 30% for validation. The dataset is made up of 7 attributes, of which 6 are the inputs, 
and the seventh is the output. The training algorithm used is of the RMSProp type.

Finally, I extracted the bias and weight values from the hidden and output layer. This, in order to build the same neural 
network on Arduino. There, I loaded an array of validation values ​​to be read by the neural network and plotted on the
Serial Plotter.

The result obtained is a model, neural network that predicts with considerable accuracy and precision the residual 
resistance of yachts.

In this case, the results are consistent, because the residual resistance is proportional to the Froude number. 
Which is the most influential parameter in the calculation of the mentioned resistance.
