# Brain Tumor Mri Transfer Learning

Brain tumor MRI classification with PyTorch transfer learning.

## What it does

Classifies MRI slices (7,023 images across glioma, meningioma, pituitary and no-tumor classes) with transfer learning. Includes EDA of class balance and image sizes.

## Files

- `brain_tumor_mri_transfer_learning.ipynb`

## Tools

PyTorch, torchvision, scikit-learn, pandas, matplotlib, seaborn, kagglehub

## Dataset

[Brain Tumor MRI Dataset (Kaggle)](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

The dataset is not included in this repo.

## Results

The saved notebook copy has no recorded metrics. Run it to reproduce them.

## How to run

1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies: `pip install -r requirements.txt`.
3. Download the dataset from the link above (some notebooks fetch it with `kagglehub`, which asks for Kaggle credentials) and update the data path if needed.
4. Run all cells.

## Author

Mark Ayman
