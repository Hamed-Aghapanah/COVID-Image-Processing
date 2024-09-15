
# COVID-19 Imaging Datasets for Machine Learning and Image Processing

This repository provides a comprehensive collection of publicly available datasets for COVID-19 detection through various image modalities, such as CT scans and X-rays. These datasets have been crucial for training machine learning (ML) and deep learning (DL) models used in tasks like image **segmentation**, **classification**, and **localization**. The goal of this repository is to facilitate further research and application in the field of medical imaging, especially in the context of COVID-19.

## Table of Datasets

| Dataset Name                    | Modality        | Images (Train/Test)               | Labels                              | Access Link                                                    |
|----------------------------------|-----------------|-----------------------------------|-------------------------------------|---------------------------------------------------------------|
| **COVID-CTset**                 | CT              | 349/100                           | Positive, Negative                  | [COVID-CTset](https://www.medrxiv.org/content/10.1101/2020.03.16.20036145v3) |
| **COVIDx**                      | Radiography     | 13,975/400                        | Normal, Pneumonia, COVID-19         | [COVIDx](https://www.covid-net.ca/)                           |
| **MosMedData**                  | CT              | 1,111/276                         | Mild, Moderate, Severe              | [MosMedData](https://mosmed.ai/)                              |
| **SIRM**                        | Radiography, CT | 1000+ (exact number not available) | Positive, Negative                  | [SIRM Database](https://www.sirm.org/category/senza-categoria/covid-19/) |
| **BIMCV-COVID19+**              | Radiography     | 1,200+ (exact number not available) | Normal, COVID-19                    | [BIMCV-COVID19+](https://bimcv.cipf.es/bimcv-projects/bimcv-covid19/) |
| **Covid Dataset Qatar IEEE**     | CT, X-ray       | N/A                               | Normal, Pneumonia, COVID-19         | [Covid Dataset Qatar IEEE](https://ieeexplore.ieee.org/document/9314069) |
| **Covid Dataset Isfahan**        | CT, X-ray       | N/A                               | Normal, COVID-19                    | [Covid Dataset Isfahan](https://data.mendeley.com/datasets)   |
| **Covid Dataset Kohen**          | CT, X-ray       | N/A                               | Positive, Negative                  | [Covid Dataset Kohen](https://github.com/ieee8023/covid-chestxray-dataset) |
| **Covid-19 Image Dataset**       | Radiography     | 5000+ (exact number not available) | Normal, Pneumonia, COVID-19         | [Covid-19 Image Dataset](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset) |
| **COVID-19 Radiography Database**| Radiography     | 21,165+ (exact number not available) | Normal, Pneumonia, COVID-19         | [COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database) |
| **AIforCOVID Imaging Archive**   | CT, X-ray       | 983 patients                      | Positive, Negative                  | [AIforCOVID Imaging Archive](https://aiforcovid.radiomica.it/) |
| **Radiopaedia Database**         | Radiography     | 101 patients                      | COVID-19                            | [Radiopaedia Database](https://radiopaedia.org/articles/covid-19-3) |
| **UCSD COVID-CT Database**       | CT              | 349 images from 216 patients       | COVID-19                            | [UCSD COVID-CT Database](https://github.com/UCSD-AI4H/COVID-CT) |
| **CT Machine Learning Dataset**  | CT              | 930 images from 461 patients       | COVID-19                            | [CT Machine Learning Dataset](https://github.com/ieee8023/covid-chestxray-dataset) |
| **CT Segmentation Dataset 1**    | CT              | 100 images from 40 patients        | COVID-19                            | [CT Segmentation Dataset 1](http://medicalsegmentation.com/covid19) |
| **CT Segmentation Dataset 2**    | CT              | 800 slices from 9 patients         | COVID-19                            | [CT Segmentation Dataset 2](http://medicalsegmentation.com/covid19) |
| **CT Segmentation Dataset 3**    | CT              | 20 cases                          | COVID-19                            | [CT Segmentation Dataset 3](https://zenodo.org/record/3757476) |

## Overview

This repository consolidates the most significant **COVID-19 imaging datasets** used in the development and evaluation of ML models, with datasets provided in formats such as **CT scans** and **X-rays**. These datasets have been instrumental in advancing the capabilities of **convolutional neural networks (CNNs)**, **U-Net-based models**, and other architectures for tasks such as segmentation and classification.

Most of the resources from the COVID-19 databases referenced in the literature, along with their corresponding articles and code repositories, have been provided in this repository for further research and application. As machine learning continues to play a critical role in enhancing diagnostic capabilities, this repository serves as an accessible resource for professionals in the field.

## How to Use This Repository

This repository can be used for a variety of research tasks, including:

- **Training machine learning and deep learning models** for classification and segmentation tasks.
- **Segmenting COVID-19-affected areas** in medical images using techniques such as **UNet** and **Mask R-CNN**.
- **Developing classification models** using architectures like **DenseNet** and **InceptionV3**.
- Further advancing the diagnostic capabilities of AI-driven tools in the context of medical imaging for COVID-19.

## Future Directions

Based on the current trends and challenges in the application of ML and DL to medical imaging, several future directions can be explored:

1. **Transformer-based models** such as the **Vision Transformer (ViT)** can further improve diagnostic accuracy.
2. **Explainable AI (XAI)** techniques, including **Grad-CAM**, should be integrated to provide transparency and improve clinical applicability.
3. Hybrid models that combine **CNNs** with attention mechanisms could offer enhanced performance in complex medical image analysis tasks.

## Contributions

Contributions are welcome! If you are aware of other relevant publicly available datasets or have improvements to suggest, feel free to create an issue or a pull request.
