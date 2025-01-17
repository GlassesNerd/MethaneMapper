## MethaneMapper: Spectral Absorption aware Hyperspectral Transformer for Methane Detection

MethaneMapper is a fast and accurate deep learning based solution for methane detection from airborne hyperspectral imagery. MethaneMapper introduces a spectral absorption wavelength aware transformer network and largest public dataset called Methane HotSpot dataset (MHS). This repository contains code for MethaneMapper, scripts to download and online tool to visualize dataset.

### [**MethaneMapper: Spectral Absorption aware Hyperspectral Transformer for Methane Detection**](https://openaccess.thecvf.com/content/CVPR2023/papers/Kumar_MethaneMapper_Spectral_Absorption_Aware_Hyperspectral_Transformer_for_Methane_Detection_CVPR_2023_paper.pdf)
[Satish Kumar*](https://www.linkedin.com/in/satish-kumar-81912540/), [Ivan Arevalo](https://www.linkedin.com/in/ivanfarevalo/), [A S M Iftekhar](), [B S Manjunath](https://vision.ece.ucsb.edu/people/bs-manjunath).

Official repository of our [**CVPR 2023 (Highlights)**](https://openaccess.thecvf.com/content/CVPR2023/papers/Kumar_MethaneMapper_Spectral_Absorption_Aware_Hyperspectral_Transformer_for_Methane_Detection_CVPR_2023_paper.pdf) paper.

<img src="./docs/mainpage_github.gif" width="700">

This repository includes:
* Source code of MethaneMapper.
* Pre-trained weights for methane plume bounding box detector and segmentation mask
* Scripts to download MHS dataset
* Online tool to visualize MHS dataset ([**BisQue**](https://bisque2.ece.ucsb.edu/client_service/view?resource=https://bisque2.ece.ucsb.edu/data_service/00-kKkPJUHK6KJDEVBRfDpmmA))
* Code for custom data preparation for training/testing
* Code for mapping ground truth masks from CarbonMapper to AVIRIS-NG flightline
* Annotation generator to read-convert mask annotation into json.


![supported versions](https://img.shields.io/badge/python-(3.8--3.10)-brightgreen/?style=flat&logo=python&color=green)
![Library](https://img.shields.io/badge/Library-Pytorch-blue)
![GitHub license](https://img.shields.io/cocoapods/l/AFNetworking)


The repository follows the structure of paper, making it easy to follow and use/extend the work. If this research is helpful to you, please consider citing our paper (bibtex below)

## Citing
If this research is helpful to you, please consider citing our paper:
```
@inproceedings{kumar2023methanemapper,
  title={Methanemapper: Spectral absorption aware hyperspectral transformer for methane detection},
  author={Kumar, Satish and Arevalo, Ivan and Iftekhar, ASM and Manjunath, BS},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={17609--17618},
  year={2023}
}
```

## Usage

### Requirements
- Linux or macOS with Python >= 3.7
- Pytorch >= 1.7.0
- CUDA >= 10.0
- cudNN (compatible with CUDA)

### Installation
1. Clone the repository
2. Install dependencies
```
pip install -r requirements.txt
```

### Data Visualization
Please checkout to the [BisQue](https://github.com/UCSB-VRL/MethaneMapper-Spectral-Absorption-aware-Hyperspectral-Transformer-for-Methane-Detection/blob/main/data/visualize_data/README.md)


### Download Methane HotSpot (MHS) Dataset
Please follow the tutorial [MHS_dataset](https://github.com/UCSB-VRL/MethaneMapper-Spectral-Absorption-aware-Hyperspectral-Transformer-for-Methane-Detection/tree/main/mhs_dataset) to download dataset

### Training
Follow the training tutorial [Here](https://github.com/UCSB-VRL/MethaneMapper-Spectral-Absorption-aware-Hyperspectral-Transformer-for-Methane-Detection/blob/main/methanemapper/README.md)

## For Developers
Please refer to [CONTRIBUTING.md](https://github.com/UCSB-VRL/MethaneMapper-Spectral-Absorption-aware-Hyperspectral-Transformer-for-Methane-Detection/blob/main/docs/CONTRIBUTING.md) for contribution to the repository. Thank you!

## License
MethaneMapper is released under the UCSB license. Please see the [LICENSE](./LICENSE) file for more information.
