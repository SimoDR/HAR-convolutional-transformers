# Convolutional Transformer for Sensor data on Human Activity Recognition: Classification and Feature Extraction
## Project for Human Data Analytics course

The primary focus of this project lies in exploring a novel approach to HAR using a model based on convolutional transformers, here named SCvT (Sensor Convolutional Transformer), combining the strengths of Convolutional Neural Networks (CNN) and the transformer architecture. Unlike standard methods usually employed in this domain, this model operates directly on raw sensory data, bypassing the need for data augmentation and signal processing techniques.

Additionally, an investigation into the significance of accelerometer positioning on activity prediction was conducted, showing insights into the varying contributions of different accelerometer positions. The study revealed that certain positions, such as the wrists, might contribute relatively less information for predictive tasks compared to other locations like hips and ankles.

The evaluation of the SCvT model across different window sizes demonstrated its robustness and consistent high performance, surpassing existing models in accuracy and automating the data processing pipeline, with performance exceeding 90\% across all metrics.

# Content

This repository presents the code for the project `Project.ipynb`, with the data preparation, implementation of the various architectures (including SCvT), training and testing; and the paper report of the work `Report.pdf`.
