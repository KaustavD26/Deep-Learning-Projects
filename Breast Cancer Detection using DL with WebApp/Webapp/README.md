
# Web Application for Breast Cancer Detection Using Ultrasound Imaging

## Project Objective  
This web application provides a user-friendly platform designed to assist healthcare professionals in detecting breast cancer from ultrasound images. By leveraging advanced deep learning models, the application aims to improve the accuracy and efficiency of breast cancer diagnosis.

## Models Integrated  
The application incorporates the following models for robust breast cancer detection:

- **VGG16 Transfer Learning Model**  
  A pre-trained VGG16 model is adapted via transfer learning to extract high-level features from ultrasound images. This approach leverages knowledge from a large-scale dataset to improve model accuracy and generalization on the breast cancer detection task.

- **Custom Multilayer Perceptron (MLP)**  
  A tailored MLP architecture specifically designed for classifying ultrasound images into cancerous and non-cancerous categories. This custom model enables fine-tuning to better capture the unique characteristics of ultrasound imagery.

- **ResNet50 Transfer Learning Model**  
  Utilizing the deep residual learning capabilities of ResNet50, this model leverages skip connections and residual blocks to effectively learn complex features from ultrasound data, enhancing detection performance.

## Key Features of the Web Application

- **Built with Flask Framework**  
  The application uses Flask, a lightweight Python web framework, to deliver a responsive and easy-to-use interface.

- **Model Loading and Inference**  
  The trained breast cancer detection model (`best_breast_cancer_detection_model.h5`) is loaded using TensorFlow/Keras for prediction.

- **Image Preprocessing**  
  Uploaded ultrasound images are preprocessed through grayscale conversion, resizing, and normalization to meet the input requirements of the models.

- **Prediction Endpoint**  
  A `/predict` POST endpoint processes incoming images and returns classification results — Benign, Malignant, or Normal — directly to the user interface.

- **Interactive User Interface**  
  The web interface allows users to upload ultrasound images and view immediate predictions in a clear and accessible manner.

## Video Demonstration

Watch the full demonstration of the web application in action:  
[Breast Cancer Detection Web App Demo](https://github.com/TheNaiveSamosa/DL-Simplified/assets/)

---

## Author  
**Kaustav Deb**  
Deep Learning Enthusiast and Developer

LinkedIn: [linkedin.com/in/kaustavdeb](https://www.linkedin.com/in/kaustavdeb)
