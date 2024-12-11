# CS775-Project
This is the code and data for my CS775 Project @UW-Madison

### Project Overview
This project focuses on implementing and extending a multilabel prediction model for molecules. It leverages Python's ecosystem for efficient data processing and model training, based on insights from [MathWorks tutorials](https://www.mathworks.com/help/deeplearning/ug/multilabel-graph-classification-using-graph-attention-networks.html), with the following improvements and extensions:

#### ./multilabel prediction for molecules Folder:

We recreated the dataset using NumPy, optimizing its performance and flexibility.
The model was rebuilt using PyTorch, offering enhanced customization and scalability.

#### ./extension Folder:

We extended the framework by incorporating SMILES strings extracted from other datasets.
Additional label generation algorithms were implemented for improved prediction capabilities.
Structure
multilabel prediction for molecules: Contains the main implementation of the dataset and model for multilabel classification.
extension: Includes extended functionalities such as new datasets, label generation algorithms, and further optimizations.
Requirements
To run this project, install the following dependencies:

Python 3.9
NumPy
PyTorch
PyTorch Geometric
RDKit