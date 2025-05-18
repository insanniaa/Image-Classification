
# Fruit and Vegetable Image Classification 

This project is a deep learning-based image classification model built using TensorFlow and Keras. It classifies images of fruits and vegetables into 36 different categories using a Convolutional Neural Network (CNN). 

## Dataset

The dataset used for this project is sourced from [Kaggle - Fruit and Vegetable Image Recognition](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition).

### Directory Structure

```
dataset/
├── apple/
├── banana/
├── ...
└── watermelon/

```

## Model Architecture

- Custom Sequential CNN with multiple `Conv2D`, `MaxPooling2D`, and `Dropout` layers
- Categorical Crossentropy loss
- Adam optimizer
- Softmax activation in final layer

## Requirements
- matplotlib==3.10.1
- numpy==1.24.3
- scikit_learn==1.3.2
- tensorflow==2.15.0
- tensorflow_intel==2.15.0

## How to Run

1. Clone the repository.
2. Download and extract the dataset from Kaggle into the appropriate folders.
3. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the notebook or training script to train the model.