🐶🐱 PRODIGY_ML_03 — Dogs vs Cats Image Classification (SVM)
Prodigy InfoTech Machine Learning Internship — Task 03

📌 Task Description
Implement a Support Vector Machine (SVM) to classify images of cats and dogs.

📂 Dataset
Microsoft Cats and Dogs Dataset
🔗 https://www.microsoft.com/en-us/download/details.aspx?id=54765

🐱 12,500 Cat images
🐶 12,500 Dog images
📁 Total: 25,000 images
🛠️ Tech Stack
Tool	Purpose
Python 3.x	Programming Language
OpenCV (cv2)	Image loading & preprocessing
Scikit-learn	SVM model & evaluation
PCA	Dimensionality reduction
Matplotlib	Visualizations
NumPy	Numerical computations
📁 Project Structure
PRODIGY_ML_03/
│
├── dogs_vs_cats_svm.py        # Main Python script
├── sample_images.png          # Sample cat & dog images
├── class_distribution.png     # Class distribution plot
├── model_results.png          # Confusion matrix & PCA plot
├── predictions.png            # Sample predictions
└── README.md                  # Project documentation
⚙️ How to Run on Google Colab
1. Open Google Colab
Go to https://colab.research.google.com and create a new notebook

2. Enable GPU
Runtime → Change runtime type → T4 GPU → Save

3. Upload and run
Paste the code from dogs_vs_cats_svm.py
Click Run
Upload PetImages.zip when prompted
📊 Model Performance
Metric	Value
Total Images	2,000
Training Set	1,600 images
Testing Set	400 images
PCA Components	100
Accuracy	57.75%
📈 Key Visualizations
Sample Images — 5 cats and 5 dogs from dataset
Class Distribution — Equal distribution of cats and dogs
Confusion Matrix — Model prediction accuracy
PCA Feature Space — Dimensionality reduction visualization
Sample Predictions — Green = correct, Red = incorrect
🔍 Key Findings
SVM with RBF kernel used for image classification
PCA reduced dimensions from 12,288 to 100 components
Model achieved 57.75% accuracy with basic features
Accuracy can be improved using CNN (deep learning)
👤 Author
VIGNESH
Machine Learning Intern — Prodigy InfoTech
🔗 GitHub

📜 License
This project is for educational purposes as part of an internship program.
