Eye-Tracking Guided Medical Image Segmentation

Deep learning framework that combines radiologist eye-tracking data with grouped fusion networks to improve medical image segmentation, especially under limited data conditions.

📌 Overview

Medical image segmentation is a key step in computer-aided diagnosis. However, challenges like limited annotated datasets and large variation in lesion sizes make it difficult for models to perform well.

This project integrates eye-tracking data from radiologists into a U-Net based grouped fusion network. By learning where doctors focus during diagnosis, the model achieves better segmentation accuracy for both tiny micro-calcifications and large masses in mammograms.

->> Features

Eye-tracking data used as weak supervision.

Grouped fusion U-Net architecture with attention gates.

 Works effectively with small datasets.

Improved detection of both small and large lesions.

->> Tech Stack

Programming Language: Python

Deep Learning: PyTorch / TensorFlow

Libraries: OpenCV, NumPy, Matplotlib

->> Workflow

Collect or simulate medical images + eye-tracking data.

Preprocess gaze points → generate gaze attention maps.

Train grouped fusion U-Net with gaze supervision.

Evaluate against standard models (U-Net, UNet++, etc.).

->> References

J. Xie et al., “Integrating Eye Tracking With Grouped Fusion Networks for Semantic Segmentation on Mammogram Images,” IEEE Transactions on Medical Imaging, vol. 44, no. 2, pp. 868–879, Feb. 2025.
