## Course 1: Custom Models, Layers, and Loss Functions with TensorFlow
Understand the underlying basis of the Functional API and build exotic non-sequential model types, custom loss functions, and layers. 

### Week 1: Functional APIs
Compare how the Functional API differs from the Sequential API, and see how the Functional API gives you additional flexibility in designing models. Practice using the functional API and build a Siamese network!

- Review the Sequential API and compare it to the Functional API
- Describe new model types that can be built with the Functional API
- Functional API: define input, layers, and model
- Use the Functional API to build a model
- Use the Functional API to create a model that produces multiple outputs
- Use the Functional API to build a Siamese network

[Lab: Practice with the Keras Functional API][C1W1U1]  
[Lab: Build a Multi-output Model][C1W1U2]  
[Lab: Implement a Siamese network][C1W1U3]  
[Assignment: Functional APIs][C1W1A1]  

### Week 2: Custom Loss Functions
Loss functions help measure how well a model is performing and are used to help a neural network learn from training data. Learn how to create custom loss functions, including the contrastive loss function used in a Siamese network.

- Describe when you need to build a custom loss function
- Implement Huber Loss with a custom loss function
- Add an adjustable hyperparameter to a custom loss using a wrapper function
- Define a custom loss using an object oriented class
- Implement the contrastive loss function used in a Siamese network

[Lab: Huber Loss][C1W2U1]  
[Lab: Huber Loss hyperparameter and class][C1W2U2]  
[Lab: Implement a Siamese network][C1W2U3]  
[Assignment: Custom Loss Functions][C1W2A1]  

### Week 3: Custom Layers
Custom layers give you the flexibility to implement models that use non-standard layers. Practice building on existing standard layers to create custom layers for your models. 

- Define a custom layer to include the activation function
- Define a custom layer class by inheriting from the Layer class
- Describe the two components of a custom layer
- Describe what a custom layer can do that a lambda layer cannot
- Use a lambda layer to customize a network layer

[Lab: Lambda Layer][C1W3U1]  
[Lab: Building a Custom Dense Layer][C1W3U2]  
[Lab: Activation in Custom Layers][C1W3U3]  
[Assignment: Custom Layers][C1W3A1]  

### Week 4: Custom Models
You can build on existing models to add custom functionality. Extend the TensorFlow Model Class to build a ResNet model!

- Explain some of the advantages of defining a custom model class instead of using the functional or sequential APIs.
- Define a model by creating a Python class that inherits from the TensorFlow Model class
- Describe functions that can be inherited from the TensorFlow Model class
- Build a residual network by defining a custom model class

[Lab: Coding a Wide and Deep Model][C1W4U1]  
[Lab: Implementing ResNet][C1W4U2]  
[Assignment: Custom Models][C1W4A1]  


### Reference
[Coursera - Custom Models, Layers, and Loss Functions with TensorFlow](https://www.coursera.org/learn/custom-models-layers-loss-functions-with-tensorflow?specialization=tensorflow-advanced-techniques)


[C1W1U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W1-Functional-APIs/Labs/C1_W1_Lab_1_functional-practice.ipynb
[C1W1U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W1-Functional-APIs/Labs/C1_W1_Lab_2_multi-output.ipynb
[C1W1U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W1-Functional-APIs/Labs/C1_W1_Lab_3_siamese-network.ipynb
[C1W1A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W1-Functional-APIs/C1W1_Assignment.ipynb

[C1W2U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W2-Custom-Loss-Functions/Labs/C1_W2_Lab_1_huber-loss.ipynb
[C1W2U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W2-Custom-Loss-Functions/Labs/C1_W2_Lab_2_huber-object-loss.ipynb
[C1W2U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W2-Custom-Loss-Functions/Labs/C1_W1_Lab_3_siamese-network.ipynb
[C1W2A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W2-Custom-Loss-Functions/C1W2_Assignment.ipynb

[C1W3U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W3-Custom-Layers/Labs/C1_W3_Lab_1_lambda-layer.ipynb
[C1W3U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W3-Custom-Layers/Labs/C1_W3_Lab_2_custom-dense-layer.ipynb
[C1W3U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W3-Custom-Layers/Labs/C1_W3_Lab_3_custom-layer-activation.ipynb
[C1W3A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W3-Custom-Layers/C1W3_Assignment.ipynb

[C1W4U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W4-Custom-Models/Labs/C1_W4_Lab_1_basic-model.ipynb
[C1W4U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W4-Custom-Models/Labs/C1_W4_Lab_2_resnet-example.ipynb
[C1W4A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C1-Custom-Models-Layers-and-Loss-Functions-with-TensorFlow/W4-Custom-Models/C1W4_Assignment.ipynb
