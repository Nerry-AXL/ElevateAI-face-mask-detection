# ElevateAI Face Mask Detection

This repository contains the source code for a Face Mask Detection system, a deep learning-based application designed to detect whether individuals are wearing face masks. This dummy system is capable of real-time detection and can be used in public spaces, workplaces, or other environments to ensure compliance with health and safety regulations.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)

## Project Overview

The ElevateAI Face Mask Detection system uses convolutional neural networks (CNNs) to identify whether individuals in an image or video stream are wearing face masks. This technology can help automate the monitoring process in various settings, reducing the need for manual checks and improving overall safety.

## Features

- **Real-Time Face Mask Detection:** Detects face masks in real-time using a webcam or video feed.
- **High Accuracy:** Trained on a diverse dataset to ensure high accuracy in different environments.
- **Visual Feedback:** Provides clear visual indicators of whether a mask is detected on each face.
- **Easy Integration:** Can be easily integrated into existing security systems or deployed as a standalone application.

## Installation

To run the ElevateAI Face Mask Detection system locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Nerry-AXL/ElevateAI-face-mask-detection.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd ElevateAI-face-mask-detection
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

### Dependencies

The main dependencies for this project include:

- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy
- Streamlit (for web-based interface)
- Matplotlib (for visualization)

## Usage

1. **Start the application:**

    ```bash
    python app.py
    ```

2. **Access the app interface:**
   Open your web browser and navigate to `http://127.0.0.1:5000/` to access the ElevateAI Face Mask Detection interface.

3. **Begin mask detection:**
   Use a webcam or upload an image or video file to start detecting face masks.

4. **Custom Model Integration:**
   To use a custom-trained model, replace the default model in the `models/` directory and update the code in `app.py` accordingly.

## Model Details

- **CNN (Convolutional Neural Network):** The system uses a CNN model trained on a dataset of images with and without face masks.
- **Pre-trained Model:** The default model is trained on a large dataset to ensure high accuracy and generalization across different environments.
- **Transfer Learning:** Techniques like transfer learning can be used to adapt the model to specific datasets or requirements.

### Face Detection

- **OpenCV:** Used for detecting faces in images or video streams before applying the mask detection model.

### Mask Classification

- **Binary Classification:** The model classifies each detected face as either "Mask" or "No Mask."

## Results

The ElevateAI Face Mask Detection system provides the following outputs:

- Bounding boxes around detected faces with labels indicating "Mask" or "No Mask."
- Confidence scores for each detection.
- Visualizations of the detection process, including highlighted faces and mask status.

## Contributing

Contributions to this project are welcome! If you have suggestions for new features, improvements, or bug fixes, feel free to fork the repository, make your changes, and submit a pull request.
