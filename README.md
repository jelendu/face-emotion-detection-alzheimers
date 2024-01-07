Facial Emotion Detection in Alzheimer’s Patients

Overview

This project applies machine learning to detect facial emotions in Alzheimer’s patients, with the goal of aiding in their care and understanding their emotional states.

Installation

Ensure you have Python installed, then set up your environment with the required libraries:

	•	PyTorch: For creating deep learning models.
	•	EfficientNet PyTorch: An efficient model for deep learning.
	•	TorchSampler: For imbalanced dataset handling.

Install them using:

pip install torch torchvision efficientnet_pytorch torchsampler

For emotion detection:

pip install fer
pip install ffmpeg moviepy

Data Augmentation

The code includes data augmentation techniques to improve model robustness, avoiding bias by excluding ‘ColorJitter’.

Emotion Detection

The project uses the FER library to detect emotions in images, presenting the detected emotions with bounding boxes.

Contribute

This project welcomes feedback, corrections, and collaborations to improve and expand its impact.

For detailed instructions, please refer to the comments within the code in the Google Collab Notebook.
