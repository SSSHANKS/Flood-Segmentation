
# Flood Area Segmentation in R

This project focuses on performing **image segmentation** to detect **flooded areas** based on provided images and masks.  
The model is trained using a U-Net architecture and evaluated on segmentation accuracy.

The dataset is sourced from [Kaggle: Flood Area Segmentation](https://www.kaggle.com/datasets/faizalkarim/flood-area-segmentation).  

---

## Project Structure

```
.
├── LICENSE
├── flood-segmentation.qmd
├── report-flood-segmentation.html
└── README.md
```

---

## How It Works

- Images and corresponding segmentation masks are loaded from the dataset.
- Preprocessing steps include resizing, normalization, and data augmentation.
- A **U-Net** convolutional neural network is built for pixel-wise classification.
- The model is trained and evaluated on a train/test split of the data.
- Results and segmentation examples are visualized in the final report.

The full workflow is documented in `flood-segmentation.qmd`  
and summarized in `report-flood-segmentation.html`.

---

## Model

- **Architecture**: U-Net
- **Framework**: TensorFlow / Keras
- **Loss function**: Binary Crossentropy
- **Metrics**: IoU Score (Intersection over Union), Accuracy

---

## Technologies Used

- RStudio
- TensorFlow
- Keras
- tidyverse
- magick
- tfdatasets

---

## How to Run


1. Open and run the `flood-segmentation.qmd` file using RStudio environment.

2. Install the required libraries.

3. Alternatively, check the final results directly in the `report-flood-segmentation.html` file.

---

## 📑 Check the Report

A detailed description of the model training, data preprocessing, segmentation results, and evaluation metrics  
is available in the final report:  
👉 **[`report-flood-segmentation.html`](./report-flood-segmentation.html)**

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
