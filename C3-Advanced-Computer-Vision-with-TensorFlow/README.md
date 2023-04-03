## Course 3: Advanced Computer Vision with TensorFlow
Practice object detection, image segmentation, and visual interpretation of convolutions.

### Week 1: Introduction to Computer Vision
Gain a conceptual overview of image classification, object localization, object detection, and image segmentation. Also be able to describe multi-label classification, and distinguish between semantic segmentation and instance segmentation. Use TensorFlow to build models for object detection and image segmentation.

- Distinguish between object localization and object detection
- Distinguish between object detection and image segmentation
- Distinguish between semantic segmentation and instance segmentation
- Explain what transfer learning is and why it's used
- Describe design options when using transfer learning
- Implement object localization using a CNN
- Implement an image classifier using transfer learning

[Lab: Basic transfer learning with cats and dogs data][C3W1U1]  
[Lab: Transfer Learning with ResNet 50][C3W1U2]  
[Lab: Image Classification and Object Localization][C3W1U3]  
[Assignment: Predicting Bounding Boxes][C3W1A1]  

### Week 2: Object Detection
Get an overview of some popular object detection models, such as regional-CNN and ResNet-50. Use and configure object detection models from the TensorFlow Hub for training, and build your own object detection models. Use transfer learning to train a model to detect and localize rubber duckies with just five training examples.

- Get a conceptual overview of Regional CNN (R-CNN), Fast-RCNN, and Faster R-CNN
- Retrieve the R-CNN model from the TensorFlow hub and use it to perform object detection
- Use TensorFlow’s object detection API to visualize the predicted bounding boxes from an object detection model
- Go beyond the models in the TensorFlow Hub: Load and configure a Resnet-50 model that isn’t on TensorFlow Hub, restore pre-trained weights, and select which parts of the model to retrain.
- Use the object detection API to manually annotate images for object detection
- Implement a custom training loop to fine-tune a model with as few as 5 training examples.

[Lab: Simple Object Detection in Tensorflow][C3W2U1]  
[Lab: Object Detection][C3W2U2]  
[Lab: TensorFlow Hub Object Detection Colab][C3W2U3]  
[Lab: Eager Few Shot Object Detection Colab][C3W2U4]  
[Assignment: Zombie Detection][C3W2A1]  

### Week 3: Image Segmentation
Use variations of the fully convolutional neural network for image segmentation. Assign class labels to each pixel, and perform much more detailed object identification compared to bounding boxes. Build the fully convolutional neural network, U-Net, and Mask R-CNN to identify and detect numbers, pets, and zombies!

- Describe the conceptual design of fully convolutional neural networks and subsequent models based on them
- Describe the decoder part of a fully convolutional neural network
- Describe two methods of upsampling: simple scaling and transposed convolutions
- Build the encoder and decoder sections of a fully convolutional neural network
- Evaluate the performance of a segmentation model using intersection-over-union and dice score
- Describe the conceptual design of the U-Net model
- Build a U-Net model for image segmentation
- Use the Mask R-CNN to perform instance segmentation

[Lab: Fully Convolutional Neural Networks for Image Segmentation][C3W3U1]  
[Lab: U-Net for Image Segmentation][C3W3U2]  
[Lab: Mask R-CNN Image Segmentation Demo][C3W3U3]  
[Assignment: Image Segmentation of Handwritten Digits][C3W3A1]  

### Week 4: Visualization and Interpretability
Learn about the importance of model interpretability, which is the understanding of how your model arrives at its decisions. Implement class activation maps, saliency maps, and gradient-weighted class activation maps to identify which parts of an image a model uses to make its predictions. See an example of how visualizing a model’s intermediate layer activations can help to improve the design of a famous network, AlexNet.

- Explain why model interpretation is important
- Calculate class activation maps to visualize the parts of the image that a model uses to make its predictions.
- Calculate saliency maps to visualize the parts of the image that a model uses to make its predictions.
- Implement Gradient-weighted Class Activation Mapping (GradCAM) to identify parts of the image that are important to a model’s predictions.
- Describe how visualization can help to improve the design of a model

[Lab: Class Activation Maps with Fashion MNIST][C3W4U1]  
[Lab: Cats vs Dogs Class Activation Maps][C3W4U2]  
[Lab: Saliency][C3W4U3]  
[Lab: GradCAM][C3W4U4]  
[Assignment: Saliency Maps][C3W4A1]  


### Reference
[Coursera - Advanced Computer Vision with TensorFlow](https://www.coursera.org/learn/advanced-computer-vision-with-tensorflow?specialization=tensorflow-advanced-techniques)


[C3W1U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W1-Introduction-to-Computer-Vision/Labs/C3_W1_Lab_1_transfer_learning_cats_dogs.ipynb
[C3W1U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W1-Introduction-to-Computer-Vision/Labs/C3_W1_Lab_2_Transfer_Learning_CIFAR_10.ipynb
[C3W1U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W1-Introduction-to-Computer-Vision/Labs/C3_W1_Lab_3_Object_Localization.ipynb
[C3W1A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W1-Introduction-to-Computer-Vision/C3W1_Assignment.ipynb

[C3W2U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W2-Object-Detection/Labs/C3_W2_Lab_1_Simple_Object_Detection.ipynb
[C3W2U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W2-Object-Detection/Labs/C3_W2_Lab_2_Object_Detection.ipynb
[C3W2U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W2-Object-Detection/Labs/Object_Detection_Inference_on_TF_2_and_TF_Hub.ipynb
[C3W2U4]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W2-Object-Detection/Labs/interactive_eager_few_shot_od_training_colab.ipynb
[C3W2A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W2-Object-Detection/C3W2_Assignment.ipynb

[C3W3U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W3-Image-Segmentation/Labs/C3_W3_Lab_1_VGG16_FCN8_CamVid.ipynb
[C3W3U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W3-Image-Segmentation/Labs/C3_W3_Lab_2_OxfordPets_UNet.ipynb
[C3W3U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W3-Image-Segmentation/Labs/C3_W3_Lab_3_Mask_RCNN_ImageSegmentation.ipynb
[C3W3A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W3-Image-Segmentation/C3W3_Assignment.ipynb

[C3W4U1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W4-Visualization-and-Interpretability/Labs/C3_W4_Lab_1_FashionMNIST_CAM.ipynb
[C3W4U2]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W4-Visualization-and-Interpretability/Labs/C3_W4_Lab_2_CatsDogs_CAM.ipynb
[C3W4U3]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W4-Visualization-and-Interpretability/Labs/C3_W4_Lab_3_Saliency.ipynb
[C3W4U4]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W4-Visualization-and-Interpretability/Labs/C3_W4_Lab_4_GradCam.ipynb
[C3W4A1]: https://nbviewer.jupyter.org/github/pabaq/Coursera-TensorFlow-Advanced-Techniques-Specialization/blob/main/C3-Advanced-Computer-Vision-with-TensorFlow/W4-Visualization-and-Interpretability/C3W4_Assignment.ipynb
