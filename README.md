
# Flood Area Segmentation

This project focuses on performing **image segmentation** to detect **flooded areas** based on provided images and masks.  
The model is trained using a U-Net architecture and evaluated on segmentation accuracy.

The dataset is sourced from [Kaggle: Flood Area Segmentation](https://www.kaggle.com/datasets/faizalkarim/flood-area-segmentation).  
(Note: the exact source of the original images — satellite or aerial — is unspecified.)

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

- Python
- TensorFlow
- Keras
- OpenCV
- Matplotlib
- Pandas

---

## How to Run

1. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

2. Open and run the `flood-segmentation.qmd` file using Quarto or Jupyter environment.

3. Alternatively, check the final results directly in the `report-flood-segmentation.html` file.

---

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
