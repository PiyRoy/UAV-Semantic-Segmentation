# UAV-Semantic-Segmentation
This repository contains a collection of deep learning–based semantic segmentation models for aerial (UAV) imagery, implemented and experimented primarily using UAVid and Aeroscapes datasets. The work focuses on analyzing and comparing different attention mechanisms integrated with popular encoder–decoder architectures such as U-Net, SegNet, SegUNet, and UNet3+. The repository is intended for research, experimentation, and academic use, especially for students and researchers working on remote sensing, UAV vision, and semantic segmentation.

Models & Attention Mechanisms Implemented:

🔹 Architectures
- U-Net
- SegNet
- UNet3+
- SegUNet

🔹 Attention Modules
- BAM (Bottleneck Attention Module)
- CBAM (Convolutional Block Attention Module)
- SAM (Self-Attention Module)
- scSE (Concurrent Spatial and Channel Squeeze-and-Excitation)
- SE (Squeeze-and-Excitation)

Datasets Used:
- UAVid
- Aeroscapes
  
Datasets are not included in this repository due to size and licensing. Please download them from their official sources and update dataset paths inside the notebooks.



Note: Filenames reflect the architecture + attention module + dataset used. AeroUNet3+ and SpaCENet are custom attention modules modified by me and my co-authors.
