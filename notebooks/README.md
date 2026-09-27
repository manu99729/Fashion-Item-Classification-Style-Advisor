# Fashion Item Classification and Style Advisor

## Project Overview

This project uses a Convolutional Neural Network (CNN) to classify fashion items from the Fashion-MNIST dataset. After identifying the fashion item, an AI-based Style Advisor provides information about its common use and styling suggestions.

## Objectives

* Classify fashion items using a CNN.
* Train and evaluate the model using Fashion-MNIST.
* Identify the predicted fashion category.
* Provide common-use information.
* Provide styling suggestions.
* Develop an interactive interface using Gradio.

## Technologies Used

* Python
* Google Colab
* TensorFlow / Keras
* Fashion-MNIST
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Gradio

## Fashion-MNIST Classes

The model classifies the following 10 categories:

1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## System Architecture

Image Input
↓
Image Preprocessing
↓
CNN Classification
↓
Fashion Item Prediction
↓
Style Advisor Agent
↓
Common Use + Styling Suggestions
↓
Gradio Interface

## Project Structure

```text
fashion-item-classification-style-advisor/
│
├── notebooks/
│   └── Fashion_Item_Classification_Style_Advisor.ipynb
│
├── models/
│   └── fashion_cnn.keras
│
├── app/
│   └── app.py
│
├── report/
│   └── Project_Report.pdf
│
├── presentation/
│   └── Fashion_Style_Advisor.pptx
│
├── requirements.txt
└── README.md
```

## Model

The CNN consists of convolutional layers, max-pooling layers, a fully connected layer, dropout, and a final softmax classification layer.

## Interface

The Gradio interface allows users to upload an image and receive:

* Predicted fashion item
* Prediction confidence
* Common use
* Styling suggestions

## Limitations

Fashion-MNIST contains small 28×28 grayscale images and only ten categories. Therefore, performance on ordinary real-world photographs may differ from performance on Fashion-MNIST test images.

## Future Improvements

* Use larger real-world fashion datasets.
* Add color and clothing attribute detection.
* Provide occasion-based recommendations.
* Add personalized outfit recommendations.
* Integrate a larger language model for more flexible fashion advice.

## Author

Student Project — Fashion Item Classification and Style Advisor
