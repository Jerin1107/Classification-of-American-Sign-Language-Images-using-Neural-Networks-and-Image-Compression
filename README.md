# Classification of American Sign Language Images using Neural Networks and Image Compression

**Authors:** Jerin Easo Thomas, Shreya Mariam Varghese, Ismail Shaikh  
**Fall 2023**  
**Luddy School of Informatics, Computing and Engineering**  
**Indiana University Bloomington, Bloomington, Indiana**

**Keywords:** Confusion Matrix, Classification Report, Precision, Recall, F1-Score, Keras, Standardization.

## Abstract
The goal of this project is to develop machine learning models employing neural networks for the classification of American Sign Language (ASL) movements. The aim is to improve digital accessibility for the deaf and hard-of-hearing community by addressing the challenge of understanding a language primarily based on visual signals. The research also explores image compression techniques such as Principal Component Analysis (PCA) and Singular Value Decomposition (SVD).

## 1. Introduction
The project addresses the communication gap between the rapidly evolving digital world and the deaf and hard-of-hearing community, focusing on the essential means of communication, American Sign Language (ASL). Lack of reliable technology solutions for ASL interpretation in digital environments is a significant obstacle.

### 1.1 Motivation
The motivation behind this project is to enhance accessibility and inclusivity in digital communication. With the growing use of digital platforms for various purposes, ensuring accessibility for all users, including those who rely on ASL, becomes crucial. The project aims to develop machine learning models to classify ASL motions accurately, laying the foundation for real-time ASL-to-text or speech translation technologies.

## 3. Methods
### Image Classification
- Image classification is performed using convolutional neural networks (CNNs) for ASL gesture recognition.
- The process involves extracting features from images such as colors, forms, textures, and patterns.
### Image Compression
- Image compression techniques like PCA and SVD are explored to reduce the size of image files effectively.
- Compression aids in managing large datasets and real-time applications.
### Neural Networks
- Neural networks, modeled after the human brain, are utilized for their efficiency in handling complex tasks like image categorization.
- TensorFlow, particularly its Keras API, is employed for its deep learning capabilities and ease of use.

#### 3.1 Implementation
- Image compression is implemented using PCA and SVD to reduce data size without sacrificing essential information.
- Deep Neural Network (DNN), Convolutional Neural Network (CNN), Visual Geometry Group Network (VGGNet), Residual Network (ResNet), and Ensemble models are implemented and trained using TensorFlow/Keras.
- Training and validation accuracy, loss, and other metrics are monitored and analyzed for each model.

## 4. Experimental Setup
- Google Colab is used for experimentation, leveraging its GPU resources.
- The dataset consists of ASL alphabet images, partitioned into training and test sets.
- Data augmentation techniques are applied using the ImageDataGenerator class from Keras to prevent overfitting.

## 5. Results
- Performance metrics, including training and validation accuracy, loss, confusion matrix, and classification report, are analyzed for each model.
- The Ensemble model outperforms individual models, achieving the highest accuracy on the test set.

## 6. Conclusion
- The Ensemble approach demonstrates superior performance in ASL image classification.
- By combining multiple models, the Ensemble leverages the strengths of each model, resulting in better generalization and higher accuracy.
- The Ensemble strikes a balance between predictive performance and training efficiency, making it an effective solution for ASL classification tasks.

