# 🌲 Comparison Of Forest Fire Detection Using Satellite Imagery & YOLO Models  
---

## 🌐 Live Preview  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)  
![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)  
![YOLO](https://img.shields.io/badge/YOLO-v5|v6|v8|v11-orange?style=for-the-badge&logo=yolo)  
![Dataset](https://img.shields.io/badge/Dataset-Roboflow-green?style=for-the-badge&logo=roboflow)  

---

## 📖 About the Project  
Forest fires are one of the most devastating natural disasters. Traditional methods like ground patrols are slow and inefficient.  
This project leverages **satellite imagery** and **YOLO object detection models** to build an **automated forest fire detection system** with high accuracy and speed.  

---

## 🎯 Objectives  
- ✅ **Detect Forest Fires:** Build a system to identify fire regions in satellite images.  
- ✅ **Compare YOLO Models:** Evaluate YOLOv5, YOLOv6, YOLOv8, and YOLOv11.  
- ✅ **Determine Best Model:** Choose the most accurate and efficient YOLO model.  

---

## 🖼 Project Screenshots  

### 🔍 Detection Output  
![WhatsApp Image 2025-08-28 at 00 54 29_ed78505d](https://github.com/user-attachments/assets/139a2c29-a307-4e97-a7f0-15dc77f692b6) <!-- Add sample output image -->

### 📊 Model Comparison  
<img width="1856" height="1276" alt="image" src="https://github.com/user-attachments/assets/83c92465-14bd-497d-be2b-dd856eca24d5" /> <!-- Add chart comparing YOLO models -->

---

## 🛠 Tech Stack  
| Logo | Technology |
|------|------------|
| <img src="https://www.python.org/static/community_logos/python-logo-master-v3-TM.png" alt="Python Logo" width="80"/> | **Python** for development |
| <img src="https://raw.githubusercontent.com/ultralytics/assets/main/yolo-logo.png" alt="YOLO Logo" width="80"/> | **YOLO Models** for object detection |
| <img src="https://raw.githubusercontent.com/roboflow/roboflow-python/main/roboflow-logo.png" alt="Roboflow Logo" width="80"/> | **Roboflow** for dataset management |
| <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" alt="Jupyter Logo" width="80"/> | **Jupyter Notebooks** for training & evaluation |

---

## 📂 Dataset  
- **Source:** [Roboflow Universe](https://universe.roboflow.com)  
- **Images:** 3,500+ high-resolution annotated satellite images  
- **Includes:** Fire regions, smoke plumes, unaffected areas  

- **Preprocessing:** Resizing (640x640), normalization, augmentation  

---

## 🔍 Methodology  
1. Collect & preprocess dataset  
2. Train YOLO models (v5, v6, v8, v11)  
3. Evaluate using metrics: **mAP@0.5**, **F1-score**, **confidence**, **latency**  
4. Compare and choose best-performing model  

---

## 📊 Model Performance  

The models were evaluated on **Dataset 1** using the following metrics:  
- **F1-score**  
- **Confidence**  
- **mAP@0.5**  
- **Latency**  

| Model  | F1-Score | Confidence | mAP@0.5 | Latency |
|--------|----------|-----------|---------|---------|
| YOLOv5 | 0.54     | 0.355     | 0.529   | 200ms   |
| YOLOv8 | 0.52     | 0.259     | 0.511   | 212ms   |
| YOLOv11| 0.55     | 0.319     | 0.540   | 214ms   |
| YOLOv6 | 0.54     | 0.263     | 0.527   | 285ms   |

✅ **Best Model Based on mAP & Speed:** **YOLOv11** (Highest mAP and relatively low latency)

---

## ⚠ Challenges  
- Limited fire image diversity  
- Training time and GPU requirements  
- Overfitting vs underfitting balance  
- False positives from non-fire objects  

---

## 🔮 Future Scope  
- Real-time detection with live satellite data  
- Integration of thermal and multispectral imagery  
- Transformer-based models (e.g., DETR)  
- Extend detection for floods, landslides, wildfires      

---

### ⭐ If you found this useful, give this project a **star**!
