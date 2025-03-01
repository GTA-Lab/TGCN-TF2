# TGCN-TF2

Implementation of T-GCN with Tensorflow 2 for efficient processing of temporal data and graphs

---

# T-GCN Implementation in TensorFlow 2.x

This repository contains the implementation of the **Temporal Graph Convolutional Network (T-GCN)** model, originally proposed in the paper:  
**[T-GCN: A Temporal Graph Convolutional Network for Traffic Prediction](https://ieeexplore.ieee.org/document/8809901)**.  

The original implementation was written in **TensorFlow 1.x** and can be found here:  
[https://github.com/lehaifeng/T-GCN/tree/master/T-GCN/T-GCN-TensorFlow](https://github.com/lehaifeng/T-GCN/tree/master/T-GCN/T-GCN-TensorFlow).  

This repository provides an updated version of the code, migrated to **TensorFlow 2.x**, by **Amiri & Mostafazade**. The updated code is compatible with the latest TensorFlow APIs and includes improvements for better usability and performance.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Dataset](#dataset)
4. [Usage](#usage)
6. [Contributors](#contributors)
7. [Citation](#citation)
8. [License](#license)

---

## Introduction
T-GCN is a deep learning model designed for traffic prediction, combining Graph Convolutional Networks (GCN) and Gated Recurrent Units (GRU) to capture both spatial and temporal dependencies in traffic data. This implementation provides a TensorFlow 2.x version of the original model, making it easier to use with modern deep learning workflows.

---

## Requirements
To run the code, ensure you have the following dependencies installed:
- Python 3.x
- TensorFlow 2.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib (for visualization)

---

## Dataset
The model is trained and evaluated on traffic datasets, which typically include traffic speed or flow data. The dataset used in the original paper are included in the `data/` folder.

---

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/GTA-Lab/TGCN-TF2.git
   cd TGCN-TF2
   Run T-GCN-TensorFlow.ipynb
---

## Contributors
- **Amiri & Mostafazade**: Migrated the original TensorFlow 1.x code to TensorFlow 2.x and improved the codebase.  
- **Original Authors**: The T-GCN model was originally developed by the authors of the paper linked above.

---

## Citation
If you use this code or the T-GCN model in your research, please cite the original paper:
```bibtex
@article{doi:10.1109/TITS.2019.2935152,
  author = {Zhao, Ling and Song, Yu and Zhang, Chao and Liu, Yu and Wang, Pu and Lin, Tao and Deng, Min and Li, Haifeng},
  title = {T-GCN: A Temporal Graph Convolutional Network for Traffic Prediction},
  journal = {IEEE Transactions on Intelligent Transportation Systems},
  volume = {21},
  number = {9},
  pages = {3848-3858},
  year = {2020},
  doi = {10.1109/TITS.2019.2935152}
}
```

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to open an issue or submit a pull request if you have any suggestions or improvements!

---

This `ReadMe` provides a clear overview of the repository, its purpose, and how to use it. Let me know if you need further adjustments!