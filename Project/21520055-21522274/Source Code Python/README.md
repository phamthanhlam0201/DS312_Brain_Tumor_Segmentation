# Tạo 1 Notebook trên Kaggle

# Add Input (https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation) vào Notebook

# Cài đặt 1 số thư viện hỗ trợ YOLO
!pip install -U ultralytics
!pip install -U ipywidgets
!pip install -U ray

# Import 1 số thư viện cần dùng như sau: 
from PIL import Image
import numpy as np
import pandas as pd
import os
import cv2
import matplotlib.pyplot as plt
from glob import glob
from sklearn.model_selection import train_test_split
from ultralytics import YOLO

# Thiệt lập ngôn ngữ Python và chọn Accelerator là GPU T4x2

# Lưu version Notebook và thực hiện chạy đoạn mã

# Có thể chạy từng cell hoặc Run all toàn bộ đoạn mã