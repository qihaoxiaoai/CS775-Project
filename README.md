# CS775-Project
### Overview
This is the code and data for my CS775 Project @UW-Madison
We can utilize Graph Machine Learning model to predict the labels of a given molecule, such as functional groups and fragment annotations.

We constructed the adjacency matrix, labels, and features using [RDKit](https://github.com/rdkit/rdkit.git) and the [Ertl algorithm](https://jcheminf.springeropen.com/articles/10.1186/s13321-017-0225-z). These data were saved in .npy format for features and .json format for labels. Functional groups of certain molecules were annotated, and a molecule could have none or multiple labels, represented in a one-hot encoding format. Based on PyTorch Geometric (PyG), we implemented models using GAT, GCN, and GraphSAGE. This aligns with my research interests, particularly the influence of fragment structures on the properties of polymers. If you are interested, feel free to reach out to me at my email: qihaoxiaoai@gmail.com.
#### To run this project, install the following dependencies:
Python 3.9
NumPy
PyTorch
PyTorch Geometric
RDKit

### Files Intro
#### ./demo:
We recreated the dataset using NumPy, optimizing its performance and flexibility. The model was rebuilt using PyTorch, offering enhanced customization and scalability.

#### ./Different Models:
Based on PyTorch Geometric (PyG), we implemented models using GAT, GCN, and GraphSAGE. Both the implementation and experiments can be conducted within the corresponding Jupyter notebooks.
