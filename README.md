
In this project, we became familiar with the challenges of creating a good model by implementing a neural network model on two different datasets and addressing these challenges. Additionally, we used pre-trained models to compare their performance with the model we created. Finally, we visualized the weights of the convolutional layers of these trained networks to gain a better understanding of their learning and role in the training process. We plotted the trend graph showing the accuracy of our model on the Train and Validation data after training each model in phases one and two.

**Phase One**

In this section, we created a model that included at least Convolutional and Fully Connected layers after loading and reviewing the CIFAR-10 dataset. The model achieved good accuracy and performance on Train, Validation, and Test data (we added other layers and techniques to increase accuracy and overcome challenges, understanding their application and functionality).

**Phase Two**

In this phase, we adapted the model designed in the previous phase for the Pet IIIT-Oxford dataset. We used Data Augmentation to improve our model's performance and visualized the changes made to a sample of the dataset's images. Our model did not overfit or underfit, and we increased and optimized our model's accuracy for all parts of the data.

**Phase Three**

In this section, we used three models—ResNet-18, MobileNetV2, and GoogLeNet—for Transfer Learning and retraining on the Pet IIIT-Oxford dataset. (When programming with TensorFlow, we used ResNet-50 instead of ResNet-18 and InceptionV3 instead of GoogLeNet.) We stated the accuracy of each model for the dataset and compared the results of the models. We made necessary changes to the models' structures for this task.
- We paid attention to the number of classes in the dataset and edited the final layer of each model accordingly.
- We changed and improved the retraining process of the models by freezing certain layers.
- We visualized a few images for each model with their actual and predicted labels.

---
