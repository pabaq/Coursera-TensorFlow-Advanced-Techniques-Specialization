## Course 4: Generative Deep Learning with TensorFlow
Explore generative deep learning and how AI can create new content, from style transfer through auto-encoding and VAEs to Generative Adversarial Networks.

### Week 1: Style Transfer
Extract the content of an image and the style of a painting and combine them into a new image using transfer learning.

- Describe how total variation loss ensures spatial continuity and smoothness
- Explore the benefits of fast neural style transfer over traditional DCNN
- Define style transfer
- Gain an intuitive understanding of the gram matrix
- Describe the steps required to calculate loss

[Lab: Neural Style Transfer][C4W1U1]  
[Lab: Fast Neural Style Transfer][C4W1U2]  
[Assignment: Neural Style Transfer][C4W1A1]  

### Week 2: AutoEncoders
Get an overview of AutoEncoders and how to build them with TensorFlow. Build a simple AutoEncoder on the familiar MNIST dataset, before diving into more complicated deep and convolutional architectures on the Fashion MNIST dataset. See the difference in results between the DNN and CNN AutoEncoder models, and then identify ways to denoise noisy images.

- Build your first AutoEncoder with TensorFlow
- Build an AutoEncoder on MNIST
- Build a DNN AutoEncoder on MNIST
- Build a CNN AutoEncoder on Fashion MNIST
- Build a Noisy CNN AutoEncoder on Fashion MNIST

[Lab: First Autoencoder][C4W2U1]  
[Lab: MNIST Autoencoder][C4W2U2]  
[Lab: MNIST Deep Autoencoder][C4W2U3]  
[Lab: Convolutional Autoencoders][C4W2U4]  
[Lab: Denoising with a CNN Autoencoder][C4W2U5]  
[Assignment: CIFAR-10 Autoencoder][C4W2A1]  

### Week 3: Variational AutoEncoders
Explore Variational AutoEncoders (VAEs) to generate entirely new data.

- Train your own VAE model
- Use a loss function to calculate the loss value
- Use a decoder to generate new data
- Use a sample layer to encode the architecture
- Describe the VAE architecture and code
- Define Variational AutoEncoders (VAEs)

[Lab: Variational Autoencoders][C4W3U1]  
[Assignment: Variational Autoencoders on Anime Faces][C4W3A1]  

### Week 4: GANs
Learn about GANs, what they are, who invented them, their architecture, and how they differ from VAEs. See the function of the generator and the discriminator within the model, as well as the concept of two training phases and the role of introduced noise.

- Design your first GAN architecture
- Train a GAN
- Build your first GAN
- Build a DCGAN on Fashion MNIST
- Build a face generator GAN on the Celebrity dataset

[Lab: First GAN with MNIST][C4W4U1]  
[Lab: First DCGAN][C4W4U2]  
[Lab: CelebA GAN Experiments][C4W4U3]  
[Assignment: GANs with Hands][C4W4A1]  


### Reference
[Coursera - Generative Deep Learning with TensorFlow](https://www.coursera.org/learn/generative-deep-learning-with-tensorflow?specialization=tensorflow-advanced-techniques)


[C4W1U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W1-Style-Transfer/Labs/C4_W1_Lab_1_Neural_Style_Transfer.ipynb
[C4W1U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W1-Style-Transfer/Labs/C4_W1_Lab_2_Fast_NST.ipynb
[C4W1A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W1-Style-Transfer/C4W1_Assignment.ipynb

[C4W2U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W2-AutoEncoders/Labs/C4_W2_Lab_1_FirstAutoEncoder.ipynb
[C4W2U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W2-AutoEncoders/Labs/C4_W2_Lab_2_MNIST_Autoencoder.ipynb
[C4W2U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W2-AutoEncoders/Labs/C4_W2_Lab_3_MNIST_DeepAutoencoder.ipynb
[C4W2U4]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W2-AutoEncoders/Labs/C4_W2_Lab_4_FashionMNIST_CNNAutoEncoder.ipynb
[C4W2U5]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W2-AutoEncoders/Labs/C4_W2_Lab_5_FashionMNIST_NoisyCNNAutoEncoder.ipynb
[C4W2A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W2-AutoEncoders/C4W2_Assignment.ipynb

[C4W3U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W3-Variational-AutoEncoders/Labs/C4_W3_Lab_1_VAE_MNIST.ipynb
[C4W3A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W3-Variational-AutoEncoders/C4W3_Assignment.ipynb

[C4W4U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W4-GANs/Labs/C4_W4_Lab_1_basic-model.ipynb
[C4W4U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W4-GANs/Labs/C4_W4_Lab_2_resnet-example.ipynb
[C4W4U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W4-GANs/Labs/C4_W4_Lab_3_CelebA_GAN_Experiments.ipynb
[C4W4A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C4-Generative-Deep-Learning-with-TensorFlow/W4-GANs/C4W4_Assignment.ipynb
