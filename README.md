<div align="center">
<h1>FFENet </h1>
<h3>Efficient Feature Focus Enhanced Network for Small and Dense Object Detection in SAR Images</h3>
</div>


Based on the **[MMdetection](https://github.com/open-mmlab/mmdetection) 3.1.0** framework, this project modifies its data flow and related classes and functions, and changes the MMdetection to a  detection framework to facilitate **SAR Object Detection**.

## **Overview**

<p align="center">
  <img src="README.assets\pipeline.png" alt="overview" width="90%">
</p>


## **Main Results**

**`Dataset: HRSID and LS-SSDD-V1.0`**


## **Getting Started**

### Installation

ref : [mmdetection installation](https://mmdetection.readthedocs.io/en/latest/get_started.html)

**Step 1: Clone the FFE-YOLO repository:**

To get started, first clone the FFE-YOLO repository and navigate to the project directory:

```bash
git clone https://github.com/CongLi-18/FFE-YOLO.git
cd FFE-YOLO
```

**Step 2: Environment Setup:**

FFE-YOLO recommends setting up a conda environment and installing dependencies via pip. Use the following commands to set up your environment:

***Create and activate a new conda environment***

```bash
conda create -n FFE-YOLO
conda activate FFE-YOLO
```

***If you develop and run mmdet directly, install it from source***

```
pip install -v -e .
```

***Install Dependencies***

```bash
pip install -r requirements.txt
pip install -r requirements_rgbt.txt
```

## :white_check_mark: Updates
* **` Novermber. 18th, 2024`:** The source code is provided. 

## **Acknowledgment**
