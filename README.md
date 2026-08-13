# Hi, I'm Dilip Goswami 👋

<div align="left">
  <a href="mailto:gshubro@yahoo.com">
    <img src="https://img.shields.io/badge/Email-gshubro@yahoo.com-blue?style=for-the-badge&logo=yahoo" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/dilip-goswami-853018108/">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.researchgate.net/profile/Dilip-Goswami-2">
    <img src="https://img.shields.io/badge/ResearchGate-Publications-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white" alt="ResearchGate" />
  </a>
</div>

<br>

I am a **Computer Vision Engineer** focused on **3D perception, geometric computer vision, sensor fusion, deep learning, and spatial computing**.

I build end-to-end vision systems—from multimodal data acquisition and model development to geometric reconstruction, quantitative evaluation, backend integration, and deployment.

> **Portfolio note:** This profile contains both public portfolio repositories and descriptions of private research or competition work. Private source code is not shared when restricted by competition rules, collaboration agreements, or data-privacy requirements.

---

## 🛠 Technical Expertise

### Languages, Libraries & Frameworks

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-EF6C00?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Open3D](https://img.shields.io/badge/Open3D-3D8FC6?style=flat-square)
![ARKit](https://img.shields.io/badge/ARKit-000000?style=flat-square&logo=apple&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=flat-square&logo=swift&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### 3D Vision & Geometry

- Point-cloud and mesh processing
- RGB-D fusion and TSDF reconstruction
- Rigid and similarity registration
- Kabsch alignment, RANSAC, and ICP
- Camera calibration and coordinate transformations
- Multi-view and monocular 3D reconstruction
- Surface-distance and spatial-accuracy evaluation

### Deep Learning & Medical Vision

- Image classification, object detection, and semantic segmentation
- CNNs, vision transformers, and transfer learning
- Anatomical registration and landmark detection
- Endoscopic image and video processing
- Limited-data and privacy-aware visual learning
- Reproducible model evaluation

### Spatial Computing & Sensor Fusion

- ARKit-based RGB-D acquisition
- RGB, depth, confidence, intrinsics, and pose processing
- Object and indoor-scene reconstruction
- Confidence-aware measurements and scan diagnostics
- Multi-sensor and mobile vision workflows

### Software Engineering

- Python API and backend development with Flask and FastAPI
- Multiprocessing and resumable data pipelines
- Docker, CI/CD, automated testing, and GitHub Actions
- TensorRT model optimization
- Input validation, metadata, and audit manifests
- Reproducible evaluation workflows

---

## 🌐 Featured Public Projects

### [myHut: Mobile RGB-D Reconstruction System](https://github.com/goapu/myHut)

- End-to-end SwiftUI/ARKit and Python/Open3D system for synchronized RGB, depth, confidence, camera intrinsics, pose, timestamp, and metadata acquisition from an iPhone.
- Supports object reconstruction, room measurement, and indoor scanning with TSDF fusion, confidence-aware filtering, pose-quality checks, scan guidance, backend services, Docker, and automated tests.

### [3D Mesh Registration and Evaluation Pipeline](https://github.com/goapu/3D-Mesh-Registration-and-Evaluation-Pipeline)

- Similarity and rigid registration using landmark scale normalization, Kabsch alignment, mesh RANSAC, and ICP refinement.
- Includes forward/inverse transformations, surface-distance metrics, correspondence evaluation, convergence plots, error statistics, and MeshLab-compatible heatmaps.

### [Anatomical Nose Landmark Extractor](https://github.com/goapu/anatomical-nose-landmarks-extractor)

- Mesh-first Open3D pipeline for extracting anatomical regions, proposing landmarks, and generating dense nasal surface templates from OBJ, PLY, and STL facial meshes.
- Combines PCA-based coordinate estimation, statistical filtering, curvature and geodesic cues, optional symmetry-based pose normalization, confidence scoring, and diagnostic overlays.

### [3D FaceMesh Fusion and Facial Analysis](https://github.com/goapu/3d-facemesh-fusion-pipeline)

- Fuses 468 MediaPipe facial landmarks across video frames and exports 3D OBJ meshes and geometric measurements.
- Integrates mask-aware analysis, FaceNet embeddings, duplicate detection, face-shape classification, batch workflows, and privacy-aware output handling.

### [Nasal Cavity Classification](https://github.com/goapu/Nasal-Cavity-Classification)

- Three-class anatomical-view classification pipeline for anterior, middle, and posterior nasal-cavity images.
- Provides reproducible training and evaluation outputs, including class-level metrics and confusion-matrix visualization.

### [Temporal Block-Based Frame Extraction](https://github.com/goapu/Temporal-Block-Based-Frame-Extraction-for-Endonasal-Videos)

- Video-processing pipeline for temporally structured frame extraction from endonasal videos.
- Designed to support reproducible dataset preparation and downstream medical computer-vision workflows.

---

## 🔒 Private & Confidential Contribution

### InvisibleEye: 3D Pinna Landmark Estimation — Competition Project

I designed and implemented the **core end-to-end project pipeline** for estimating **85 ordered landmarks per ear** from 3D pinna meshes. My work includes:

- PointNet- and DGCNN-based heatmap models in PyTorch
- Mesh preprocessing, surface sampling, and geometric feature construction
- Coordinate canonicalization and subject-level data splits
- Training, inference, post-processing, and quantitative evaluation components
- Reproducible experiment and dataset workflows

The repository is private because the project is subject to **competition restrictions**. Later commits include collaborative modifications by teammates; the project description above reflects my core technical contribution. Source code, restricted data, and competition-sensitive implementation details are not published.

---

## 📐 Selected Technical Results

- **1.205 mm mean surface error** and **1.557 mm RMSE** for anatomical registration
- **94.1% of evaluated surface samples within 3 mm**
- Registration evaluated across more than **19,150 surface samples**
- **91.8% accuracy** and **92.7% macro F1 score** for anatomical viewpoint classification

---

## ⚙️ Engineering Approach

I build systems that are:

- **Geometrically rigorous**
- **Quantitatively evaluated**
- **Robust to real-world data**
- **Modular and maintainable**
- **Deployment-oriented**
- **Reproducible**

---

## 🔬 Background

I hold an **M.Sc. in Geodesy and Geoinformation Science** from **Technische Universität Berlin**, specializing in **Photogrammetric Computer Vision and Remote Sensing**.

My research at **Institut Pascal** focused on registering preoperative anatomical models with intraoperative 3D observations for **AR-guided endonasal surgery**.

---

## 🧭 Technical Interests

- Robust 3D registration
- Monocular and RGB-D reconstruction
- Neural and geometric 3D representations
- Confidence-aware sensor fusion
- Medical image analysis
- Privacy-preserving computer vision
- Mobile spatial computing

---

## 📊 Public GitHub Activity

> These cards summarize **public GitHub activity only**. They do not include commits, languages, or engineering work in private research and competition repositories.

<div align="center">
  <a href="https://github.com/goapu">
    <img
      src="https://github-readme-stats.vercel.app/api?username=goapu&show_icons=true&theme=vision-friendly-dark&hide_border=true"
      height="165"
      alt="Dilip Goswami's public GitHub statistics"
    />
  </a>
  <a href="https://github.com/goapu?tab=repositories">
    <img
      src="https://github-readme-stats.vercel.app/api/top-langs/?username=goapu&layout=compact&theme=vision-friendly-dark&hide_border=true&langs_count=8"
      height="165"
      alt="Languages by public code volume across Dilip Goswami's repositories"
    />
  </a>
</div>

<br>

<div align="center">
  <a href="https://github.com/goapu">
    <img
      src="https://streak-stats.demolab.com/?user=goapu&theme=vision-friendly-dark&hide_border=true"
      alt="Dilip Goswami's public GitHub contribution streak"
    />
  </a>
</div>
