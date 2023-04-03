## Course 2: Custom and Distributed Training with TensorFlow
Learn how optimization works and how to use GradientTape and Autograph. Optimize training in different environments with multiple processors and chip types.

### Week 1: Differentiation and Gradients
Get an in-depth look at the fundamental building blocks of TensorFlow - tensor objects. Describe the difference between eager mode and graph mode, and explain why eager mode is very user-friendly for developers. Use TensorFlow GradientTape to compute gradients.

- Use various TensorFlow functions to create tensor objects
- Describe the difference between graph-based execution and eager execution in TensorFlow
- Use TensorFlow’s GradientTape to compute derivatives of loss functions

[Lab: Basic Tensors][C2W1U1]  
[Lab: Gradient Tape Basics][C2W1U2]  
[Assignment: Basic Tensor operations and GradientTape][C2W1A1]  

### Week 2: Custom Training
Build custom training loops using GradientTape and TensorFlow Datasets for more flexibility in model training. 

- Define the steps in a custom training loop
- Implement custom training loops using GradientTape
- Implement a custom training loop with data from TensorFlow Datasets

[Lab: Custom Training Basics][C2W2U1]  
[Lab: Fashion MNIST using Custom Training Loop][C2W2U2]  
[Assignment: Breast Cancer Prediction][C2W2A1]  

### Week 3: Graph Mode
Learn about the benefits of generating code that runs in "graph mode". See what graph code looks like, and practice automatically generating this more efficient code using TensorFlow's tools.

- Describe when graph mode code is preferred over eager mode code
- Use decorators and tf.autograph to convert code into graph based code

[Lab: Autograph Basics][C2W3U1]  
[Lab: Graphs for complex code][C2W3U2]  
[Assignment: Horse or Human? In-graph training loop Assignment][C2W3A1]  

### Week 4: Distributed Training
Harness the power of distributed training to handle more data and train larger models faster. Get an overview of different distributed training strategies and practice working with two strategies, one that trains on multiple GPU cores and the other that trains on multiple TPU cores.

- Explain how distributed training is different from regular model training
- Use the Mirrored Strategy to train a model on multiple GPUs on the same device
- Use the TPU Strategy to train on multiple cores of a TPU

[Lab: Mirrored Strategy Basic][C2W4U1]  
[Lab: Multi-GPU Mirrored Strategy][C2W4U2]  
[Lab: TPU Strategy][C2W4U3]  
[Lab: One Device Strategy][C2W4U4]  
[Assignment: Custom training with tf.distribute.Strategy][C2W4A1]  


### Reference
[Coursera - Custom and Distributed Training with TensorFlow](https://www.coursera.org/learn/custom-distributed-training-with-tensorflow?specialization=tensorflow-advanced-techniques)


[C2W1U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W1-Differentiation-and-Gradients/Labs/C2_W1_Lab_1_basic-tensors.ipynb
[C2W1U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W1-Differentiation-and-Gradients/Labs/C2_W1_Lab_2_gradient-tape-basics.ipynb
[C2W1A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W1-Differentiation-and-Gradients/C2W1_Assignment.ipynb

[C2W2U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W2-Custom-Training/Labs/C2_W2_Lab_1_training-basics.ipynb
[C2W2U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W2-Custom-Training/Labs/C2_W2_Lab_2_training-categorical.ipynb
[C2W2A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W2-Custom-Training/C2W2_Assignment.ipynb

[C2W3U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W3-Graph-Mode/Labs/C2_W3_Lab_1_autograph-basics.ipynb
[C2W3U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W3-Graph-Mode/Labs/C2_W3_Lab_2-graphs-for-complex-code.ipynb
[C2W3A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W3-Graph-Mode/C2W3_Assignment.ipynb

[C2W4U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W4-Distributed-Training/Labs/C2_W4_Lab_1_basic-mirrored-strategy.ipynb
[C2W4U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W4-Distributed-Training/Labs/C2_W4_Lab_2_multi-GPU-mirrored-strategy.ipynb
[C2W4U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W4-Distributed-Training/Labs/C2_W4_Lab_3_using-TPU-strategy.ipynb
[C2W4U4]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W4-Distributed-Training/Labs/C2_W4_Lab_4_one-device-strategy.ipynb
[C2W4A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C2-Custom-and-Distributed-Training-with-TensorFlow/W4-Distributed-Training/C2W4_Assignment.ipynb
