# LECTURE01 Installation of TensorFlow

TensorFlow is an open software library of Pyrhon for numerical computation using data flow graphs.

## 1.what is a Data Flow Graph?
- Nodes in the graph represent mathematical operations
- Edges represent the multidimensional data arrays(tensors) communicated between them.

## 2.Installing TensorFlow
### 2.1 
- Linux, Mac OSX, Windows
 - (sudo -H) pip install --upgrade tensorflow
 - (sudo -H) pip install --upgrade tesnorflow-gpu

### 2.2.Check installation and version
> >>import tensorflow as tf
> >>print(tf.__version__)
> **1.4.1**
