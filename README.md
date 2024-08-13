# Facial Recognition and Emotion Detection

This project focuses on building a model that can recognize facial expressions and detect emotions from images. By leveraging convolutional neural networks (CNNs), the model can identify seven distinct emotions, providing insights into human non-verbal communication.

## Emotion Detection Overview

Human emotions play a crucial role in non-verbal communication, enhancing the clarity of thoughts and ideas. This project aims to capture these complex human features—emotions—using computer vision. The key components of the project include data gathering and augmentation, model building, training, and testing.

## Key Features

### 1. Data Gathering and Augmentation

- The dataset used for training the model is **"fer2013"**.
- The dataset can be downloaded from the [FER2013 GitHub repository](https://github.com/npinto/fer2013).
- Image augmentation techniques were applied to the dataset to enhance the model's robustness.

### 2. Model Building

- The model architecture includes Convolutional Neural Network (CNN) layers, Max Pooling layers, Flatten layers, and Dropout layers.
- The architecture is designed to effectively capture and process the complex features of human facial expressions.

### 3. Training

- The model was trained using various configurations of the layers mentioned above, with different hyperparameters.
- The best model achieved a validation accuracy of 60.1%.

### 4. Testing

- The model was tested using sample images to evaluate its performance in real-world scenarios.
- The trained model can detect seven types of emotions: Angry, Sad, Neutral, Disgust, Surprise, Fear, and Happy.

## Usage

### Face Detection and Emotion Detection Code

- The code for face detection and emotion detection is available in the notebook located at `/Emotion_Detection.ipynb`.
- The trained emotion detection model and its weights can be found in the `/Models` directory.

### Training Your Own Emotion Detection Model

- To train your own emotion detection model, refer to the notebook `/facial_emotion_recognition.ipynb`.
- This notebook provides detailed steps and code for replicating the model training process.

### Running Emotion Detection Using Webcam

1. Clone the repository to your local machine.
2. Install the required dependencies by running:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the emotion detection script using the command:
    ```bash
    python Emotion_Detection.py
    ```

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---
