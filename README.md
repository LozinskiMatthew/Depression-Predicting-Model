# 🧠 Depression-Predicting-Model

A machine learning model that predicts whether an individual is likely to suffer from depression based on input features.
The project combines data analysis, preprocessing, model development, and performance evaluation into a complete workflow.
---

## 📊 Project Structure

- **`Data_analysis_and_model_testing.ipynb`**  
  A comprehensive notebook that includes:
  - Exploratory data analysis (EDA)
  - Data cleaning and preprocessing
  - Comparison and testing of multiple model architectures

- **`Depression_model.ipynb`**  
  The final, production-ready notebook that:
  - Implements the complete ML pipeline
  - Trains the optimal model
  - Evaluates performance and saves artifacts

---
## 🚀 How to Use

### 🔧 Option 1: Google Colab (Recommended)

If you’re using **Google Colab**, simply upload and run the `.ipynb` file. All dependencies can be installed in Colab via standard commands.

### 💻 Option 2: Local Environment (Anaconda (miniconda) / PyCharm / VSCode)

If running locally, it's recommended to use:

- **Python 3.10** [Install Python](https://www.python.org/downloads/release/python-3100/)
- **Jupyter Notebook** (via Anaconda or IDE-integrated environment like PyCharm) [Install PyCharm Community Edition](https://www.jetbrains.com/pycharm/download/#section=linux)


To set up the required environment, use the provided `requirements.txt` file, that you can find beneath this line, and in project files (within the main directory):

```bash
pip install -r requirements.txt
```

## 📦 Requirements (`requirements.txt`)

Below is the compatible `requirements.txt` content:

    Python          == 3.11.12  
    pandas          == 2.2.2  
    numpy           == 2.0.2  
    matplotlib      == 3.10.0  
    seaborn         == 0.13.2  
    scikit-learn    == 1.6.1  
    xgboost         == 2.1.4  
    optuna          == 4.3.0  
    joblib          == 1.4.2  


> ⚠️ **Note:** The model was developed and tested using the exact versions listed above. While backward compatibility is likely, results may vary with other versions.

If you're using CUDA support, make sure to have the appropriate **PyTorch CUDA wheel** installed for your system:  
👉 [Install PyTorch with CUDA](https://pytorch.org/get-started/locally/)

## 📥 Usage - after proper installation

Download the `Depression_model.ipynb` notebook, launch it in your preferred environment, and follow the cells to:

- Preprocess the data  
- Train the model  
- Evaluate and visualize performance  
- Save the trained model for inference
