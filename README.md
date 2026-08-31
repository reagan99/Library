# Library

> **Official MPEG 3D Gaussian Splatting (3DGS) Test Dataset**  
> Selected for **ISO/IEC JTC 1/SC 29/WG 4 (MPEG) – Gaussian Splat Coding (GSC) Common Test Conditions**

**Institution:** Sungkyunkwan University (SKKU)  
**Captured by:** IMCLab & Department of Immersive Media Engineering  
**Version:** October 2025  
**Source:** [Download Dataset](http://gofile.me/6uap5/r5zzOBuMZ)

---

## 🖼️ Visual Overview

Representative images from the **Library Sequence**, captured on the SKKU main campus.  
They illustrate the dataset’s **architectural scale**, **lighting diversity**, and **reflective surfaces**.

---

### Aerial Overview
![Aerial View of Library](images/library_overview.png)

---

### Drone Path
![Drone Path](images/library_drone.png)

---

### Render
![Render](images/library_facade.png)

> The images above are sample previews.  
> Full-resolution 4K imagery and corresponding calibration data are available in the linked dataset.

---

## 🏛️ Overview

The **Library Sequence** is a large-scale **3D Gaussian Splatting dataset** captured at **Sungkyunkwan University’s central library area**, featuring both aerial and ground-level perspectives.  
It provides **high-resolution image sequences** for evaluating **Gaussian Splatting**, **3D reconstruction**, and **view-synthesis** techniques.

The dataset replicates **real-world campus-scale environments** with complex **lighting**, **architectural**, and **specular reflection** characteristics, making it suitable for evaluating realistic rendering and coding systems.

---

## 📷 Capture Setup

| Property | Description |
|-----------|-------------|
| **Capture Device** | DJI Mavic 3 Pro (Tele Lens 166 mm @ f/3.4) |
| **Altitude** | 50 m / 70 m |
| **Coverage Area** | Approx. 98,000 m² (Library & Courtyard Zone) |
| **Environment** | Outdoor daylight, varying illumination and reflections |


## 📦 Dataset Availability

| Dataset | Description | Size | Download |
|---------|-------------|------|----------|
| **4K Dataset** | 4,000 training images | 40 GB | [Download](http://gofile.me/6uap5/XBg5YWxcE) |
| **FHD-100** | 100 training images + 200 common test images | 2.67 GB | [Download](http://gofile.me/6uap5/o6DXV7DSi) |
| **FHD-200** | 200 training images + 200 common test images | 3.58 GB | [Download](http://gofile.me/6uap5/owoVtn7Hh) |
| **FHD-400** | 400 training images + 200 common test images | 5.43 GB | [Download](http://gofile.me/6uap5/rOn2X86JY) |
| **FHD-800** | 800 training images + 200 common test images | 9.19 GB | [Download](http://gofile.me/6uap5/gDoNc93Rt) |
| **FHD-1600** | 1,600 training images + 200 common test images | 17.04 GB | [Download](http://gofile.me/6uap5/l0w1HRQjO) |

> **Note:** In each FHD subset, the 200 common test images are prefixed with `test_` and must be excluded from 3DGS training.

---

## 🌤️ Scene Characteristics

- **Architectural diversity:** combination of glass, stone, and concrete façades  
- **Dynamic lighting:** morning to late-afternoon captures with moving shadows  
- **Reflective materials:** large window façades and metal panels for specular effects  
- **Outdoor openness:** trees, paths, and plazas with wide-area continuity  
- **Realistic complexity:** natural lighting transitions ideal for photometric testing  

---

## 📄 Citation and References

If you use or refer to this dataset, please cite:

Additional references for the MPEG standardization context:

> **ISO/IEC JTC 1/SC 29/WG 4 (MPEG Video Coding Group)**  
> *Gaussian Splat Coding (GSC) – Common Test Conditions (CTC)*  
> Contribution: ISO/IEC JTC 1/SC 29/WG 4 m74011, Geneva, October 2025.  
>  
> **Library Sequence** was officially introduced and adopted as a **representative large-scale scene** for GSC evaluation,  
> providing coverage of architectural, specular, and outdoor conditions suitable for **Gaussian-based 3D scene coding** experiments.
@inproceedings{koo2026library,
  author    = {Reagan Koo and Yeong-Gyu Kim and Isaac Yang and Seung Ahn and Eun-Seok Ryu},
  title     = {Library: A Large-Scale Outdoor Gaussian Splat Reconstruction Dataset},
  booktitle = {Proceedings of the IEEE Conference on Virtual Reality and 3D User Interfaces Workshops (VRW)},
  year      = {2026},
  pages     = {153--156},
  doi       = {10.1109/VRW70859.2026.00033}
}
> https://imclab.skku.edu/MCSL/wp-content/uploads/2026/03/052900a153.pdf
---

## 🔗 Related Links

- MPEG WG 4 (Video Coding) — Gaussian Splat Coding (GSC)  
- IMCLab, Sungkyunkwan University — [https://imclab.skku.edu/](https://imclab.skku.edu/)  
