https://github.com/user-attachments/assets/3ef0708b-6b36-4c22-9bec-485113d9660b
# Red-Stop
## 🚦 Traffic Monitoring and Detection System

## Project Overview
A comprehensive computer vision project for traffic monitoring using two complementary approaches:
- Traffic Violation Detection
- Traffic Light Detection with YOLOv8

## 🛠 Key Technologies
- OpenCV
- YOLOv8
- Ultralytics
- Pytesseract
- Roboflow

## 🌟 Features
### Traffic Violation Detection
- Traffic light color recognition
- Lane line detection
- License plate identification
- Automated violation logging

### Traffic Light Detection
- Custom YOLOv8 model training
- Multi-class traffic light classification
- Video and image inference
- Performance metrics visualization

## 📦 Installation
```bash
pip install opencv-python pytesseract ultralytics roboflow
```

## 🚀 Workflow
1. Traffic Light Detection
   - Train YOLOv8 model on custom dataset
   - Validate model performance
   - Perform inference on test images/videos

2. Traffic Violation Tracking
   - Monitor traffic light signals
   - Detect lane violations
   - Capture and process license plates
   - Log violations

## 📊 Model Performance
- Trained on custom Roboflow dataset
- 80 epochs of training
- Image size: 640x640
  ## Confusion Matrix
  ![output1](https://github.com/user-attachments/assets/1acc473c-c86b-4729-83f6-c59847f9db19)
  ## 🚦 Training and Validation Loss
  ![output](https://github.com/user-attachments/assets/63c3f60c-e708-426c-8fd6-c7be41eee393)


## 🔍 Key Components
- Custom YOLOv8 traffic light detection
- Haar Cascade license plate recognition
- Tesseract OCR for plate text extraction
- Advanced image processing techniques

## 🖥️ Requirements
- Python 3.7+
- GPU recommended for training
- CUDA-compatible environment

## 👥 Contributors
- [G Sai Sudarshan Rao]()
- [K R Eashwar Sai]()
- [Shivam](https://github.com/Ayush-mishra-0-0/cs550) - 12241710
- 
Team KERAS - DS510: AI/ML Project
