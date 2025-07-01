# Neural Network from Scratch

I have attempted to make a neural network from scratch without using libraries like tensorflow and pytorch. This [tutorial](https://medium.com/@waadlingaadil/learn-to-build-a-neural-network-from-scratch-yes-really-cac4ca457efc) from Medium helped me understand how neural networks actually function behind the scenes.

## Datset Used
The [diabetes.csv](https://www.kaggle.com/datasets/mathchi/diabetes-data-set) dataset is taken from Kaggle.

## Features
The custom neural network has the following added functionalities:
+ Fully customisable layers
+ Learning Rate reduction based on a performance metric
+ Early Stopping based on a performance metric
+ Saving best weights

## Performance
The network achieved a 0.8168 F1-score (macro average) and an accuracy of 83.3% on the validation set.

## Installation
1. Clone this repository by:
   `git clone https://github.com/Dheemant19/Neural-Network-from-Scratch.git`
   then navigate `cd` to the folder where the repository is cloned.
2. Install libraries by:
   `pip install -r requirements.txt`
3. Open the Jupyter notebook and run individual blocks as is or customize as you wish.

