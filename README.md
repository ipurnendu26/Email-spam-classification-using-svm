# Email Spam Classification using SVM

A comprehensive data science project implementing email spam classification using Support Vector Machines (SVM) with complete lifecycle workflow.

## 📋 Project Overview

This project demonstrates a complete data science workflow for email spam classification:
- Business understanding and problem definition
- Exploratory data analysis (EDA)
- Data preprocessing and feature engineering
- Model development and comparison
- Hyperparameter tuning
- Model evaluation and insights

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- VS Code with Jupyter extension (or Jupyter Notebook)

### Installation

1. **Clone or download this repository**

2. **Navigate to the project directory**
   ```bash
   cd "Email-spam-classification-using-svm"
   ```

3. **Activate the virtual environment**
   ```powershell
   # Windows PowerShell
   .\venv\Scripts\Activate.ps1
   
   # Windows Command Prompt
   venv\Scripts\activate.bat
   ```

4. **Verify installation**
   ```bash
   pip list
   ```

### Running the Notebook

1. Open `SVM - Email Classification.ipynb` in VS Code
2. Select the Python interpreter from the `venv` folder
3. Run cells sequentially or use "Run All"

## 📦 Dependencies

- **pandas** (>=2.0.0) - Data manipulation and analysis
- **numpy** (>=1.24.0) - Numerical computing
- **matplotlib** (>=3.7.0) - Data visualization
- **seaborn** (>=0.12.0) - Statistical visualization
- **scikit-learn** (>=1.3.0) - Machine learning algorithms

## 📊 Dataset

Place your `emails.csv` file in the project root directory. The dataset should contain:
- Email features (columns)
- Target variable: `Prediction` (0=Ham, 1=Spam)

## 🎯 Key Features

- ✅ Complete data science lifecycle implementation
- ✅ Multiple model comparison (Logistic Regression, SVM, Random Forest, Naive Bayes)
- ✅ Comprehensive EDA with visualizations
- ✅ Hyperparameter tuning using GridSearchCV
- ✅ Cross-validation analysis
- ✅ ROC-AUC evaluation
- ✅ Business insights and recommendations

## 📈 Project Structure

```
Email-spam-classification-using-svm/
│
├── venv/                           # Virtual environment
├── SVM - Email Classification.ipynb # Main notebook
├── emails.csv                      # Dataset (place here)
├── requirements.txt                # Python dependencies
└── README.md                       # This file
```

## 🔧 Troubleshooting

**Virtual environment not activating?**
- Run PowerShell as Administrator
- Execute: `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`

**Missing dataset error?**
- Ensure `emails.csv` is in the project root directory

**Import errors?**
- Verify virtual environment is activated
- Reinstall packages: `pip install -r requirements.txt`

## 📝 License

This project is for educational purposes.

## 👤 Author

Data Science Team - January 2026
