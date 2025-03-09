# Graduation-Project
## *Pothole And Crack Detection Using Convolutional Neural Networks (CNNs)*

## **1. Introduction**  
- Most transportation relies on paved roads.  
- Poor road conditions (potholes, cracks) cause vehicle damage and accidents.  
- The project aims to develop a **road defect detection system** using **Convolutional Neural Networks (CNNs)**.  

## **2. Dataset & Data Processing**  
- The dataset originates from:  
  **J. Rashid, A. Ghulam, & I. Ahmad. (Feb 2023) - ResearchGate**
- **Dataset Details:**  
  - **Original dataset:** 6,000 images (3 classes: Potholes, Cracks, Normal roads).
  - **The Link: https://bit.ly/3scBvlG**
  - <img width="248" alt="image" src="https://github.com/user-attachments/assets/4fc7039c-2f26-4fcb-87f5-167114c427a6" />
  - **Augmented dataset:** Increased to **36,000 images** using data augmentation.
  - <img width="267" alt="image" src="https://github.com/user-attachments/assets/720ab5fd-159a-4b62-85ff-4f8a4b546bf9" />
  - **Additional datasets for testing:**  
    - **Augmented-18:** 18,000 images  
    - **Augmented-36:** 36,000 images
    - **The Augmentation Code:**
    - <img width="374" alt="image" src="https://github.com/user-attachments/assets/2b54c3fd-0c85-4451-be3a-b0547a62af30" />
- **Image Specifications:**  
  - Size: **256 × 256 pixels**  
  - Format: **RGB**
  - Summary of the All Dataset images type:
  - <img width="424" alt="image" src="https://github.com/user-attachments/assets/b48dc53a-a387-488a-84c7-d48bdffe2100" />

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

<img width="394" alt="image" src="https://github.com/user-attachments/assets/0690fb1f-83a2-4e24-a906-67905e7ab155" />

<img width="389" alt="image" src="https://github.com/user-attachments/assets/583a0f94-6d47-444b-a744-a08f6dc1ae93" />

## **5. Conclusion**  
- The study proves that **CNN models can effectively detect road defects**.  
- **Deep Learning significantly enhances road safety** by providing an automated monitoring system.  
- **Transfer learning with VGG-16 & VGG-19 achieved top performance**, confirming CNNs' effectiveness in addressing road infrastructure challenges.  

- *Note: This is a graduation project for the 2023-2024 academic year in the Computer Science major. I worked on it with two colleagues, and the summary below presents our findings. All the results shown are from my own work, as they have been fully updated to achieve better outcomes.*
