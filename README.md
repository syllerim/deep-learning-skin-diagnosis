# 🧠 Skin Lesion Classification - Deep Learning (HAM10000)

**Author:** Mirellys Arteta Davila

This project is part of the KeepCoding Full-Stack AI Bootcamp III. The goal is to classify skin lesions using the **HAM10000** dataset by combining dermatoscopic images and clinical metadata.

## 🔍 Overview
- Predict skin condition from both images and tabular metadata.
- Use CNNs for image data and dense neural nets for tabular data.

## 🧪 Main Steps

- **Hito 1**: Tabular model with preprocessing and dense layers
  - [1_HAM10000_Tabular.ipynb](https://drive.google.com/file/d/1700jNd9kWJWUuoe1WaGVkooeuVNKF1ru)
- **Hito 2**: Transfer Learning (EfficientNetB0) for image embeddings + classifier.
  - [2_HAM10000_CNN.ipynb](https://drive.google.com/file/d/1axuBL3PSMtHcJZDx1PPcrmIiQ0C6dwQR)
- **Hito 3**: Late Fusion – concatenate predictions from both models.
  - [3_HAM10000_Fusions.ipynb](https://drive.google.com/file/d/1zNWktvnWtASnxH1m615L3-cIl9sOAdc7)
- **Hito 4**: Early Fusion – merge learned embeddings before classification.
  - [3_HAM10000_Fusions.ipynb](https://drive.google.com/file/d/1zNWktvnWtASnxH1m615L3-cIl9sOAdc7)

## ✅ Notes
- Models trained and evaluated on consistent train/val/test splits.
- Accuracy and learning curves reported.

## ⚙️ Requirements
- Python 3.11, TensorFlow/Keras, scikit-learn, pandas, matplotlib
