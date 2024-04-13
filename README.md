#Car tyre Evaluation

This project aims to classify tire textures into two categories: "normal" and "cracked." The classification is based on analyzing images of tire textures using deep learning techniques.

## Project Structure

The project consists of the following main components:

1. **Dataset**: Contains the training and testing images of tire textures. The dataset is organized into subdirectories based on the class labels ("normal" and "cracked").

2. **Model Training**: Includes scripts for training the deep learning model using the provided dataset. The model architecture used is based on the ResNet50 convolutional neural network.

3. **Model Evaluation**: Provides scripts for evaluating the trained model's performance on unseen data and generating classification reports, confusion matrices, etc.

4. **Requirements**: Lists the required Python packages and dependencies. It is recommended to create a virtual environment and install the dependencies using the provided requirements file.

## Usage

1. **Data Preparation**:
   - Ensure that the dataset is properly organized with images categorized into "normal" and "cracked" classes.
   - Optionally, perform data augmentation or preprocessing techniques if necessary.

2. **Model Training**:
   - Run the training script (`train_model.py`) to train the deep learning model on the training dataset.
   - Adjust hyperparameters, such as dropout rate, learning rate, and optimizer settings, as needed.

3. **Model Evaluation**:
   - After training, evaluate the model's performance using the testing dataset.
   - Generate evaluation metrics, such as accuracy, precision, recall, and F1-score.

4. **Deployment**:
   - Once satisfied with the model's performance, deploy it for real-world classification tasks.
   - Integrate the model into a web application, mobile app, or other systems as required.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- OpenCV
- tqdm
- Other dependencies listed in the `requirements.txt` file

## Credits

This project was developed by Harshil Gautam as part of Car Tyre Evaluation project. It utilizes open-source libraries and datasets.
