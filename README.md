# Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used for training and testing was obtained from Kaggle: [Credit Card Fraud Detection Dataset 2023](https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023). The dataset contains 30 numerical features, suspected to be transformed using Principal Component Analysis (PCA), but no feature descriptions are available.

## 🎯 Project Goal
- Build an effective fraud detection model.
- Handle class imbalance in the dataset.
- Train, evaluate, and fine-tune various machine learning models.
- Assess the feasibility of deploying the model in real-world scenarios.

## 📊 Dataset Information
- **Source:** Kaggle
- **Features:** 30 numerical columns (V1, V2, ..., V30)
- **Target Variable:** Binary (0 = Legitimate, 1 = Fraudulent)
- **Challenge:** Lack of feature descriptions, making real-world deployment difficult

## 🔧 Technologies Used
- **Programming Language:** Python
- **Libraries:** Sklearn, NumPy, Pandas, Matplotlib, Seaborn, PyTorch
- **ML Models Tested:** Logistic Regression, Decision Trees, Random Forest (Best Model)

## 🏆 Best Model - Random Forest Classifier
After testing multiple models, **Random Forest Classifier** was found to be the most effective:
- **Training Accuracy:** 99.98%
- **Testing Accuracy:** 99.94%
- **Training Loss:** 0.49
- **Testing Loss:** 1.04
- **Cross-validation Accuracy:** 99.93%
- **Feature Importance:** The most important features were V17, V16, V2, V21, and V9.

## 🚧 Limitations & Deployment Challenge
While the model performs exceptionally well on the dataset, it **cannot be deployed in real-world conditions** due to:
- The dataset lacking proper feature descriptions.
- PCA-transformed features making it unclear what real-world input values would be.
- The need for actual banking transaction features for real deployment.

## ✅ How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/RohitXJ/Credit-Card-Fraud-Detection.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook (`Fraud-Detection.ipynb`) to see the full training process.

## 📝 Future Improvements
- Use a dataset with clearly defined transaction features.
- Experiment with deep learning techniques like autoencoders or anomaly detection.
- Implement real-time fraud detection using streaming data.

---
📌 **Note:** This project is for learning purposes only and is not intended for real-world financial fraud detection.

📢 **Contributions & Feedback:** Feel free to contribute or suggest improvements! 🚀

