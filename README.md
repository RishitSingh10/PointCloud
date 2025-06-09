# Point Cloud Processing

A beginner-friendly tutorial on point cloud processing using Open3D. This repo walks through the full pipeline — from data preparation to segmentation and classification — with clear explanations of the math and computer vision concepts behind each step.

---

## Follow the Notebook Order

1. [intro_point_cloud_processing.ipynb](./intro_point_cloud_processing.ipynb)<br>
  Intro to point clouds, Open3D basics.

2. [point_cloud_from_depth.ipynb](./point_cloud_from_depth.ipynb)<br>
  Estimate 3D point clouds from 2D images from scratch using numpy. Generate coloured point clouds from RGB image.

3. [ground_detection.ipynb](./ground_detection.ipynb)<br>
  Intro to 3D coordinate system and ground detection using thresholding. Also introducing organized point clouds.

4. [point_cloud_filtering.ipynb](./point_cloud_filtering.ipynb)<br>
  Filter point clouds for down-sampling and outlier removal.

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
