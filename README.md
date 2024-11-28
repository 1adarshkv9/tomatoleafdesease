
# Tomato Leaf Disease Classification

This repository contains a Jupyter Notebook that demonstrates how to classify tomato leaf diseases using a deep learning model based on MobileNet. The project leverages transfer learning and TensorFlow to create a lightweight, efficient model suitable for edge deployment.

---

## Features
- **Data Preprocessing**: Includes resizing, normalization, and data augmentation techniques.
- **Model Architecture**: Uses MobileNet for feature extraction with a custom classification head.
- **Evaluation**: Measures accuracy and loss, and provides a classification report.
- **Export Ready**: The model is designed to be compatible with TensorFlow Lite for deployment.

---

## Files
- `Tomato_Leaf_Disease_Classification.ipynb`: Jupyter Notebook containing the entire workflow:
  - Data preprocessing.
  - Model training and evaluation.
  - Conversion to TensorFlow Lite.

---

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Tomato-Leaf-Disease-Classification.git
   cd Tomato-Leaf-Disease-Classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   (Or ensure TensorFlow, NumPy, Matplotlib, and other libraries used in the notebook are installed.)

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Tomato_Leaf_Disease_Classification.ipynb
   ```

4. Add your dataset:
   - Organize it into `train`, `val`, and `test` folders as expected in the notebook.

---

## Dataset Structure
Ensure the dataset follows this structure:
```
dataset/
├── train/
├── val/
└── test/
```

---

## Results
The notebook includes:
- Visualizations of model performance.
- Predictions on test images.
- Export of the trained model.

---

## Example Output
| Input Image         | Predicted Class           |
|---------------------|---------------------------|
| ![Input Image](example.jpg) | `Tomato___Bacterial_spot` |

---

## Acknowledgments
This project is built using TensorFlow and relies on transfer learning to create an efficient model for edge devices. 

Feel free to contribute or report any issues! 😊
