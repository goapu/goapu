# Hi, I'm Dilip Goswami 👋

**Computer Vision Engineer based in Berlin, Germany**

I build geometrically grounded computer vision systems for **3D reconstruction,
medical imaging, RGB-D sensor fusion and AR-assisted navigation**.

My work spans the complete perception pipeline—from data capture and model
development to geometric evaluation, backend APIs and deployment.

## Current work

- Developing monocular 3D facial reconstruction and privacy-preserving
  visual-learning systems
- Building an iPhone ARKit RGB-D scanning platform with a Python/Open3D backend
- Exploring robust registration, reconstruction and spatial evaluation methods

## Selected engineering results

- **1.205 mm mean surface error** in preoperative-to-intraoperative
  anatomical registration
- **94.1% of evaluated points within 3 mm**
- **91.8% accuracy** and **92.7% macro F1** for anatomical viewpoint
  classification
- Registration evaluation performed across **19,150+ surface samples**

## Featured projects

### [myHut](REPOSITORY_URL)
**iPhone ARKit RGB-D capture and 3D reconstruction**

An end-to-end spatial capture system combining a SwiftUI/ARKit application
with a Python and Open3D reconstruction backend.

`Swift` `ARKit` `SwiftUI` `Python` `Open3D` `FastAPI` `RGB-D` `TSDF`

Key capabilities:

- synchronized RGB, depth, confidence, intrinsics and camera-pose capture;
- object and room scanning workflows;
- TSDF-based volumetric reconstruction;
- keyframe selection and scan-quality diagnostics;
- confidence-aware room measurements;
- Chamfer-distance and F-score evaluation;
- API-based processing and artifact generation.

---

### [Medical 3D Registration](REPOSITORY_URL)
**Registration for AR-guided endonasal surgery**

A coarse-to-fine pipeline for aligning preoperative anatomical models with
intraoperative 3D observations.

`Python` `Open3D` `PyTorch` `Kabsch` `RANSAC` `ICP`

Includes:

- semantic initialization;
- scale normalization and landmark alignment;
- robust spatial refinement;
- point-to-surface error analysis;
- convergence reporting, CDF plots and mesh error maps.

**Evaluation:** 1.205 mm mean error, 1.557 mm RMSE and 94.1% of samples
within 3 mm.

---

### [Endoscopic Dataset Pipeline](REPOSITORY_URL)
**Reproducible frame extraction for annotated surgical videos**

A resumable multiprocessing pipeline for converting temporal annotations and
endoscopic videos into structured machine-learning datasets.

`Python` `OpenCV` `Multiprocessing` `Data Validation`

Features sequential decoding, annotation normalization, quality filtering,
metadata generation, audit manifests and recovery from interrupted runs.

## Technical focus

**Vision and geometry:** 3D registration, RGB-D fusion, TSDF reconstruction,
camera calibration, point clouds, mesh processing and surface-distance metrics

**Machine learning:** PyTorch, semantic segmentation, image classification,
transfer learning, vision transformers and limited-data training

**Engineering:** Python, C++, Swift, FastAPI, Docker, CI/CD, GitHub Actions
and reproducible evaluation pipelines

## Background

I hold an M.Sc. in Geodesy and Geoinformation Science from Technische
Universität Berlin, specializing in photogrammetric computer vision,
remote sensing and multi-sensor navigation.

My master's research at Institut Pascal focused on automatic registration of
preoperative and intraoperative views for AR-guided endonasal surgery.

## Connect

[LinkedIn](https://www.linkedin.com/in/dilip-goswami-853018108/) ·
[ResearchGate](https://www.researchgate.net/profile/Dilip-Goswami-2) ·
[Email](mailto:gshubro@yahoo.com)
