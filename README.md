# Logistic_Regression_as_a_Neural_Network

This repo presents my own implementation for an image recognition algorithm, and more specifically a logistic regression cat classifier, from Coursera's "Deep Learning Specialization". For this project I implemented logistic regression as a neural network to minimize the loss and calculate the cost derivatives for updating the network's parameters, in order to correctly classify pictures as cat or non-cat.

More concretely, the architecture of the learning algorithm is as follows:

   1) Parameter initialization
   2) Iterative calculation of the loss and its gradient
   3) Iterative optimization (with gradient descent)
   4) Generation of predictions

Eventually I combined all the separate functions that deal with the aforementioned tasks into a main model function and further analysed the results.

<ins>How to run</ins>

- Install the `numpy` module. [(pypi link](https://pypi.org/project/numpy/) [/ numpy link)](https://numpy.org/)
- Install the `matplotlib` module. [(pypi link](https://pypi.org/project/matplotlib/) [/ matplotlib link)](https://matplotlib.org/)
- Install the `h5py` package. [(pypi link](https://pypi.org/project/h5py/) [/ h5py info)](http://www.h5py.org/)
- Install the `PIL` package. [(pypi link](https://pypi.org/project/Pillow/) [/ pillow link)](https://python-pillow.org/)
- Install the `scipy` module. [(pypi link](https://pypi.org/project/scipy/) [/ scipy link)](https://www.scipy.org/)

Hint: The initial train and test datasets are not included as they are property of Coursera.
