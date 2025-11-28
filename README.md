![image alt](https://github.com/priyanshubhaskar1/Cloth_Classification_cnn/blob/034a63028adeb4abac0c888b259acbca363548c6/9-class-clothing-classification-using-CNN.png)

✅ **Model Description**

This project implements a deep learning–based image classification model built using the Xception Convolutional Neural Network (CNN) architecture. The model is designed to perform multi-class image classification with high accuracy by leveraging transfer learning on a pre-trained network.

The model is developed using TensorFlow and Keras, ensuring scalability, performance efficiency, and easy deployment.

🔹**Architecture Overview**

Base Model: Xception (pre-trained on ImageNet)

Top Layers: Custom fully connected layers added for task-specific learning

Pooling Layer: Global Average Pooling

Activation Functions:

ReLU (hidden layers)

Softmax (output layer)

Output Classes: 4 (Multi-class classification)

🔹**Model Workflow**

Input images are resized to 299×299×3

Feature extraction is performed using pre-trained Xception

Deep features are passed through:

Global Average Pooling

Dense Layer (128 neurons)

Output Dense Layer (4 neurons with Softmax)

The model predicts the final class probabilities

🔹**Training Configuration**

Optimizer: Adam

Loss Function: Categorical Crossentropy

Metrics: Accuracy

Epochs: 10

Batch Size: 32

Dataset Type: Image dataset loaded using image_dataset_from_directory

🔹**Performance Evaluation**

The trained model is evaluated using the following metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score (Coefficient of Determination)

These metrics provide insights into both classification performance and prediction stability.

🔹**Key Features of the Model**

✅ Uses transfer learning for faster convergence and improved accuracy

✅ Works efficiently with small and medium-scale datasets

✅ Reduces overfitting using pre-trained feature extraction

✅ Fully compatible with Kaggle and cloud-based environments

✅ Can be easily extended to other image classification tasks

🔹**Applications**

This model can be adapted for:

Image-based medical diagnosis

Object classification

Industrial defect detection

Smart surveillance systems

E-commerce product categorization

✅** Summary**

This model demonstrates the practical implementation of transfer learning using Xception for high-accuracy image classification. It combines powerful pre-trained feature extraction with custom classification layers to deliver efficient, scalable, and production-ready performance


**Clothing dataset** (subset)

This project makes use of a publicly available dataset provided by [Alexey Grigorev](https://github.com/alexeygrigorev) through his GitHub repository. I sincerely acknowledge and thank him for sharing high-quality, well-structured, and openly accessible data for educational and research purposes.

The dataset has played a crucial role in training and evaluating the deep learning model used in this project. His contribution to the open-source community has significantly supported students and developers in building real-world machine learning applications.

All rights and credits for the original dataset remain with the original author. This project strictly uses the data for educational and non-commercial research purposes, with full respect to the creator’s ownership and contribution.

This is a subset of the full clothing dataset with the top-10 most popular classes.

This dataset can be freely used for any purpose. For example:

* Training a model for self-education
* Creating a tutorial or a course (free or paid)
*Writing a book
**Examples**

https://github.com/alexeygrigorev/mlbookcamp-code/blob/master/chapter-07-neural-nets/07-neural-nets-train.ipynb
Add a link here
Do you use this dataset somewhere? Please submit a PR with a link

**Acknowledgements**

We'd like to thank

*Kenes Shangereyev and [Tagias.com](https://github.com/alexeygrigorev/clothing-dataset-small/blob/master/tagias.com) for helping with 3000 images

All the 32 people who contributed their images to the dataset via the forms:
* [Patricia Goldberg](https://www.linkedin.com/in/patricia-goldberg/)
* [Chandana Priya](https://www.linkedin.com/in/chandanapriyanivarthi/)
 
Everyone who supported the initiative by engaging with the announcements on social media
It wouldn't be possible to collect this dataset without your help!
