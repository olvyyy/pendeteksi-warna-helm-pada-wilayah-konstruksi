# 🦺 Helmet Color Detection in Construction Areas

## 📌 Overview
This system is designed to detect **safety helmet color** in construction areas, as well as identify whether a worker is wearing a helmet or not. This project combines **YOLOv8** (object detection model) with **Flask** as a simple web interface that allows users to upload images or videos and view the detection results automatically.

---

## 🛠️ Background

Workplace safety in construction environments is a crucial aspect and one of the top priorities in every infrastructure project. One key indicator of compliance with safety standards is the use of **Personal Protective Equipment (PPE)**, especially **safety helmets**. Helmets not only protect workers' heads from injury but also use **color coding** to represent specific roles:

- ⚪ White Helmet → Supervisors / Project Managers  
- 🔵 Blue Helmet → Field Engineers / Technicians  
- 🟡 Yellow Helmet → General Workers  
- 🟠 Orange Helmet → Security / Visitors

Manual monitoring of helmet usage is often inefficient and prone to error. By applying **Computer Vision**, this system provides an automatic solution to detect helmet presence and color using **images** or **videos**, improving both efficiency and safety compliance.

---

## 🎯 Objectives

- 🔍 To apply color-based object detection using YOLOv8 for helmet classification.
- 🧪 To simulate an automated system that can be deployed in real-world construction safety monitoring.

---

## 🌟 Benefits

✅ Automates the monitoring process of helmet usage  
✅ Reduces dependency on manual inspections  
✅ Supports image and video inputs  
✅ Helps enforce Occupational Health and Safety (OHS) regulations

---

## 📊 Dataset

- **Source**: [Roboflow - Safety Helmet Dataset](https://universe.roboflow.com/kasetsart-university-xgpvm/safety-helmet-3)  
- **Published by**: Kasetsart University  
- **Classes**:
  - `helmet-blue`: Field supervisors / Technicians  
  - `helmet-white`: Project managers / Engineers  
  - `helmet-yellow`: General laborers / Equipment operators  
  - `helmet-orange`: Site visitors / Safety officers  
  - `no-helmet`: Individuals violating safety rules

---

## ⚙️ Input & Output Support

### ✅ Input Formats:
- Images: `.jpg`, `.jpeg`, `.png`
- Videos: `.mp4`, `.avi`, `.mov`

### 📸 Output:
- Annotated image/video with bounding boxes and labels
- Counts and description of each helmet class

---

## 🖼️ Example

### Input Image:
![Input](https://raw.githubusercontent.com/olvyyy/pendeteksi-warna-helm-pada-wilayah-kontruksi/main/static/outputs/helm-proyek.jpg)

### Output Result:
![Result](https://raw.githubusercontent.com/olvyyy/pendeteksi-warna-helm-pada-wilayah-kontruksi/main/static/outputs/coba.jpg) 

---

## 💻 Technologies Used

- Python 3.x  
- [YOLOv8 by Ultralytics](https://github.com/ultralytics/ultralytics)  
- Flask  
- OpenCV  
- HTML/CSS (for web interface)

---

## 🤝 Contributors

This repository is maintained by @olvyyy.
