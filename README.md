# **Deep Learning Projects**
Welcome to my repository, where I document my journey as a **Machine Learning Engineer** exploring the diverse applications of **Deep Learning** in engineering and science. Originally "only" a mechanical engineer, I've adapted to the modern world necessities of what it means to be a mechanical engineer. The flexibility & knowledge gained during university, backed by my working experience, has taught me how to **identify**, **adapt**, and **learn** possible applications of ML in the vast world of engineering.

Over the past five years, I’ve worked on various projects utilizing different architectures, models & constantly learning and refining my approach to real-world AI challenges.  

## **Project Overview**
### **1. Dense Networks - Fuel Property Prediction**
📂 **Location:** `Dense_networks/`  
This was my first deep learning project, where I **predicted fuel properties** based on their **chemical structure** and **thermodynamic conditions**. The main challenge was **feature engineering**, particularly segmenting thermodynamic states effectively to **prevent information leakage** from training to validation sets.  

### **2. Recurrent Neural Networks (RNNs) - Wind Behavior Analysis**
📂 **Location:** `RNNs/`  
As part of my **TechLabs project**, I implemented **LSTM networks** to analyze **wind behavior**. The dataset contained numerous features, making **feature selection and preprocessing** a significant challenge in building a meaningful model.  

### **3. Convolutional Neural Networks (CNNs) - Medical Image Segmentation**
📂 **Location:** `CNNs/`  
This project focuses on using a **U-Net architecture** to **segment blood vessels in human kidneys**. The key difficulty lies in tuning **ImageDataGenerator** parameters while balancing **computational efficiency**. This is an ongoing project, where I continue iterating on **data augmentation strategies** to enhance performance.  

### **4. Graph Neural Networks (GNNs) - Catalyst Adsorption Energy Prediction**
📂 **Location:** `GNNs/`  
In this project, I leverage **Graph Neural Networks (GNNs)** to accelerate **catalyst material screening** for **fuel cell development**.  
The goal is to predict **adsorption energies of adsorbates on catalyst surfaces**, helping researchers construct **volcano plots** to identify optimal compositions for the **oxygen reduction reaction (ORR)**.  
- The model is trained using **quantum chemistry data** and fine-tuned using **MLflow**.  
- A **FastAPI backend** allows real-time predictions.  
- A **Streamlit web app** provides an interactive interface for researchers to easily input catalyst compositions and visualize results, including **parity plots**.  
