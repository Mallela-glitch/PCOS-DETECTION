PCOS-DETECTION
This project uses transfer learning with the VGG16 model to classify ultrasound images for Polycystic Ovary Syndrome (PCOS) detection.
It is built with TensorFlow Keras, OpenCV, and trained on the PCOS Detection using Ultrasound Images dataset from
[Kaggle](https://www.kaggle.com/datasets/anaghachoudhari/pcos-detection-using-ultrasound-images).
🏆 Project Goals
- Build an AI model to detect PCOS from ultrasound images  
- Use VGG16 as the base model (transfer learning)  
- Train the model with high accuracy  
- Save the trained model  
- Create a simple inference script to predict new images  
- Upload project to GitHub for sharing
📂 Project Structure
PCOS_Detection_Project/
├── pcos_detection.py        # Main model training script
├── predict_image.py         # Predict on new image
├── requirements.txt         # Python package requirements
│   └── pcos_detection_vgg16.h5
└── pcos_data/               
    ├── data/
        ├── train/
            ├── infected/
            ├── notinfected/
        ├── test/
            ├── infected/
            ├── notinfected/
*Requirements
tensorflow
opencv-python
numpy
matplotlib
tqdm
scikit-learn


