# Emotion Analysis

<video src="yolo_mo2q5c.mp4" autoplay loop muted playsinline style="width: 100%; border-radius: 10px;"></video>

Recognizing emotions in real-time has vast applications ranging from entertainment to mental health analysis. Utilizing the power of YOLOv8, Roboflow for dataset annotation, and Google Colab for model training, this project detects and displays cumulative emotions from frames of any video or live webcam feed.

## The Concept

The core objective is to leverage **YOLOv8** for high-speed, real-time emotion detection. By training a custom model on a specialized dataset, the system identifies facial expressions and generates a live, cumulative pie chart to visualize the distribution of emotions detected throughout a session.

## Model Development

The development process involved:
* **Annotation**: Using Roboflow to label a diverse dataset of facial expressions.
* **Training**: Executing the training pipeline on Google Colab over 100 epochs to ensure high accuracy and robust generalization.
* **Optimization**: Fine-tuning the YOLOv8 architecture to maintain high frame rates during inference.

![Training Results](https://res.cloudinary.com/dlb65j6di/image/upload/v1722007552/trainresults_rfvjd3.png)

## Performance & Real-time Visualization

The model processes video frames dynamically, updating a visual representation of emotional trends in real-time. This provides an immediate summary of the emotional state captured during the video feed.

![Emotion Distribution Pie Chart](https://res.cloudinary.com/dlb65j6di/image/upload/v1722007619/pie_tnb9rd.gif)

## Development Stack

* **Model**: Ultralytics YOLOv8
* **Analytics**: Ultralytics Analytics for real-time rendering
* **Data Management**: Roboflow (Annotation and Versioning)
* **Compute**: Google Colab (GPU-accelerated training)
* **Processing & Visualization**: OpenCV and Matplotlib

## Repository

You can find the full source code and implementation details on GitHub:
[GitHub - Emotion Analysis](https://github.com/kasun98/emotion)

---
© 2025 | Emotion Analysis Project
