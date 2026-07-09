# Hello, I'm Dilip Goswami

I am a **Computer Vision Engineer** based in Berlin, Germany, with an M.Sc. in **Geodesy and Geoinformation Science** from **Technische Universität Berlin**. My work focuses on **3D computer vision, RGB-D sensor fusion, medical image analysis, geometric registration, and deployment-ready vision systems**.

I build end-to-end perception pipelines that connect **data acquisition, image processing, deep learning, 3D reconstruction, geometric evaluation, backend services, and practical deployment workflows**. My experience spans **AR-guided surgical navigation, endoscopic image understanding, 3D mesh registration, iPhone ARKit RGB-D capture, room-scale reconstruction, visual anonymization, and spatial-data applications**.

I am especially interested in building vision systems that are **geometrically reliable, data-efficient, interpretable, deployable, and useful in real-world environments**.

---

## 🧭 Focus Areas

* Medical Computer Vision
* 3D Registration and Reconstruction
* RGB-D Sensor Fusion
* Endoscopic Image Understanding
* Surface-Distance Evaluation
* Semantic Segmentation and Classification
* AR-Guided Surgical Navigation
* Mobile ARKit-Based 3D Capture
* Deployment-Ready Computer Vision Systems

---

## 🛠️ Technical Skills

| Area                           | Skills                                                                                                                                                                                             |
| :----------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Programming**                | Python, C++, Swift, MATLAB, SQL                                                                                                                                                                    |
| **Computer Vision & Geometry** | RGB-D Fusion, TSDF Fusion, 3D Registration, ICP, RANSAC, Kabsch Alignment, Camera Calibration, Multi-view Geometry, Structure from Motion, Point Clouds, Mesh Processing, Surface-Distance Metrics |
| **Deep Learning**              | PyTorch, CNNs, ResNet, U-Net++, MA-Net, Vision Transformers, YOLO, GANs, Transfer Learning, Fine-Tuning, Focal Loss, Tversky Loss, EMA, Mixed Precision Training                                   |
| **Medical Imaging & AR**       | Endoscopic Image Analysis, Anatomical Landmark Segmentation, Viewpoint Classification, Preoperative-to-Intraoperative Alignment, AR-Guided Navigation                                              |
| **Mobile AR & Sensor Fusion**  | ARKit, SwiftUI, RGB-D Capture, CVPixelBuffer Depth Maps, Confidence Maps, Camera Intrinsics, SIMD Poses, Local Network Streaming                                                                   |
| **Backend & Deployment**       | FastAPI, Docker, REST APIs, CI/CD, GitHub Actions, TensorRT, Model Optimization, Reproducible Pipelines, API-Based Reconstruction Workflows                                                        |
| **Tools & Libraries**          | OpenCV, Open3D, MediaPipe, NumPy, Matplotlib, Albumentations, MeshLab, COLMAP, Supervisely, Git                                                                                                    |

---

## 🚀 Featured Project

### myHut — iPhone ARKit RGB-D Capture and 3D Reconstruction System

**myHut** is an end-to-end iPhone ARKit RGB-D scanning system with a Python/Open3D backend for **object reconstruction, room measurement, and full-room 3D scanning**.

The system combines a **SwiftUI + ARKit iOS app** with an `ark_fusion` backend. The iPhone captures synchronized RGB frames, depth maps, confidence maps, camera intrinsics, timestamps, and ARKit camera poses, then streams the data to a local backend for saving, processing, and reconstruction.

**Core features:**

* SwiftUI + ARKit iPhone RGB-D capture app
* Local network streaming using `URLSession`
* RGB image, depth map, confidence map, pose, intrinsics, and metadata export
* Object scanning mode
* Room measurement mode
* Full-room reconstruction mode
* Python/Open3D backend for RGB-D reconstruction
* TSDF volumetric integration and sensor-fusion pipeline
* Keyframe handling and geometric alignment
* Scan-quality diagnostics and reconstruction artifact generation
* Confidence-based room measurement workflow
* Benchmark evaluation using Chamfer distance and F-score metrics
* Deployment-ready backend/API structure

---

## 🧪 Experience

### Freelance Computer Vision Consultant

**Spiral Physical Therapy Inc., USA — Remote**
*September 2025 – Present*

* Developing monocular 3D facial reconstruction and personalized geometric modeling methods from mobile imagery.
* Building learning-based workflows for facial shape estimation, video-based analysis, and privacy-preserving visual learning.
* Exploring data-efficient and privacy-aware approaches for real-world mobile vision systems.

### Research Trainee / Erasmus+ Scholar

**Institut Pascal, EnCoV – Axe TGI, Clermont-Ferrand, France**
*January 2025 – June 2025*

* Developed a coarse-to-fine 3D registration framework for AR-guided endonasal surgery using semantic initialization and spatial refinement.
* Built synthetic medical image generation and segmentation workflows for limited-data anatomical landmark detection.
* Designed a registration pipeline combining semantic cues, landmark-based alignment, rigid transformation estimation, and geometric refinement.
* Designed evaluation pipelines across **19,150+ surface samples**, achieving **1.205 mm mean surface error** and **1.557 mm RMSE**.
* Achieved **91.8% overall accuracy** and **92.7% macro F1-score** on held-out anatomical viewpoint classification.

### Computer Vision Intern

**SurgAR, Clermont-Ferrand, France**
*November 2024 – December 2024*

* Annotated, validated, and quality-checked medical video data for segmentation and AR-based hepatectomy visualization workflows.
* Supported AR-based visualization workflows for image-guided surgical applications.

### Working Student — Computer Vision

**Eagle Eye Technologies GmbH, Berlin, Germany**
*August 2020 – October 2020*

* Implemented a CNN-based visual anonymization workflow for automatic fading of human faces and vehicle registration plates.
* Prepared training data through preprocessing, augmentation, and quality-control workflows.

---

## 🎓 Education

### M.Sc. Geodesy and Geoinformation Science

**Technische Universität Berlin, Germany**
*Graduated March 2026*

* **Major:** Photogrammetric Computer Vision and Remote Sensing
* **Minor Focus Areas:** Real-Time Multi-Sensor Navigation, GNSS Signal Processing, Geoinformation Technology, Engineering Survey, Adjustment Theory
* **Master’s Thesis:** *Automatic Registration of Preoperative and Intraoperative Views for AR-Guided Endonasal Surgery*
* **Academic Project:** Real-Time Hand Tracking and Monocular Depth Estimation Using a Smartphone Camera

### B.Sc. Urban and Regional Planning

**Khulna University of Engineering & Technology, Bangladesh**
*Graduated August 2015*

---

## 📊 Selected Thesis Results

My master’s thesis integrated **deep learning-based scene understanding** with **3D geometric registration** for AR-guided endonasal surgery.

| Task                                  | Result                      |
| :------------------------------------ | :-------------------------- |
| Nasal-cavity viewpoint classification | **91.8% accuracy**          |
| Macro F1-score                        | **92.7%**                   |
| Weighted F1-score                     | **91.8%**                   |
| Dense registration evaluation         | **19,150+ surface samples** |
| Mean registration error               | **1.205 mm**                |
| RMSE                                  | **1.557 mm**                |
| Median registration error             | **0.96 mm**                 |
| Threshold success                     | **94.1% within 3 mm**       |

---

## 🧩 Selected Projects

### myHut — iOS ARKit RGB-D Capture and Reconstruction System

* Developed an end-to-end RGB-D reconstruction system combining Swift/SwiftUI ARKit capture with a Python backend.
* Built synchronized acquisition and streaming of RGB frames, CVPixelBuffer depth maps, confidence maps, camera intrinsics, and SIMD device poses.
* Implemented RGB-D sensor fusion with TSDF volumetric integration, keyframe selection, geometric alignment, scan-quality diagnostics, and reconstruction artifact generation.
* Added confidence-scored room measurement, benchmark evaluation using Chamfer distance and F-score metrics, and deployment-ready API workflows.

### 3D Mesh Registration Pipeline

* Built a comprehensive alignment pipeline for preoperative anatomical models and intraoperative meshes.
* Used landmark-based scale normalization, Kabsch alignment, RANSAC refinement, and surface-distance evaluation.
* Developed outputs including convergence logs, summary statistics, CDF plots, and MeshLab-compatible error heatmaps.

### Temporal Endoscopic Video Frame Extraction Pipeline

* Architected a resumable multiprocessing Python pipeline for extracting frames from temporally annotated endoscopic surgical videos.
* Used sequential OpenCV decoding, annotation normalization, metadata generation, audit manifests, quality filtering, and structured output generation.
* Designed the pipeline for reproducible medical AI dataset creation.

---

## 🧰 Engineering & Deployment Interests

* Building reproducible computer vision pipelines from data capture to evaluation
* Deploying model inference and reconstruction workflows through backend APIs
* Optimizing vision models for practical runtime constraints
* Using Docker and CI/CD for reliable development and deployment
* Designing evaluation pipelines with clear geometric and statistical metrics
* Creating tools that bridge research prototypes and production-ready applications

---

## 🎯 Roles of Interest

* Computer Vision Engineer
* Machine Learning Engineer
* Research Engineer
* Medical Image Analysis Engineer
* 3D Vision / Reconstruction Engineer
* Sensor Fusion Engineer
* AR/VR Perception Engineer
* Spatial AI Engineer
* Computer Vision Deployment Engineer

---

## 🌍 Languages

* **Bengali:** Native
* **English:** C2
* **German:** A2, actively improving

---

## 📫 Contact

* **LinkedIn:** [linkedin.com/in/dilip-goswami-853018108](https://www.linkedin.com/in/dilip-goswami-853018108/)
* **ResearchGate:** [researchgate.net/profile/Dilip-Goswami-2](https://www.researchgate.net/profile/Dilip-Goswami-2?ev=hdr_xprf)
* **Email:** [gshubro@yahoo.com](mailto:gshubro@yahoo.com)

---

> Building geometrically grounded computer vision systems for real-world medical, spatial, AR, and sensor-fusion applications.
