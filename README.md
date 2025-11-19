# 🏞️ Landmark Classification & Tagging for Social Media

**Project Overview**  
This project focuses on building a **Convolutional Neural Network (CNN)** to classify landmarks in images. It was completed as part of the [Deep Learning Nanodegree Program](https://www.udacity.com/course/deep-learning-nanodegree--nd101?utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=12907727449_c&utm_term=121152412746&utm_keyword=nanodegree%20deep%20learning_e&gclid=Cj0KCQiAuvOPBhDXARIsAKzLQ8FAvwPPKAF_H4dDtoM72ul1lKBTcQeUHrankyOSeiNxB5F-l5LHvIoaAmsAEALw_wcB) by Udacity.

The goal was to develop a system capable of recognizing landmarks in images, which can be used for **social media tagging, travel recommendations, and image organization**.

---

## 🚀 Project Steps

1. **CNN from Scratch**  
   - Visualized and processed the dataset.  
   - Built a CNN architecture from scratch.  
   - Explained design decisions around data preprocessing and network layers.

2. **CNN with Transfer Learning**  
   - Explored pre-trained models for feature extraction.  
   - Chose the best model for transfer learning to improve accuracy.  
   - Evaluated performance and explained the rationale behind the model choice.

3. **Landmark Prediction Algorithm**  
   - Developed a prediction pipeline using the trained model.  
   - Created a simple interface to input images and receive landmark predictions.  
   - Analyzed strengths and weaknesses of the model.

---

## 🗂️ Dataset
The dataset is a subset of the **Google Landmarks Dataset v2**, available [here](https://www.kaggle.com/google/google-landmarks-dataset).

- **Repository:** [GitHub link](https://github.com/Athari22/Write-an-Algorithm-for-Landmark-Classification)  
- **Folder structure:**  
  - `landmark_project/images/train/00.Haleakala_National_Park`  
  - `landmark_project/images/test`

---

## 🛠️ Skills & Tools
- **Languages & Frameworks:** Python, TensorFlow, Keras, PyTorch (if used)  
- **Deep Learning Techniques:** CNN, Transfer Learning, Image Classification  
- **Data Handling:** Preprocessing, Augmentation, Train-Test Split  
- **Other Tools:** Jupyter Notebook, Matplotlib/Seaborn (for visualization)  

---

## 🌟 Key Achievements
- Built a CNN from scratch for landmark classification.  
- Improved accuracy using transfer learning with pre-trained models.  
- Developed a practical algorithm for predicting landmarks in unseen images.

## 📁 Repository Structure

```
landmark_project/
│
├── images/                  # Dataset images
│   ├── train/               # Training images (organized by landmark class)
│   │   └── 00.Haleakala_National_Park/
│   └── test/                # Test images for prediction
│
├── notebooks/               # Jupyter notebooks for experiments
│   ├── CNN_from_scratch.ipynb
│   └── Transfer_Learning.ipynb
│
├── models/                  # Saved trained models
│   └── best_model.h5
│
├── src/                     # Python scripts
│   ├── data_preprocessing.py
│   ├── train_cnn.py
│   ├── train_transfer.py
│   └── predict.py
│
├── requirements.txt         # Python dependencies
└── README.md
```
