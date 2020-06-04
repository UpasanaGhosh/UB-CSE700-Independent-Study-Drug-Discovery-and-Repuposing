# UB CSE700 Independent-Study: Drug Discovery and Repurposing
## Using Graph Convolutional Networks(GCN) on Tox21 dataset to find the feature molecule
### What are GCNs?
Graph Convolutional Networks are a type of deep learning architectures that are specifically designed to work with life science data. GCN is a powerful neural network architecture for machine learning on molecular data as they can be naturally visualized as graphical structures. GCNs are so powerful that even a randomly initiated 2-layer GCN can produce useful feature representations of the nodes in the networks.

### Approach
We tried out the GCN specific libraries provided by DeepChem for this experiment and followed the DeepChem tutorials to implement the same on Tox21 dataset. The two approaches that we followed to build this GCN model are as follows:

1. We used the already available DeepChem GCN
2. Implementing GCN from scratch using TensorGraphs

### Instructions on how to run the project
The report 'Drug Discovery and Repurposing Report' contains a detailed description about the model implementation, training, evaluation and results that we achieved. The GCN_on_Tox21_dataset.ipynb can be downloaded directly and imported on Google Collab to run the project.
**(The runtime environment should be GPU)**
