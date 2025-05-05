
# README

## 📌 Project Overview
This project utilizes PyTorch for deep learning tasks, by packaging ResNet50V2 to a Mask rcnn for fine-tuning and evaluation, doing a cell segementation task.

## 🛠 How to Install

### 1️⃣ Install Python
Ensure you have **Python 3.8 or later** installed on your system. You can download it from the official Python website: [Python.org](https://www.python.org/downloads/)

### 2️⃣ Install PyTorch
Choose the appropriate version based on your hardware:

**For GPU (CUDA 11.8)**:
```bash
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

**For CPU only**:
```bash
pip install torch torchvision torchaudio
```

For more installation options, refer to the [official PyTorch website](https://pytorch.org/get-started/locally/).

### 3️⃣ Install Required Dependencies
```bash
pip install pillow pandas
```

### 4️⃣ Verify Installation
Run the following script to check if PyTorch is correctly installed:
```python
import torch
print("Torch Version:", torch.__version__)
print("CUDA Available:", torch.cuda.is_available())
```
### 5️⃣ Install Dataset
https://drive.google.com/file/d/1B0qWNzQZQmfQP7x7o4FDdgb9GvPDoFzI/view?usp=sharing

## ✍️ Author
**Student ID:** 111550173  
**Name:** 林庠安  
**Instructor:** 林彥宇  

---
## Performance Snapshot
![Description](https://github.com/Seanlin0911/NYCU-DLCV-2025-Spring/blob/main/Hw3/score%20board.png)

## 📜 License
This project is for educational purposes. Feel free to modify and use it!


