# Canada-Glacier-Data

## Overview
Canada-Glacier-Data is a labeled dataset designed for training deep learning models to classify Antarctic moss on the Canada Glacier. The dataset is structured into training and testing sets and is intended for use with YOLO and other deep learning frameworks in Google Colab.

## Dataset Structure
The dataset is organized as follows:
```
Canada-Glacier-Data/
│-- train/   # Training images and labels
│-- test/    # Testing images and labels
```
Each image in the dataset is annotated to facilitate supervised learning.

## Usage
To utilize the dataset in Google Colab:
1. Upload the dataset to your preferred cloud storage (e.g., Google Drive).
2. Mount the drive in Google Colab:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
3. Access the dataset and integrate it into your YOLO or other deep learning workflows.

## License
This dataset is provided for research and educational purposes. Please ensure proper citation if used in publications.

## Contributions
Contributions and feedback are welcome. Feel free to submit issues or suggestions to improve the dataset.

---
**Maintainer:** Samantha Swift

