# Graduation-Project

## **1. Introduction**  
- Most transportation relies on paved roads.  
- Poor road conditions (potholes, cracks) cause vehicle damage and accidents.  
- The project aims to develop a **road defect detection system** using **Convolutional Neural Networks (CNNs)**.  

## **2. Dataset & Data Processing**  
- The dataset originates from:  
  **J. Rashid, A. Ghulam, & I. Ahmad. (Feb 2023) - ResearchGate**  
- **Dataset Details:**  
  - **Original dataset:** 6,000 images (3 classes: Potholes, Cracks, Normal roads).  
  - **Augmented dataset:** Increased to **36,000 images** using data augmentation.  
  - **Additional datasets for testing:**  
    - **Augmented-18:** 18,000 images  
    - **Augmented-36:** 36,000 images  
- **Image Specifications:**  
  - Size: **256 × 256 pixels**  
  - Format: **RGB**  

## **3. Model & Implementation**  
- Implemented using **Python** and **Keras library**.  
- Training performed on **Google Colab Pro GPU (A100)**.  
- **CNN-based models used for training and evaluation:**  
  - Custom CNN  
  - **VGG-16 & VGG-19 (Transfer Learning applied)**  

## **4. Performance Metrics**  
- **Accuracy & F1-Score:**  
  - Achieved **99.37% accuracy** with **VGG-16 & VGG-19**.  
  - **F1-Score:** **0.99**  
- **Evaluation Metrics Used:**  
  - **Accuracy, Loss, and F1-Score**  
  - **Performance visualized using curves & tables**  

![Final Result Chart](https://github.com/user-attachments/assets/80799666-2cc6-4941-a7cb-32c3d939f562)

![Final Result Chart (Loss)](https://github.com/user-attachments/assets/c6d55531-5161-4984-a03a-6d6c19bfe4e8)

## **5. Conclusion**  
- The study proves that **CNN models can effectively detect road defects**.  
- **Deep Learning significantly enhances road safety** by providing an automated monitoring system.  
- **Transfer learning with VGG-16 & VGG-19 achieved top performance**, confirming CNNs' effectiveness in addressing road infrastructure challenges.  

