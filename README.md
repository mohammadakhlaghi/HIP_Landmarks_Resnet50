# HIP Landmarks Detection using ResNet50

This repository contains the implementation of a **two-stage ResNet50-based model** for detecting hip geometrical landmarks in X-ray images. This model builds upon the work in the **HipLandmarkDetection** project by Mahdie Aghasi, which utilized a VGG-based approach. By leveraging ResNet50, our method achieves improved accuracy in detecting anatomical landmarks crucial for hip measurements.

## 📌 Overview
Hip anatomical landmark detection plays a key role in **preoperative planning for hip replacement arthroplasty**. Precise localization of these landmarks enables accurate measurement of hip parameters, leading to better surgical outcomes.

## 🔬 Research Publication
Our work has been published in **The Archives of Bone and Joint Surgery**:

**"Deep Learning-based Detection of Hip Anatomical Landmarks in X-ray Images"**

Please cite our article if you use this model in your research.

## 🏗️ Model Details
- **Architecture:** Two-stage deep learning model based on ResNet50.
- **Dataset:** Trained on the same dataset as the original VGG-based model.
- **Performance:** Achieves improved accuracy compared to the previous VGG-based approach.

## 📊 Data Availability
The data that support the findings of this study are available from the corresponding author upon reasonable request.

## 🔍 Related Work
This project is developed in collaboration with **Mahdie Aghasi**, who initially proposed a **VGG-based two-stage model** for hip landmark detection. You can find the original work [here](https://github.com/MahdieAghasi/HipLandmarkDetection).

## 🚀 Usage
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/mohammadakhlaghi/HIP_Landmarks_Resnet50.git
cd HIP_Landmarks_Resnet50
```
### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```
### 3️⃣ Run Inference
```sh
python test.py --image_path /path/to/xray.jpg
```

## 📬 Citation
If you find this work useful, please consider citing our paper:
```
@article{your_citation_here,
  title={Deep Learning-based Detection of Hip Anatomical Landmarks in X-ray Images},
  author={Mohammad Akhlaghi, Mahdie Aghasi, et al.},
  journal={The Archives of Bone and Joint Surgery},
  year={202X}
}
```

## 📝 License
This project is licensed under **[Your Chosen License]**.

---
Feel free to reach out in case of any questions or contributions!
