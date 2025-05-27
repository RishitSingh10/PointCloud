# Point Cloud Processing

A beginner-friendly tutorial on point cloud processing using Open3D. This repo walks through the full pipeline — from data preparation to segmentation and classification — with clear explanations of the math and computer vision concepts behind each step.

---

## Follow the Notebook Order

1. [intro_point_cloud_processing.ipynb](./intro_point_cloud_processing.ipynb)  
  Intro to point clouds, Open3D basics.

2. [point_cloud_from_depth.ipynb](./point_cloud_from_depth.ipynb)  
  Estimate 3D point clouds from 2D images from scratch using numpy.
---

## Setup

```bash
git clone git@github.com:RishitSingh10/pointcloud.git
cd pointcloud

# Create and activate virtual environment using uv
uv venv
.venv\Scripts\activate

# Install dependencies
uv pip install -r pyproject.toml
```
