# Traffic Sign Classification using CNN

This project uses a Convolutional Neural Network (CNN) to classify traffic signs from the GTSRB dataset. The model is built with TensorFlow and Keras, and achieves high accuracy on the multiclass classification task.

## Project Overview
- **Goal:** Automatically recognize and classify traffic signs for smarter and safer vehicles.
- **Dataset:** Downloaded from [Kaggle - GTSRB: German Traffic Sign Recognition Benchmark](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign) using the Kaggle API in Google Colab.
- **Classes:** 43 different traffic sign categories

## Steps
1. **Download Dataset:**
   - Download `kaggle.json` from your Kaggle account and upload it when prompted in Google Colab.
   - The notebook will use the Kaggle API to download and extract the dataset.
2. **Preprocessing:**
   - Images are resized to 50x50 pixels and normalized.
   - Data is split into training and validation sets.
   - Labels are one-hot encoded.
3. **Model Building:**
   - A CNN is built using TensorFlow/Keras with Conv2D, MaxPool2D, Dropout, Flatten, and Dense layers.
4. **Training:**
   - The model is trained for 10+ epochs with batch size 128.
   - Training and validation accuracy/loss are plotted.
5. **Evaluation:**
   - The model is evaluated on the test set.
   - Predictions are visualized and compared to true labels.

## Requirements
Install dependencies with:

    pip install -r requirements.txt

## Usage
1. Run the Jupyter notebook `Traffic_Sign_Classification.ipynb` in Google Colab.
2. Follow the instructions to upload your `kaggle.json` and download the dataset from Kaggle.
3. Execute all cells to preprocess data, train, and evaluate the model.

## Results
- The model achieves over 95% accuracy after training.
- Can be further improved with hyperparameter tuning.

## Applications
- Self-driving cars
- Driver assistance systems

## Author
- Adapted for educational/demo purposes.

---
*For more details, see the code and comments in the notebook.*
