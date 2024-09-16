# COVID-19 Chest X-ray Detection with Flask and TensorFlow

This project is a web-based application that allows users to upload chest X-ray images for COVID-19 detection. The application uses a Convolutional Neural Network (CNN) for classification and Flask for the web interface.

## 🚀 Overview

The **COVID-19 Detection Application** allows users to upload X-ray images, which are processed by the trained CNN model to predict whether the individual is affected by COVID-19. The application ensures that only appropriate grayscale X-ray images are used for prediction.

## ✨ Features

- **Image Upload**: Users can upload `.jpg`, `.jpeg`, or `.png` X-ray images for prediction.
- **Grayscale Validation**: The system ensures that only grayscale X-ray images are processed.
- **Prediction Output**: The model predicts if the X-ray is COVID-affected or COVID-unaffected.
- **Web-based Interface**: Simple and intuitive UI to upload X-ray images and get the results instantly.

## 🖥️ UI Design

The web interface consists of:

1. **Home Page**:
   - Upload form for users to select their chest X-ray image.
   - Button to submit the image for processing.

2. **Result Page**:
   - Displays the prediction result (COVID Affected or COVID Unaffected).
   - Error handling for inappropriate image uploads (e.g., non-X-ray or colored images).

### Sample Pages:

#### Home Page:
- **Title**: COVID-19 Chest X-ray Detection
- **Upload Section**: 
    - "Choose File" button for selecting the X-ray image.
    - "Submit" button to upload the image.
  
#### Result Page:
- **Result Section**:
    - Displays "COVID Affected" or "COVID Unaffected" based on the prediction.
    - If an inappropriate image is uploaded, displays an error message: *"Error: This is an inappropriate image. Please upload a Chest X-ray."*

## 🛠️ Installation and Setup

To run the project locally, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/your-github-username/covid-xray-detection.git
cd covid-xray-detection
