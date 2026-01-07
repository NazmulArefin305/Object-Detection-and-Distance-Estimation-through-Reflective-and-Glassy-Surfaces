
**YOLO-Based Object Detection and Distance Estimation**

This repository contains the code, dataset, trained models, outputs, and report for **CoE 595 Assignment 3**. The project focuses on object detection using YOLO and distance estimation using depth data from an Intel RealSense camera.

---

## Repository Structure

```
CoE 595 Assignment 3
│
├── Code/
│   ├── Assignment_3_Train_YOLO_Models.ipynb
│   ├── Collect Distance from npy and Analysis Plot.ipynb
│   ├── Realsense_Image_Capture.ipynb
│   └── Realtime Detection.ipynb
│
├── Dataset/
│   ├── Before annotation/
│   ├── After annotation/
│   │   └── ObjectBehindTheGlass.v3i.yolov11/
│   ├── After annotation.zip
│   └── ObjectBehindTheGlass.v3i.yolov11.zip
│
├── Output/
│   ├── Error Plot/
│   ├── Predicted Output/
│   └── Realtime Output/
│
├── Trained Yolo11s Model/
│
└── Assignment 3 Report (.docx)
```

---

## Project Description

The objective of this project is to:

* Train a **YOLOv11** model on a custom annotated dataset
* Detect objects behind glass
* Estimate object distance using depth data
* Perform real-time detection with an Intel RealSense camera
* Analyze and visualize distance estimation error

---

## Notebook Overview

* **Assignment_3_Train_YOLO_Models.ipynb**
  Trains the YOLOv11 model using the annotated dataset.

* **Realsense_Image_Capture.ipynb**
  Captures RGB and depth images from an Intel RealSense camera.

* **Realtime Detection.ipynb**
  Performs real-time object detection and distance estimation.

* **Collect Distance from npy and Analysis Plot.ipynb**
  Analyzes saved distance data and generates error plots.

---

## Dataset

* Raw images are stored in `Before annotation`
* Annotated YOLO-formatted data is stored in `After annotation`
* Dataset is provided in both extracted and zipped formats

---

## Outputs

* **Predicted Output**: Detection results on images
* **Realtime Output**: Real-time detection results
* **Error Plot**: Distance estimation error analysis

---

## Trained Model

* The trained YOLOv11s model is available in:

  ```
  Trained Yolo11s Model/
  ```

---

## Requirements

* Python 3.x
* Ultralytics YOLO
* OpenCV
* NumPy
* Matplotlib
* Intel RealSense SDK (`pyrealsense2`)
* Jupyter Notebook

---

## How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
2. Install required dependencies.
3. Train the model using:

   * `Assignment_3_Train_YOLO_Models.ipynb`
4. Run real-time detection using:

   * `Realtime Detection.ipynb` (with RealSense camera connected)

---

## Authors

* 202427100
* 202416760
* 202418400
* 202319170
