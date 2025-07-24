# 🕳️ Pothole Detection using YOLOv5 🚗
This project implements a deep learning-based pothole detection system using the YOLOv5 object detection model. It is designed to help in identifying potholes from road images for road safety and maintenance systems.

## 📁 Project Structure

Pothole-Detection-YOLOv5/
├── pothole_detection.ipynb       ← Final Google Colab training/testing notebook  
├── data/  
│   └── pothole.yaml              ← Dataset configuration file  
├── weights/  
│   └── best.pt                   ← Trained YOLOv5 model weights  
├── results/  
│   └── test_img result.jpg       ← Example image with detection  
├── README.md                     ← Project description (this file)

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/MEHATAJ-PS/Pothole-Detection-YOLOv5.git
cd Pothole-Detection-YOLOv5
```

2. Open `pothole_detection.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.

3. Follow the steps in the notebook to:

   * Load the dataset  
   * Train YOLOv5  
   * Detect potholes in test images  

## 🧠 Model

* **YOLOv5s** used as the base model  
* Trained on a custom pothole dataset (600 images)  
* Format: YOLO annotated `.txt` files  

## 🔍 Results

Sample detection:

[Sample] (results/test_img result.jpg)

## 📦 Requirements

* Python ≥ 3.8  
* PyTorch ≥ 1.7  
* OpenCV, Pandas, Matplotlib  
* `ultralytics/yolov5` repo  

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Mehataj P.S**  
🔗 GitHub: [MEHATAJ-PS](https://github.com/MEHATAJ-PS)
