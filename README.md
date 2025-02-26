# Depth Reconstruction with Deep Neural Networks

## Overview

This project focuses on implementing a deep neural network for depth reconstruction from 2 images from different perspective. It follows the pioneering work of Eigen et al. ([2014](https://arxiv.org/pdf/1406.2283.pdf), [2015](https://openaccess.thecvf.com/content_iccv_2015/papers/Eigen_Predicting_Depth_Surface_ICCV_2015_paper.pdf)) and uses the [KITTI dataset](http://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=stereo) for training and evaluation.

## Features

- Utilizes convolutional neural networks (CNNs) for depth estimation.
- Works with the KITTI dataset for real-world depth estimation.
- Implements data augmentation and preprocessing techniques.
- Uses TensorFlow for model training and inference.

## Dataset

The project uses the KITTI dataset, which provides high-quality depth maps. You can obtain the dataset from [KITTI Stereo Benchmark](http://www.cvlibs.net/datasets/kitti/eval_scene_flow.php?benchmark=stereo).

## Installation

To set up the environment, install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the Jupyter Notebook to train and evaluate the model:

```bash
jupyter notebook KITTI.ipynb
```

## Results

The trained model predicts depth maps from single RGB images, enabling applications in autonomous driving and 3D scene understanding.

## References

- Eigen et al., "Predicting Depth, Surface Normals and Semantic Labels with a Common Multi-Scale Convolutional Architecture," ICCV 2015.
- KITTI Vision Benchmark Suite: [http://www.cvlibs.net/datasets/kitti/](http://www.cvlibs.net/datasets/kitti/)

## License

This project is for educational purposes and follows the licensing terms of the KITTI dataset.

