# Clothing-Segmentation-with-YOLOv8-Annotation-Task
YOLOv8-based segmentation model for clothing annotation. This project demonstrates how to prepare a custom dataset, train a YOLOv8 segmentation model, and evaluate results for classifying and segmenting clothing types (full sleeve, half sleeve, pants). Implemented in Google Colab using the Ultralytics library



🔖Repository Description

YOLOv8-based segmentation model for clothing annotation. This project demonstrates how to prepare a custom dataset, train a YOLOv8 segmentation model, and evaluate results for classifying and segmenting clothing types (full sleeve, half sleeve, pants). Implemented in Google Colab using the Ultralytics library.


# 👕 Clothing Annotation Task – YOLOv8 Segmentation

This project demonstrates how to use **YOLOv8 segmentation** for detecting and segmenting clothing items.  
The dataset was custom-annotated with three classes:  
- full_sleeve`  
- half_sleeve`  
- pants_full`
- 
## 🚀 Features
- Prepares dataset in YOLO format (train/val splits).
- Trains YOLOv8 segmentation model on clothing dataset.
- Evaluates model with mAP, precision, and recall.
- Visualizes segmented predictions.
- Exports trained model to ONNX and TorchScript formats.

![image alt](https://github.com/irfanulkabirhira/Amazon-Sales-yearly-Product-s-Dashboard-Creation/blob/10c6d2726d9aabc312517472a352e8270a994a53/Amazon%20Sales%20DashBoarad%20Creation.png)


## 🛠️ Tech Stack
- Python  
- Google Colab  
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)  
- OpenCV & Matplotlib for visualization  

## 📊 Results
- Trained for **30 epochs** using `yolov8n-seg.pt`.  
- Segmentation masks correctly identify clothing regions.  
- Evaluation metrics and prediction examples are included in the notebook.  

## 📂 Repository Structure
.
├── dataset/ # Images & labels
├── Annotation_Task.ipynb # Colab notebook
├── data.yaml # YOLO dataset config
└── README.md # Project report




## 📌 Future Improvements
- Train with larger YOLOv8 models (`m`, `l`, `x`) for higher accuracy.
- Expand dataset with more clothing types.
- Deploy as a web/app demo for real-time use.

---

