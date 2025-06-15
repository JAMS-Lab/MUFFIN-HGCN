# 🚗 MUFFIN-HGCN: Multi-feature Fusion Hierarchical-GCN for 3D Object Detection

This repository provides the implementation of **MUFFIN-HGCN**, a novel framework for 3D object detection from LiDAR point clouds and RGB images.

## 🔍 Overview

Accurate 3D object detection in point clouds is challenging due to the non-Euclidean nature and sparsity of LiDAR data. Our method addresses these issues through a two-stage deep learning framework:

### ✨ Key Features

- **Multimodal Feature Fusion with Transformers**: Fuses RGB image semantics and LiDAR geometry without relying on camera extrinsics, enabling precise point-to-pixel association.
- **Hierarchical Graph Convolutional Network (HGCN)**: Efficiently captures spatial structures in non-Euclidean point clouds for robust object representation.
- **End-to-End Detection Pipeline**: Integrates semantic enrichment and geometric reasoning to achieve accurate 3D object detection.

Validated on **KITTI** and **nuScenes** datasets, MUFFIN-HGCN demonstrates strong performance in detecting vehicles, pedestrians, and other dynamic targets.

---

## 📄 Citation

If you find this work helpful, please cite:

```bibtex
@ARTICLE{Liu2025_MUFFIN_HGCN,
  author={Liu, Chang and Jiang, Aimin and Zhou, Jia and Li, Min and Zhu, Yanping and Kwan, Hon Keung},
  journal={IEEE Transactions on Vehicular Technology}, 
  title={MUFFIN-HGCN: Multi-feature Fusion Hierarchical-GCN for 3D Object Detection}, 
  year={2025},
  volume={},
  number={},
  pages={1--13},
  doi={10.1109/TVT.2025.3566696}
}
