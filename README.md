## Frequency-Enhanced and Spatial-Guided Feature Pyramid Network for Tiny Object Detection in Remote Sensing Images

This repository contains the source code associated with the manuscript:
"Frequency-Enhanced and Spatial-Guided Feature Pyramid Network for Tiny Object Detection in Remote Sensing Images" (Under Review).

### Update Status
The full source code and pre-trained models will be integrated continuously upon official publication.

### 1. Required environments:

- Linux
- Python 3.9.23
- PyTorch 2.0.0
- CUDA 11.8
- MMDetection 3.1.0

### 2. Install and start LASER-FPN:

Note that our LASER-FPN is based on MMDetection 3.1.0. Assuming that your environment satisfies the above requirements, please follow these steps for installation:

```bash
git clone https://github.com
cd LASERFPN
pip install -r requirements.txt
python setup.py develop
```

### Prepare Dataset:

- Download [AI-TODv2 Dataset](https://drive.google.com/drive/folders/1Er14atDO1cBraBD4DSFODZV1x7NHO_PY)
- Download [VisDrone2019 Dataset](https://github.com/VisDrone/VisDrone-Dataset)

