# 📦 Supply-Chain-Management-Forecasting-Report

## 🚀 Project Overview
This project aims to predict demand in a supply chain using **Neural Networks**. It leverages machine learning techniques to analyze historical data and optimize decision-making in logistics, inventory management, and production planning.

## 📊 Dataset
The dataset consists of key features related to supply chain operations, including:
- **Price**
- **Availability**
- **Number of Products Sold**
- **Revenue Generated**
- **Customer Demographics**
- **Stock Levels**
- **Lead Times**
- **Order Quantities**
- **Shipping Times & Costs**
- **Manufacturing Data** (Costs, Lead Time, Inspection Results, Defect Rates)
- **Product Types** (Cosmetics, Haircare, Skincare)
- **Shipping Carriers & Transportation Modes**
- **Routes**

## 🛠 Tech Stack
- **Python** 🐍
- **TensorFlow/Keras** 🤖
- **Scikit-Learn** 📊
- **Pandas & NumPy** 📈
- **Matplotlib & Seaborn** 🎨

## 🔍 Project Workflow
### **1️⃣ Data Preprocessing**
- Handling missing values
- Encoding categorical features
- Scaling numerical data using `StandardScaler`

### **2️⃣ Exploratory Data Analysis (EDA)**
- Data visualization
- Correlation analysis
- Identifying trends and patterns

### **3️⃣ Model Building**
- Neural Network with:
  - `Dense(128, relu)` → `Dense(64, relu)` → `Dense(32, relu)` → `Dense(1)`
- Loss function: **Mean Squared Error (MSE)**
- Optimizer: **Adam**

### **4️⃣ Model Evaluation**
- **Metric Used:** Mean Squared Error (MSE)
- True vs Predicted values plot

### **5️⃣ Model Deployment**
- Saving the model in **.keras format**
- Loading for future predictions
- Scaling new input data before prediction

## 📈 Results
- The trained model successfully predicts demand with a minimized MSE.
- Helps optimize stock levels, reduce costs, and improve supply chain efficiency.

## 🚀 How to Run the Project
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Model**
   ```python
   python train.py
   ```
4. **Make Predictions**
   ```python
   python predict.py
   ```

## 💡 Future Improvements
- Hyperparameter tuning for better accuracy
- Integration with real-time data sources
- Deployment as a REST API

## 🤝 Contributing
Feel free to fork the repo, submit issues, or create pull requests! 😊

## 📜 License
This project is licensed under the **MIT License**.

---
📌 **Author:** Akash Kumar

