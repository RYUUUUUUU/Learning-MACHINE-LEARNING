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
 ~~~
import tensorflow as tf
print(tf.__version__)
**1.4.1**
 ~~~

## 3.Basic of TensorFlow

### 3.1.TensorFlow Hello World!
 ~~~
#Create a constant op
#this op is added as a node to the default graph
hello = tf.constant("hello, TensorFlow!")

#Create a TF session
sess = tf.Session()

#Run the op and get result
print(sess.run(hello))
 ~~~
