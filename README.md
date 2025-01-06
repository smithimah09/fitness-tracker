# **Fitness Tracker - Barbell Exercise Classification**  

This project is a full machine learning pipeline that classifies barbell exercises using accelerometer and gyroscope data from a MetaMotion sensor. The project covers every step from raw data processing to building predictive models, including a custom algorithm for counting repetitions.  

---

## **Project Overview**  

### **Part 1: Introduction and Dataset Setup**  
- Explored the MetaMotion sensor for data collection and reviewed the dataset structure.  

### **Part 2: Data Preprocessing**  
- Converted raw accelerometer and gyroscope data into usable formats.  
- Read and split data from CSV files into training and testing sets.  
- Performed initial cleaning to handle missing or noisy values.  

### **Part 3: Data Visualization**  
- Plotted time-series data to identify patterns and trends in exercise movements.  
- Visualized accelerometer and gyroscope signals for insights into exercise variations.  

### **Part 4: Outlier Detection**  
- Applied outlier detection methods, including Chauvenet’s criterion and Local Outlier Factor (LOF), to remove anomalies.  

### **Part 5: Feature Engineering**  
- Extracted features like signal frequency and applied low-pass filtering to reduce noise.  
- Reduced feature dimensionality using Principal Component Analysis (PCA).  
- Explored clustering methods to group similar exercises for exploratory analysis.  

### **Part 6: Predictive Modeling**  
- Built and evaluated multiple machine learning models:  
  - **K-Nearest Neighbors (KNN):** Leveraged distance-based classification for its interpretability and simplicity.  
  - **Naive Bayes:** Explored its probabilistic approach for quick classification.  
  - **Support Vector Machines (SVM):** Applied kernel-based techniques for separating non-linear classes.  
  - **Random Forest:** Used ensemble learning for robust predictions.  
  - **Neural Networks:** Implemented a basic feedforward neural network to capture complex patterns.  
- Optimized model hyperparameters and evaluated performance using accuracy, precision, recall, and F1-score.  

### **Part 7: Repetition Counting**  
- Designed and implemented a custom algorithm to count exercise repetitions using accelerometer and gyroscope signals.  

---

## **Technologies and Tools**  
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn  
- **Sensors:** MetaMotion accelerometer and gyroscope  
- **Machine Learning Models:** KNN, Naive Bayes, SVM, Random Forest, Neural Networks  
