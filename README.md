# Nutrieasy Model - Fruit and Vegetable Classification for Fruit and Vegetable Nutrition Detection

This project aims to classify fruits and vegetables and detect the nutrients of fruits and vegetables using Convolutional Neural Network (CNN) in Python and TensorFlow. This project uses image data to identify the nutrition of fruits and vegetables based on the given image.

## [1] Dataset

The dataset used consists of images of fruits and vegetables with their corresponding labels. The dataset is divided into two main categories: "Fruits Classification" and "Vegetable Classifications".

Dataset Kaggle :
1. Fruits Dataset : https://www.kaggle.com/datasets/keycia/fruit-nutrionix
2. Vegetables Dataset : https://www.kaggle.com/datasets/keycia/vegetables-nutrionix

### Classification of Fruits 
This dataset contains images of whole fruit and pieces of fruit consisting of 44 fruit classes, such as:
* 🍎 Apple (Apel)
* 🥑 Avocado (Alpukat)
* 🍌 Banana (Pisang)
* 🍒 Cherries (Ceri)
* 🥥 Coconut (Kelapa)
* 🍇 Grape (Anggur)
* 🍋 Lemon (Lemon)
* 🥭 Mangga (Mangga)
* 🍉 Watermelon (Semangka) etc.

### Classification of Fruits and Vegetables
This dataset contains images of whole vegetables and vegetable cuts consisting of 22 vegetable classes, such as:
* 🥦 Broccoli (Brokoli)
* 🥕 Carrot (Wortel)
* 🌽 Corn (Jagung)
* 🥒 Cucumber (Mentimun)
* 🍆 Eggplant (Terong)
* 🧄 Garlic (Bawang Putih)
* 🧅 Onion (Bawang Bombay)
* 🥔 Potato (Kentang)
* 🍅 Tomato (Tomat) etc.

Our machine learning model was trained on a diverse dataset of fruit and vegetable images, totaling `66 classes` and each class consisting of 1000 images.


## [2] Research Method
![WhatsApp Image 2024-06-18 at 16 51 00_ac3c8c4c](https://github.com/Nutrieasy-Bangkit-Capstone/Nutrieasy-Model/assets/127914968/de6cb308-c998-4e62-a700-f62e38794a01)

## [3] Model Architecture

A Convolutional Neural Network (CNN) model is used to classify both dataset categories. The model architecture can be customized based on requirements, but for this project, the following architecture is used:

1. The Base Model : **Xception** (pre-trained on ImageNet, excluding the top layer).
2. Flatten Layer : Converts the 3D output from the base model into 1D.
3. Dense Layer : 1024 units with ReLU activation.
4. Output Layer : is the Number of classes (66) with softmax activation for multi-class classification.

![model_architecture](https://github.com/Nutrieasy-Bangkit-Capstone/Nutrieasy-Model/assets/127914968/3105577a-6a73-4414-b291-4f223c11fc69)

## [4] Requirements

* TensorFlow version: 2.15.0
* Keras version: 2.15.0
* NumPy version: 1.25.2
* Matplotlib version: 3.7.1
* Python 3 version: 3.10.12 

## [5] Usage

1. Clone this repository to your local machine.
2. Install all the required dependencies.
3. Make sure the dataset is available and placed in the appropriate directory structure.
4. Run the script to train the model and perform the evaluation.
5. You can customize the script, model architecture, or hyperparameters according to your needs.

## [6] References

[1] Xception Documentation : 

    a. https://keras.io/api/applications/xception/
    b. https://keras.io/api/applications/#usage-examples-for-image-classification-models
    c. https://towardsdatascience.com/xception-from-scratch-using-tensorflow-even-better-than-inception-940fb231ced9
    
[2] Dataset
  * Fruits =
    https://www.kaggle.com/datasets/keycia/fruit-nutrionix
    
  * Vegetables =
    https://www.kaggle.com/datasets/keycia/vegetables-nutrionix

## [7] Authors

This project is developed by **C241-PS072** Team Bangkit as part of Bangkit Product Capstone.
1. M505D4KY2938 – Steven Harianto
2. M505D4KY2155 – Valentino Rocky Atmojo
3. M319D4KX1450 – Kezia Natalia
