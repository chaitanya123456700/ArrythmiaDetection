# Arrhythmia Detection using Hybrid DenseNet + CNN

## Overview
This project presents a hybrid deep learning model for automated ECG heartbeat classification using a combination of **1D Convolutional Neural Networks (CNN)** and **DenseNet**. The system is trained on the **MIT-BIH Arrhythmia Database** and compares the performance of multiple machine learning and deep learning models to identify the most effective approach for arrhythmia detection.

---

## Features
- ECG heartbeat classification
- Hybrid 1D DenseNet + CNN architecture
- Comparison of multiple models
- High classification accuracy
- Data preprocessing and heartbeat segmentation
- Comprehensive performance evaluation

---

## Dataset
- **Dataset:** MIT-BIH Arrhythmia Database
- ECG signals are segmented into individual heartbeats around R-peaks.
- Multiple heartbeat classes are used for classification.

---

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- WFDB
- Jupyter Notebook / Google Colab

---

## Models Compared

| Model | Accuracy |
|--------|----------|
| CNN | 99.14% |
| DenseNet | 98.60% |
| Random Forest | 98.40% |
| **Hybrid DenseNet + CNN** | **99.17%** |

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Project Structure

```text
Arrhythmia-Detection/
│── dataset/
│── preprocessing/
│── models/
│   ├── cnn.py
│   ├── densenet.py
│   ├── hybrid_model.py
│── train.py
│── evaluate.py
│── requirements.txt
│── README.md
```

---

## Installation

```bash
git clone https://github.com/your-username/Arrhythmia-Detection.git
cd Arrhythmia-Detection

pip install -r requirements.txt
```

---

## Usage

Train the model:

```bash
python train.py
```

Evaluate the trained model:

```bash
python evaluate.py
```

---

## Results

The proposed **Hybrid DenseNet + CNN** model achieved the highest accuracy among all evaluated models by combining the feature extraction capabilities of CNN with the dense connectivity of DenseNet.

---

## Future Work
- Real-time ECG monitoring
- Explainable AI (Grad-CAM)
- Web application deployment
- Mobile application integration
- Support for additional ECG datasets

---

## License

This project is intended for educational and research purposes.

---

## Author

**Chaitanya Reddy**  
B.Tech Artificial Intelligence & Data Science  
Amrita Vishwa Vidyapeetham
