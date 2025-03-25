# Fingerprint Recognition System  
### BY: ANSHUL, NIKUNJ  

## 📌 Overview  
This project implements a **Fingerprint Recognition System** using the **SIFT (Scale-Invariant Feature Transform) algorithm**. The system aims to match **altered or damaged fingerprint images** with real fingerprint images to identify and authenticate individuals.  

## 📝 Abstract  
Fingerprint scanners are widely used **biometric security systems**. Every individual has unique friction ridge patterns on their fingers, making fingerprints an **ideal means of identification**. They remain **unchanged throughout a person’s lifetime** and are difficult to alter. Due to their uniqueness, fingerprints are commonly used in **law enforcement, security industries, smartphones, and other devices**.  

In this project, we have two directories inside the **main directory**, containing images of fingerprints:  
- **Real Directory**: Contains unmodified, authentic fingerprint images. Each file follows a naming convention, including an **ID, gender, and fingerprint type** (e.g., "left index finger").  
- **Altered Directory**: Contains fingerprint images categorized into three levels of alterations:  
  - **Easy**  
  - **Medium**  
  - **Hard**  

Using **OpenCV**, the system compares altered fingerprints with real fingerprints to find an exact match.  

## 🛠️ Tools and Technologies Used  
This project is implemented in **Python** using the following libraries:  

### 🔹 OpenCV (cv2)  
- OpenCV is an open-source **computer vision** library used for AI, Machine Learning, face recognition, and **fingerprint recognition**.  
- It allows image processing, feature extraction, and pattern matching.  

### 🔹 OS Module  
- The **os module** in Python helps interact with the **file system**, allowing us to **fetch directories, access file locations, and retrieve file contents** dynamically.  

## 📷 How It Works  
1. **Preprocessing**: Load and analyze the dataset of real and altered fingerprint images.  
2. **Feature Extraction**: Use the **SIFT algorithm** to extract fingerprint features.  
3. **Matching & Authentication**: Compare altered fingerprints against real fingerprints using OpenCV.  

## 🚀 Future Improvements  
- Enhance accuracy using **Deep Learning models (CNNs)**.  
- Implement a **Graphical User Interface (GUI)** for easy interaction.  
- Support **real-time fingerprint scanning**.  
