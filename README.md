# Enhancing Classification of Energy Meters with Limited Labels using a Semi-Supervised Generative Model

This repository contains all the necessary datasets and Jupyter notebooks used in our research, "Enhancing Classification of Energy Meters with Limited Labels using a Semi-Supervised Generative Model" in the 10th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation (BuildSys’23), November 15–16, 2023, Istanbul, Turkey.

## Research Abstract

In the energy domain, the classification of power meters has become an increasingly significant area of interest, such as appliance identification and characteristics prediction, enabling targeted and efficient energy management. However, the limited availability of labeled data for power meters and the inconsistencies in labeling and naming conventions have constrained the potential of metadata for further application. This study aims to bridge the gap by employing semi-supervised Generative Adversarial Networks (SGAN) to classify 1805 power meters distributed globally. This approach explores and assesses the advantages of incorporating unlabeled power meter data into the learning process. A comparative analysis is performed between supervised and semi-supervised baseline models using different proportions of labeled data. The results reveal that SGAN can achieve an accuracy rate exceeding 0.8 with just 100 labeled samples, whereas a Two-dimensional Convolution Neural Network (2D-CNN) requires a minimum of 300 samples to attain the same performance level. The innovative contribution of this study lies in formulating a refined classification model and a label propagation method that optimizes the use of unlabeled energy meter data. Additionally, the classification framework established in this study has the potential for expanded application in categorizing other metadata.

## Repository Content

This repository is organized as follows:

1. **Notebooks**: This directory contains all Jupyter notebooks that provide the code implementations of the various techniques used in the research.

2. **Data**: Due to the constraints posed by the Github platform, the dataset used in our research is not provided here. Nevertheless, the energy dataset (including meter data, metadata, and weather data) could be found on [Kaggle website](https://www.kaggle.com/competitions/ashrae-energy-prediction/data) or [BDG2 Github repository](https://github.com/buds-lab/building-data-genome-project-2).

## License

This project is licensed under the terms of the MIT license.
