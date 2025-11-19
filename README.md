# Industrial-Bearing-Fault-Diagnosis

This project develops a complete vibration-based machine learning system for diagnosing **8 bearing fault conditions** using **2,048 accelerometer signals** obtained from an SKF tapered roller bearing testbed. The goal is to build a predictive maintenance pipeline capable of identifying roller, inner-race, outer-race, and compound defects.

---

## 🔍 Project Overview
- **Data Source:** Vibration signals measured under 8 bearing states  
- **Samples:** 2,048 training files, 512 test files  
- **Tools:** MATLAB, Signal Processing Toolbox, ML Toolbox  
- **Objective:** Build ML classifiers to detect fault types in rotating machinery  

---

## 🛠 Methods

### 1. **Signal Processing & Feature Engineering**
- RMS  
- Standard Deviation  
- Skewness  
- Mean Absolute Value (MAV)  
- Peak Frequency  
- 1× and 2× Harmonics  
- FFT-based spectral features  

### 2. **Dimensionality Reduction**
- Principal Component Analysis (PCA)  
- Feature Importance Ranking  

### 3. **Machine Learning Models**
- Support Vector Machine (SVM)
- Random Forest (RF)
- K-Nearest Neighbors (KNN)
- Self-Organizing Maps (SOM)

### 4. **Validation**
- Confusion matrices  
- 5-fold cross-validation  
- Accuracy benchmarking across multiple models  

---

## 📈 Results

| Model | Accuracy | Notes |
|-------|----------|-------|
| SVM | **99.65% (CV)** | Best generalization |
| RF | **99.60% (CV)** | High stability |
| KNN | **99.51% (CV)** | Improved with reduced feature set |
| SOM | **100% (final)** | Improved from 97.85% → 100% via new harmonic-based features |

---

## 💡 Key Takeaways
- Advanced feature engineering massively improves classifier performance  
- SOM becomes highly accurate with the right reduced feature set  
- MATLAB is powerful for vibration analytics and industrial AI workflows  
- Predictive maintenance can be built efficiently with classical ML models  

---

## 📎 Files Included
- MATLAB code (feature extraction, PCA, classification models)  
- Dataset structure  
- Figures, confusion matrices, plots  
- Full technical report  

---

## 📚 Domains
- Predictive Maintenance  
- Industrial AI  
- Signal Processing  
- Condition Monitoring  
- Mechanical Diagnostics  

---

## 👤 Author
Sudhanshu Dubey  
Data Analyst & Data Scientist specializing in Machine Learning, MATLAB analytics, and industrial data systems.
