# Vehicle Speed Estimation using Computer Vision

This repository explores a practical approach to estimating vehicle speeds from CCTV footage using modern computer vision techniques.  
The dataset comes from a CCTV camera on the **M6 highway near Knutsford, UK** (coordinates: `53.306230, −2.406044`).

---

## 🚗 Overview
- Vehicles are **detected and tracked** using **YOLO11** and **ByteTrack**  
- **Perspective transformation (OpenCV)** projects vehicle positions onto the road plane to correct camera distortion  
- **Speed estimation** is performed by tracking movement in real-world space  
- **Video annotations** are added using the `supervision` library to overlay positions and speeds  

---

## 🛠 Tech Stack
- [YOLO11](https://github.com/ultralytics/ultralytics) – Object detection  
- [ByteTrack](https://github.com/ifzhang/ByteTrack) – Multi-object tracking  
- [OpenCV](https://opencv.org/) – Perspective transformation & speed calculation  
- [Supervision](https://github.com/roboflow/supervision) – Video annotation  

---

## 🎯 Goal
To demonstrate a simple but effective framework for vehicle speed estimation,  
which can be extended for advanced traffic analysis tasks such as:  
- Congestion monitoring  
- Traffic flow analysis  
- Violation detection  

---

## 🚀 Quick Start
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/vehicle-speed-estimation.git
   cd vehicle-speed-estimation
