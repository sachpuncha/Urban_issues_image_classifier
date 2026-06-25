# Urban Issues Classification with Privacy Anonymization  

This project presents an end-to-end pipeline for **environmental issue detection** using deep learning. It leverages a large-scale dataset of public images and ensures **privacy preservation** through automated anonymization of identifiable elements such as human faces and vehicle number plates.  

---

## 📌 Dataset  
- Collected **17,000+ public images** related to environmental issues.  
- Categorized into **16 fine-grained classes**, grouped under **3 main categories**.  
- Applied **image anonymization** using computer vision techniques (OpenCV Haar Cascade classifiers) to blur faces and number plates, ensuring compliance with privacy standards.  

---

## ⚙️ Model Architecture  
- Implemented a **custom EfficientNet-based model**, trained **from scratch** (not pre-trained).  
- Designed for high accuracy on diverse real-world scenarios.  
- Optimized for balanced classification across all 16 classes.  

---

## 🎯 Objectives  
1. **Automate classification** of environmental issues in images.  
2. **Preserve privacy** through anonymization of sensitive regions.  
3. Provide an **easy-to-use GUI** for real-time inference and visualization.  

---

## 🖥️ Graphical User Interface (GUI)  
A lightweight and interactive GUI was developed to make the system accessible:  
- Upload an image and receive **instant classification results**.  
- Visual feedback highlighting detected and anonymized regions.  
- Designed for **non-technical users** as well as researchers.  

### Screenshots  
<img width="1529" height="683" alt="env issues gui" src="https://github.com/user-attachments/assets/48106b06-7dd2-42d2-ad9b-d140deab2982" />

<img width="1529" height="683" alt="env issues gui" src="https://github.com/user-attachments/assets/c7cc55a8-e2ef-416f-83cd-6ec832053397" />

<img width="1510" height="882" alt="park" src="https://github.com/user-attachments/assets/43766928-a199-442e-9f26-6795a4ae5cc4" />

### Web App Link
[Web App](https://urban-issue-detection-app.streamlit.app/)

---

## 🚀 How to Run  

### Prerequisites  
Install the required dependencies:  
```bash
pip install numpy tensorflow opencv-python ipywidgets matplotlib pillow


