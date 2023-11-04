# AI-Real-Time-Face-Recognition

# Real-time Face Recognition AI Model


This AI model uses a DenseNet-136 based sequential neural network to perform real-time face recognition. It's trained to identify whether a detected face belongs to one of the Avengers or not. The dataset used for training includes images of five Avengers: Chris Evans, Chris Hemsworth, Mark Ruffalo, Robert Downey Jr., and Scarlett Johansson.

## Model Overview

- **Model Architecture:** Sequential model with DenseNet-136
- **Output Classes:** 5 (for each of the Avengers)
- **Input Image Size:** 128x128 (configurable)

## Prerequisites

To use this AI model, you'll need:

- Python
- Keras
- OpenCV
- DenseNet-136 pretrained weights
- A webcam or video feed for real-time face detection

The AI model will use your webcam or video feed to detect faces in real-time and display the name of the detected Avenger or "None matching" if no match is found.

*Dataset*
The dataset for this model consists of cropped face images of the following Avengers:

Chris Evans
Chris Hemsworth
Mark Ruffalo
Robert Downey Jr.
Scarlett Johansson


*Performance*
The model performs with high accuracy, thanks to the DenseNet-136 architecture and careful training on the Avenger dataset.





Regenerate

