# 🌿 Weed Detector – YOLOv5 + Google Colab

This project detects weeds in crop field images using a **YOLOv5** deep learning model.  
It is designed for use in Google Colab but can also be run locally.

---

## 📌 Features
- Weed detection using YOLOv5 object detection.
- Supports **image uploads** and **live camera input**.
- Pre-trained on a custom dataset from Roboflow.
- Outputs **annotated images** with detected weed locations.
- Can be adapted for different crops and weed types.

---

## 📂 Project Structure
Weed Detector.ipynb # Main Google Colab notebook
datasets/ # Dataset folder (YOLOv5 format)
├── images/
└── labels/
runs/ # YOLOv5 output folder (inference results)

---

## 🛠 Requirements
If running locally:
- Python 3.8+
- [PyTorch](https://pytorch.org/)
- YOLOv5 dependencies:
```bash
pip install torch torchvision torchaudio
pip install -r requirements.txt
![Lantana_20170715-120750-1_jpg rf dbefb925e592e72bf52ac5238094d6a9](https://github.com/user-attachments/assets/ee69e779-de9e-4b63-884f-5a7e59bd9532)
