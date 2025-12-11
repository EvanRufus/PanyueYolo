# 👵 YOLOv5 行人跌倒检测项目<br/>👴 YOLOv5-Fall-Detection-Research



## 🎯 项目概览 (Project Overview)

本项目是基于 **PyTorch** 深度学习框架和 **YOLOv5** 目标检测模型开展的**人体跌倒检测研究**，旨在探索计算机视觉在行为识别和智能安全监控领域的应用。本项目的核心目标是训练一个高鲁棒性的模型，并对其性能进行严谨的评估和优化。

This project is a **human fall detection research project** based on the **PyTorch** deep learning framework and **YOLOv5** object detection model. It aims to explore the application of computer vision in behavior recognition and intelligent safety monitoring. The core objective is to train a robust model, rigorously evaluate its performance.



## 🛠️ 技术栈 (Tech Stack)

| 类别 (Category) | 技术/工具 (Technology/Tool) |
| :--- | :--- |
| **模型架构 (Model)** | YOLOv5 (PyTorch) |
| **编程语言 (Language)** | Python 3.11 |
| **硬件环境 (Hardware)** | [NVIDIA GPU型号, e.g., RTX 4060] |
| **核心依赖 (Core Dependencies)** | `torch`, `torchvision`, `opencv-python` |



## ⬇️ 部署教程 (Getting Started)

### 1. 环境准备 (Environment Setup)

请确保您的系统安装了 Git、Conda 或 Venv，并拥有 CUDA 环境（如果使用 GPU）。

```bash
# 克隆仓库 (Clone the repository)

# 创建并激活环境 (Create and activate the environment)
conda create -n fall_research_env python=3.10
conda activate fall_research_env