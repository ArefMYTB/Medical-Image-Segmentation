# Medical Image Segmentation with MONAI - Prostate MRI

This repository demonstrates **3D medical image segmentation** using the [MONAI](https://monai.io/) framework on the **Task05_Prostate** dataset from the [Medical Segmentation Decathlon](http://medicaldecathlon.com/). The project implements advanced **3D data augmentation**, **transfer learning**, and **SwinUNETR** architecture for accurate organ segmentation.

---

## Features

- **Framework**: MONAI
- **Model**: [SwinUNETR](https://monai.io/research/swinunetr) (Transformer-based UNet for volumetric data)
- **Transfer Learning**: Pretrained weights used for initialization
- **Loss Function**: `DiceCELoss` (combines Dice loss with cross-entropy for better convergence)
- **Metric**: `dice_metric`
- Train Loss: 0.6702 (With 20 Epoch)
- **3D Data Augmentation**:
  - Random flips (spatial)
  - Random rotations
  - Intensity shifts
  - Gaussian noise
    
---

## Visualization Example

<img width="977" height="339" alt="image" src="https://github.com/user-attachments/assets/bba1e479-c8d2-4a6d-9815-8b2fc3fb1bad" />
