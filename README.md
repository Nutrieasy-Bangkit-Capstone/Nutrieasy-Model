# Nutrieasy Model - Fruit and Vegetable Classification for Fruit and Vegetable Nutrition Detection

This project aims to classify fruits and vegetables and detect the nutrients of fruits and vegetables using Convolutional Neural Network (CNN) in Python and TensorFlow. This project uses image data to identify the nutrition of fruits and vegetables based on the given image.

## [1] Dataset

The dataset used consists of images of fruits and vegetables with their corresponding labels. The dataset is divided into two main categories: "Fruits Classification" and "Vegetable Classifications".

Dataset Kaggle :
1. Fruits Dataset : https://www.kaggle.com/datasets/keycia/fruit-nutrionix
2. Vegetables Dataset : https://www.kaggle.com/datasets/keycia/vegetables-nutrionix

### Classification of Fruits 
This dataset contains leaf images of fruits and we have 44 classes of fruits, such as:
* 🍎 Apple (Apel)
* 🥑 Avocado (Alpukat)
* 🍌 Banana (Pisang)
* 🍒 Cherries (Ceri)
* 🥥 Coconut (Kelapa)
* 🍇 Grape (Anggur)
* 🍋 Lemon (Lemon)
* 🥭 Mangga (Mangga)
* 🍉 Watermelon (Semangka)

### Classification of Fruits and Vegetables
This dataset contains leaf images of fruits and we have 22 classes of vegetables, such as:
* 🥦 Broccoli (Brokoli)
* 🥕 Carrot (Wortel)
* 🌽 Corn (Jagung)
* 🥒 Cucumber (Mentimun)
* 🍆 Eggplant (Terong)
* 🧄 Garlic (Bawang Putih)
* 🧅 Onion (Bawang Bombay)
* 🥔 Potato (Kentang)
* 🍅 Tomato (Tomat)

## [2] Research Method
![WhatsApp Image 2024-06-18 at 16 51 00_ac3c8c4c](https://github.com/Nutrieasy-Bangkit-Capstone/Nutrieasy-Model/assets/127914968/de6cb308-c998-4e62-a700-f62e38794a01)

## [3] Model Architecture

A Convolutional Neural Network (CNN) model is used to classify both dataset categories. The model architecture can be customized based on requirements, but for this project, the following architecture is used:

* Input Layer
* Convolutional Layers: Used for feature extraction from the images.
* Max Pooling Layers: Used for dimensionality reduction of the features.
* Flatten Layer: Flattens the features into a vector.
* Fully Connected Layers: Perform classification tasks.
* Output Layer: Outputs the classification predictions, it depends on labels.

## [4] Requirements

* Python 3 -
* Keras -
* TensorFlow -
* NumPy -
* Matplotlib -

## [5] Usage

1. Clone this repository to your local machine.
2. Install all the required dependencies.
3. Make sure the dataset is available and placed in the appropriate directory structure.
4. Run the script to train the model and perform the evaluation.
5. You can customize the script, model architecture, or hyperparameters according to your needs.

## [6] References

[3] Dataset
  * Fruits =
    https://www.kaggle.com/datasets/keycia/fruit-nutrionix
    
  * Vegetables =
    https://www.kaggle.com/datasets/keycia/vegetables-nutrionix

## [7] Authors

This project is developed by C241-PS072 Team Bangkit as part of Bangkit Product Capstone.
1. M505D4KY2938 – Steven Harianto
2. M505D4KY2155 – Valentino Rocky Atmojo
3. M319D4KX1450 – Kezia Natalia
