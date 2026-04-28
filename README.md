#  Deepfake Detection using Xception + SVM
> A machine learning-based system for detecting deepfake images using hybrid techniques.

##  Overview
This project focuses on detecting deepfake images using a hybrid approach that combines deep learning feature extraction with classical machine learning classification.
The entire implementation is developed in a single Jupyter Notebook for simplicity and experimentation.

##  Methodology
The project follows a structured pipeline:
1. **Preprocessing**
   - Image resizing (224x224)
   - Normalization of pixel values

2. **Feature Extraction**
   - Pre-trained Xception model
   - Extracts high-level spatial features from images

3. **Classification**
   - Support Vector Machine (SVM)
   - Classifies images as **Real** or **Fake** based on extracted features

4. **Evaluation**
   - Model performance measured using accuracy

##  Project Structure
```
DeepfakeProject/
│
├── DeepFake Mini Project.ipynb
├── requirements.txt
└── README.md
```


## 📊 Dataset
- Deepfake dataset from Kaggle  
- Contains:
  - Real images
  - Fake (manipulated) images  

⚠️ Dataset is not included due to size limitations.

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- NumPy
- Matplotlib

## ▶️ How to Run the Project

1. Clone the repository: git clone https://github.com/laharisha1120/deepfake-detection.git
2. Install dependencies: pip install -r requirements.txt
3. Open the notebook: DeepFake Mini Project.ipynb
4. Run all cells step-by-step

## 📈 Results
- Successfully distinguishes between real and fake images  
- Demonstrates effectiveness of combining deep features with SVM  

## 🔮 Future Improvements
- Real-time deepfake detection  
- Video-based deepfake analysis  
- Integration with Autoencoder-GAN (AGAN)  
- Deployment using web frameworks

##  Author
**Laharisha Surya**

## Note

This project is implemented in a notebook format for experimentation.  
The same pipeline can be modularized into production-level code.
