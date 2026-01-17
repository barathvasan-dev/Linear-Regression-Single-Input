# 📊 Linear Regression - Single Input Variable

A comprehensive implementation of **Simple Linear Regression** from scratch using gradient descent optimization. This repository contains multiple real-world projects demonstrating linear regression on different datasets.

## 🎯 About The Project

This project implements linear regression algorithm from scratch without using built-in machine learning libraries. It uses:
- **Gradient Descent** for optimization
- **Mean Squared Error (MSE)** as the cost function
- **Jupyter Notebooks** for interactive analysis and visualization

### Key Features
✅ Implementation from scratch (no sklearn for training)  
✅ Multiple real-world datasets  
✅ Visual analysis with matplotlib  
✅ Cost function convergence tracking  
✅ Model evaluation metrics (R², RMSE, MAE)

---

## 📁 Project Structure

```
Linear-Regression-Single-Input/
│
├── datasets/
│   ├── House Price_vs_Area/
│   │   └── HousePricevsArea.csv
│   │
│   ├── salary_experience/
│   │   └── Salary_dataset.csv
│   │
│   └── student_study_hours/
│       └── Student_Performance.csv
│
├── projects/
│   ├── House Price_vs_Area/
│   │   ├── Simple_Linear_Regression.ipynb
│   │   └── results/
│   │
│   ├── salary_vs_experience/
│   │   ├── Simple_Linear_Regression.ipynb
│   │   └── results/
│   │
│   └── student_study_hours/
│       ├── Simple_Linear_Regression.ipynb
│       └── results/
│
├── README.md
├── requirements.txt (to be added)
└── .gitignore
```

---

## 📂 Datasets

### 1. [House Price vs Area](datasets/House%20Price_vs_Area/)
**Dataset**: [HousePricevsArea.csv](datasets/House%20Price_vs_Area/HousePricevsArea.csv)  
**Description**: Predict house prices based on the area (square footage)  
**Features**: Area (sq ft) → Price ($)

### 2. [Salary vs Experience](datasets/salary_experience/)
**Dataset**: [Salary_dataset.csv](datasets/salary_experience/Salary_dataset.csv)  
**Description**: Predict salary based on years of experience  
**Features**: Years of Experience → Salary ($)

### 3. [Student Study Hours](datasets/student_study_hours/)
**Dataset**: [Student_Performance.csv](datasets/student_study_hours/Student_Performance.csv)  
**Description**: Predict student scores based on hours studied  
**Features**: Study Hours → Score (%)

---

## 🚀 Projects

### 1. [House Price Prediction](projects/House%20Price_vs_Area/)
📓 **Notebook**: [Simple_Linear_Regression.ipynb](projects/House%20Price_vs_Area/Simple_Linear_Regression.ipynb)  
📊 **Results**: [View Results](projects/House%20Price_vs_Area/results/)  

Predicts house prices based on area using linear regression.

---

### 2. [Salary Prediction](projects/salary_vs_experience/)
📓 **Notebook**: [Simple_Linear_Regression.ipynb](projects/salary_vs_experience/Simple_Linear_Regression.ipynb)  
📊 **Results**: [View Results](projects/salary_vs_experience/results/)  

Analyzes the relationship between years of experience and salary.

---

### 3. [Student Performance Analysis](projects/student_study_hours/)
📓 **Notebook**: [Simple_Linear_Regression.ipynb](projects/student_study_hours/Simple_Linear_Regression.ipynb)  
📊 **Results**: [View Results](projects/student_study_hours/results/)  

Predicts student exam scores based on study hours.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **NumPy** - Numerical computations
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Jupyter Notebook** - Interactive development environment

---

## 📦 Installation & Setup

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Install Dependencies

```bash
pip install numpy pandas matplotlib jupyter
```

Or create a `requirements.txt` file:
```txt
numpy>=1.19.0
pandas>=1.2.0
matplotlib>=3.3.0
jupyter>=1.0.0
```

Then install:
```bash
pip install -r requirements.txt
```

---

## 🎓 How to Use

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Linear-Regression-Single-Input
   ```

2. **Navigate to a project**
   ```bash
   cd projects/salary_vs_experience
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Simple_Linear_Regression.ipynb
   ```

4. **Run the cells** to see:
   - Data loading and preprocessing
   - Model training with gradient descent
   - Cost function convergence
   - Predictions and visualizations
   - Model evaluation metrics

---

## 📈 What You'll Learn

- ✅ Linear regression mathematics and intuition
- ✅ Gradient descent optimization algorithm
- ✅ Cost function (Mean Squared Error)
- ✅ Model evaluation (R², RMSE, MAE)
- ✅ Data visualization and analysis
- ✅ Making predictions on new data

---

## 📊 Example Output

Each project generates:
- **Regression Line Plot**: Visual fit of the model
- **Cost vs Iterations**: Convergence of gradient descent
- **Predictions**: Model predictions on test data
- **Metrics**: R², RMSE, MAE for model evaluation

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new datasets
- Improve visualizations
- Optimize the algorithm
- Add more evaluation metrics

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

For questions or suggestions, please open an issue in the repository.

---

**Happy Learning! 🚀**
