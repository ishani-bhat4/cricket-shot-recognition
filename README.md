# 🏏 Cricket Shot Recognition using Deep Learning

This project is an automated system that classifies **cricket shots** and analyzes **player performance** using deep learning and computer vision. Designed to help coaches and players — especially in **rural areas lacking access to advanced training** — it offers real-time insights to enhance player development.

The system achieved an accuracy of **99.4%**, and our research led to the publication of **two peer-reviewed papers**, with myself as **lead author**.

---

## 📄 Table of Contents

- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Notebook Structure](#notebook-structure)
- [Published Papers](#published-papers)


---

## 🎯 Problem Statement

Cricket is a widely played sport, but not all regions have access to professional coaching or tools for performance analysis. This project builds a pipeline to:

- Classify **cricket shots** from video frames  
- Extract and analyze **player performance metrics**  
- Enable **real-time feedback** for grassroots and professional training alike

The model is trained to detect and classify shots like pull, sweep, straight drive, cover drive, and more, using deep learning-based image processing and classification.

---

## 📂 Dataset

We used a custom-labeled video dataset with frame-wise annotations of cricket shots.

🔗 **Kaggle Link**: [Click here to access the dataset](https://www.kaggle.com/datasets/taarunsridhar/cricket-shots-ipl-2023)  
(Note: You'll need to download and place it in a local `data/` folder)

---

## 🧠 Technologies Used

- Python (3.10)
- OpenCV
- TensorFlow / Keras
- Scikit-learn
- Matplotlib & Seaborn
- NumPy & Pandas

---

## 📘 Notebook Structure

- `cricket_shot_recognition.ipynb`
  - Preprocessing and frame extraction
  - Shot classification using CNNs
  - Model training and evaluation
  - Visualizations of predictions
  - Real-time demo code (optional if webcam input is used)

---

## 📝 Published Papers

We authored and published **two papers** as part of this project, highlighting both the technical approach and its application in real-world coaching environments.

1. **"Building a Video Dataset for Cricket Shot Analysiss"**  
   📍 *Published in International Journal of Engineering Research & Technology (IJERT)*  
   📝 (https://ieeexplore.ieee.org/abstract/document/10276358)

2. **"Classification of Cricket Shots from Cricket Videos using Deep Learning Models"**  
   📍 *Presented at International Journal of Engineering Research in Computer Science and Engineering*  
   📝 https://ijercse.com/classification-cricket.php)

🔹 I served as the **lead author** for both publications, working under the guidance of Dr. Sujatha R. Upadhyaya.  
🔹 These papers were part of our **final year capstone project**.

---

