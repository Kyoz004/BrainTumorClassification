
# Brain Tumor Prediction Project

## Introduction
This project focuses on predicting brain tumors using advanced deep learning techniques. The goal is to identify and classify tumors in brain MRI scans, leveraging state-of-the-art models and image processing methods. The system provides accurate predictions, helping healthcare professionals in the diagnosis process.

## Implementation
1. Clone the repository and navigate to the project directory.
2. Ensure all required libraries are installed by running:
   ```
   pip install -r requirements.txt
   ```
3. The main model used in this project is based on convolutional neural networks (CNNs). To change the model configuration, modify the following line in the configuration file:
   ```python
   model.load_weights('model_weights.h5')
   ```
   - Replace `'model_weights.h5'` with the path to your desired model weights.

## Usage
To run the brain tumor prediction script, use the following command:
```bash
python app.py 
```

## Features

- **Tumor Prediction**: Analyze MRI scans to predict whether a brain tumor is present and classify it into specific categories.
  
- **Image Preprocessing**: Automated preprocessing steps including resizing, normalization, and augmentation to improve model accuracy.
  
- **Visualization**: The system generates visual overlays on MRI scans, highlighting tumor regions when detected.

- **Model Training and Evaluation**: Provides training scripts for building and validating models on custom datasets.

- **Output**: Generates prediction results including the classification label, probability score, and visual output (if applicable).

## Libraries Used
1. **argparse**: Command-line argument parsing.
2. **numpy**: Numerical operations.
3. **pandas**: Data manipulation and analysis.
4. **tensorflow/keras**: Deep learning framework used for model creation and training.
5. **opencv-python (cv2)**: Image processing and manipulation.
6. **matplotlib**: Visualization library for plotting and image display.

## Data Preparation
- The dataset used should include brain MRI images categorized based on tumor presence or absence.
- Images should be in a standardized format (e.g., PNG or JPEG) with clear labeling.
- Custom data preprocessing scripts are included in the `data_preprocessing/` directory.

## Contribution
To contribute to the project:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and open a pull request, clearly describing your modifications.

## Authors
- **Nguyễn Công Huy**
- **Đỗ Lý Anh Kiệt**
- **Nguyễn Huỳnh Tú**
