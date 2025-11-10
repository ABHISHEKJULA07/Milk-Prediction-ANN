# Milk Quality Grade Prediction using ANN (Windows Setup)

# 1) Create virtual environment
python -m venv venv

# 2) Activate environment
.\venv\Scripts\activate

# 3) Install required libraries
pip install kagglehub ipykernel numpy pandas scikit-learn matplotlib seaborn tensorflow

# 4) Export dependencies
pip freeze > requirements.txt

# 5) Create Kaggle folder & add kaggle.json (place manually)
mkdir .kaggle
# -> Copy your kaggle.json into .kaggle folder

# 6) Launch notebook
jupyter notebook
# -> Open and run main.ipynb
