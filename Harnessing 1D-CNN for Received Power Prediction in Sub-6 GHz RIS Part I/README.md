# Harnessing 1D-CNN for Received Power Prediction in Sub-6 GHz RIS: Part I

## Abstract
This work addresses the prediction of received power at the receiver (Rx) in a reconfigurable intelligent surface (RIS)-assisted wireless communication system under varying beam-steering configurations (azimuth and elevation). Received power is influenced by multiple factors, including the beamforming strategy, the Tx–RIS and RIS–Rx distances, and the surrounding propagation environment. We leverage the ability of one-dimensional convolutional neural networks (1D-CNNs) to capture spatial correlations across beam-steering angles and accurately model power variations in a dynamic channel. Using an available dataset containing received power measurements across a range of beamforming angles, the proposed 1D-CNN learns patterns and trends in power fluctuations that are critical for efficient beam selection and improved communication performance. Experimental results across all k-fold cross-validation folds demonstrate that the proposed model achieves high prediction accuracy and outperforms several baseline deep learning approaches, enabling more efficient resource allocation and enhanced overall system performance.

## Publication
**DOI:** 10.1109/ICCWorkshops67674.2025.11162261

## Dataset
**Repository:** https://github.com/marcantonio14/RIS-Power-Measurements-Dataset

## Citation (BibTeX)
```bibtex
@inproceedings{hassan2025harnessing,
  title={Harnessing 1D-CNN for Received Power Prediction in Sub-6 GHz RIS: Part I},
  author={Hassan, Muhammad Abul and Granelli, Fabrizio},
  booktitle={2025 IEEE International Conference on Communications Workshops (ICC Workshops)},
  pages={917--922},
  year={2025},
  organization={IEEE}
}
