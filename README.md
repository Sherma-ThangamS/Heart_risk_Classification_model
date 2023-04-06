# Heart_risk_Classification_model

Heart Risk is a project that uses logistic regression to predict the risk of heart disease based on a set of features. The project is implemented in Python using the NumPy and Pandas libraries.


Installation


To run this project, you will need to have Python 3 installed on your system along with the following libraries:

numpy
pandas
You can install these libraries using pip. For example:

pip install numpy
pip install pandas

Usage


To run this project, you can follow these steps:

Clone this repository to your local machine.
Navigate to the project directory using the terminal.
Run the heart_risk.py file using Python.

python heart_risk.py


This will perform logistic regression on the heart disease dataset and print the accuracy of the model.



How It Works


The heart risk project reads in the heart disease dataset and splits it into features and labels. The features are then normalized using mean normalization. The logistic regression algorithm is implemented using gradient descent, where the weights and bias are updated based on the gradient of the loss function with respect to these parameters. The sigmoid function is used to convert the logits into probabilities, which are then rounded to obtain the predicted labels. Finally, the accuracy of the model is computed by comparing the predicted labels to the true labels.



Contact


If you have any questions or suggestions about this project, feel free to contact me at sshermathangam@gmail.com.
